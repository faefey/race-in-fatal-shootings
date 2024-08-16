# Predicting Race From Fatal Shooting Data

For a quick overview of the project and its results, check out the [presentation](presentation.pptx). For more details, refer to the [project notebook](project.ipynb).

## Fatal Force in the US

In the United States, use of deadly force by police has been a high-profile and contentious issue. A thousand people are shot and killed by US cops each year. The ever-growing argument is that the US has a flawed law enforcement system that costs too many innocent civilians their lives. In this project, I examine the role of race in fatal police shootings in the US.

## Dataset

The [Fatal Police Shootings in the US (2015-2020)](https://www.kaggle.com/datasets/andrewmvd/police-deadly-force-usage-us/data) dataset was used in this project. Specific data cleaning steps were taken upon downloading the dataset.

## Exploratory Data Analysis

I explored the following questions with the help of visualizations:

* Which state has the most fatal police shootings? Which city is the most dangerous?

* What is the most common way of being armed?

* What is the age distribution of the victims? Compare the age distribution of different races.

* Compare the total number of people killed per race. Compare the proportion of people killed per race. What difference do you observe?

## Modeling

After preprocessing the data, I applied three machine learning models (logistic regression, k-nearest neighbors, and decision tree) to explore whether it is possible to predict the race of a victim based on other features.