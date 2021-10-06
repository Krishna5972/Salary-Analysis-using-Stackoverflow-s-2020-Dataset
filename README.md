# Salary-Analysis-using-Stackoverflow-s-2020-Dataset
Analyzing Stackoverflow’s 2020 Dataset to answer a few questions regarding Salary

In this project we use data from Stackoverflow’s 2020 Annual Developer Survey, to answer few questions about salary in different reigions.
1. *What is the average salary in different Regions for IT professionals?*
2. *Will a Professional degree or Master’s degree help me to get a good salary?*
3. *How is the average salary varied between Small sized organizations and Established Big Companies in different regions?*
## Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation
For this project, I was interestested in using Stack Overflow data from 2020 to better understand about how salary is being varied in different regions.

## Data Understanding
Stackoverflow’s 2020 Annual Developer Survey Dataset is used to answer the questions, the dataset can be found here. The survey data covers over 6000 samples. The survey's objective is to study about various aspects related to IT professionals.
There were 62 questions as a part of the survey.You can the dataset from [here](https://insights.stackoverflow.com/survey).

## Exploratory Data Analysis
Data set has Dataset comprises of 64461 observations and 61 different columns.All the missing values are dropped.We could have filled the missing values with mean but in all the questions we are calculating average.For continuous/numeric features no matter how many times we add mean, it still gets conserved.

## Libraries

This project made the use of common Python libraries:
```
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns 
```

## Business Questions

### Question 1: *What is the average salary in different Regions for IT professionals?*
### Question 2: *Will a Professional degree or Master’s degree help me to get a good salary?*
### Question 3: *How is the average salary varied between Small sized organizations and Established Big Companies in different regions?*

## Results
The main findings of the code can be found at the post available here

## Acknowledgements
Licensing for the Stack Overflow data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/aitzaz/stack-overflow-developer-survey-2020).
