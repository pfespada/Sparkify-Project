# Sparkify-Project
DSND Capstone Project

### Index

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Files](#files)
4. [Conclusion](#Conclusion)
5. [Acknowledgements](#acknowledgements)
6. [Contribution](#contribution)


## Installation <a name="installation"></a>

For using this notwbook you must have the following python liberies installed:

Python

Pyspark

Numpy (https://docs.scipy.org/doc/numpy/user/install.html)

Pandas (https://pandas.pydata.org/pandas-docs/stable/install.html)

Matplotlib (https://matplotlib.org/users/installing.html)

Seaborn (https://seaborn.pydata.org/installing.html)


## Project Motivation<a name="motivation"></a>

This is a project made for the final capstone Udacity project for the Data Scientist Nanodegree.

The motivation of this project is to make a Machine Learning model to predict the Churn in a streaming music app ( 
fictional).

I made this project using a Users log dataset of two month where basic information about user is contained as well as informationa about the interactions in each session. 

So I made a EDA in order to undertand the data and then selected the most relevante features in order to use them in the ML model to predict when a user will cancell his account.


## Files <a name="files"></a>

**Sprakify .ipynb** Noteboock of this proyect. In this file you will find the code and analysis of this project

## Conclusion

As a conclusion I wouls say that to predict Churn is not a simple task and needs to be studied carrefully from the features to the models.
From a model standpoint, the three models got a similar accuracy which indicates that these models don’t predict many churn as this dataset is very unbalanced.
However based on the results of the tunning we could say that there is potencial to be improved by playing with the hyperparameters.
As mentioned, the feature has been selected by me but some other could be selected in order to do others tries in further studies. In this case Thumbs Down, NextSongs and AddFriends are the Top3 in features importance.

I post a blog with details of this project. Click the following link to go to [here](https://medium.com/@omtripathi88/customer-churn-prediction-with-pyspark-on-sparkify-data-48ef24c8e08a).


## Acknowledgements <a name="acknowledgements"></a>
I want to thank UDACITY for the oportunity of doing this project in the Data Scientist ND

## Contribution <a name="contribution"></a>
Contributions are welcome!! In case you are interesting to contribute please contact me.
