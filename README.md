## Data Scientist Udacity Nanodegree: Recommendation Engines.

### Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)


## 1. Introduction <a name="introduction"></a>

This project will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they might like. 

### Project Overview

1. Exploratory Data Analysis
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Not provided in this project.
5. Matrix Factorization


## 2. Installation <a name="installation"></a>

Everything will run with a Python 3.x version.
It is necessary to install libraries to run the code in Anaconda. The necessary libraries are included in the files. See also MY Github repository: [https://github.com/SebastianHess/Recommendation_Engines](https://github.com/SebastianHess/Recommendation_Engines)


## 3. Project Motivation<a name="motivation"></a>

#### I. Exploratory Data Analysis

Before making recommendations of any kind, it is necessary to explore the data for the project. There are some basic, required questions to be answered about the data throughout the rest of the notebook. 

#### II. Rank Based Recommendations

To get started in building recommendations, it is required to find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles which could be recommended to new users.

#### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, it is necessary to look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users.

#### IV. Not provided in this project.

#### V. Matrix Factorization

Finally, the project completes in a machine learning approach to building recommendations. Using the user-item interactions, a matrix decomposition will be build out. Using the decomposition will show how well it is possible to predict new articles an individual might interact with 

[Source of content](https://learn.udacity.com/nanodegrees/nd025/parts/cd0019/lessons/ls11961/concepts/36397974-66bf-4662-b49a-935745c0fe87 "Source of content")


## 4. File Descriptions <a name="files"></a>

### File structure
```
- data
| - articles_community.csv
| - user-item-interactions.csv

- project_tests.py
- README.md
- Recommendations_with_IBM.html
- Recommendations_with_IBM.ipynb
- top_5.p
- top_10.p
- top_20.p
- user_item_matrix.p
```

## 5. Results<a name="results"></a>

MY Github repository: [https://github.com/SebastianHess/Recommendation_Engines](https://github.com/SebastianHess/Recommendation_Engines)



## 6. Licensing, Authors, Acknowledgements<a name="licensing"></a>

* Thanks to my employer for enabling me to take the Udacity Nanodegree and for supporting me.
* Thanks to Udacity for the amazing [Data Scientist Nanodegree Programm](https://www.udacity.com/course/data-scientist-nanodegree--nd025).