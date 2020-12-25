# Udacity Data Science Project 1

This repository contains the code I wrote for tackling project 1 in the Data Scientist Nanodegree by Udacity.

## Used Packages
* Numpy
* Pandas
* Matplotlib
* Scikit-learn

## Files in the project
* Analysis.ipynb
Jupyter notebook containing the analysis
* Data folder
Folder containing the data used for this analysis.

## Motivation for the project

As an active learner it is important for me to always keep learning. At the same time, I don't think it's always valuable to learn just for the sakes of learning, but to have a clear goal in mind. 

Using the Stackoverflow Surveys I want to find out, where I could focus my learning for it to have an impact on my future salary.

## Business Understanding
### Questions Answered

The following questions are to be answered:

**Question 1**<br>
How well can I predict my own salary, using the answers I would give to the survey.

**Question 2**<br>
Which coefficients does my linear regression use to predict a salary and which of these could I use myself to increase my salary in the future.

**Question 3**<br>
Using the 2020 survey, which are the data focussed programming languages and frameworks that I could focus my learning on.

## Data Understanding
### Dataset

In this project I used the [Stack Overflow Annual Developer Survey 2017 & 2020](https://insights.stackoverflow.com/survey) from [Stack Overflow](https://stackoverflow.com). It contains the survey answers from the annual developer surveys of said years.

## Preparation of data

The data was cleaned by dropping all completely null columns and filling the remaining NaNs in numeric columns with the mean of the column as well as getting dummy values for the categorical columns.
The answers of the author were attached to the original dataset.

## Modelling

A linear regression model was trained with a subset of the full dataset. The optimal size of this subset was found by running a grid search on the subset size.

## Evaluation

It was found that the authors salary can be predicted quite accurately.
A couple of important coefficients were discussed, but it was further focussed the fact that it seems to be important to learn several programming languages and frameworks.
After looking at the 2020 survey data, a couple of decisions were made on which frameworks and languages the author will focus:
* Deepen my knowledge in Python
* Get into Spark for big data
* Learn Julia (because I think it’s interesting)
* Learn C## (because I have an Arduino lying around and also: why not)

## Deployment

The code can be run with Jupyter Notebooks after cloning the repository without any further requirements. It uses Python 3.

## Built With

* [Jupyter Notebook](https://jupyter.org) - Used for coding and documentation


## Authors

* **Robert Offner**
