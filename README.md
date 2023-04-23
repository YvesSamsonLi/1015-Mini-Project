# 1015-Mini-Project
This is a repository for our mini project


## Practical Motivation

According to the singapore heart foundation, cardiovascular disease (heart disease and stroke) represents 32% of global deaths annually. Singapore has seen a increase of death due to cardiovascular disease as well. (Singapore Heart Foundation,2021)

It was found by the Centre of disease control and prevention that there are many factors as to why one may develop heart disease. 

As a major health hazard to the population and something that can happen to anyone, we want to understand how other health factors as well as lifestyle habits might influence the risk of one getting heart disease.

## Sample Collection

Dataset is from Kaggle: https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system?select=2015.csv 

This dataset is taken from the Behavioral Risk Factor Surveillance System(BFRSS) survey conducted by the Centre of Disease Control(CDC) yearly in the United States. The survey is conducted over telephone to gather the data on the health status and conditions of the US residents.

This dataset has a variety of variables and hence we have chosen to see if an individual has heart disease based on their health metrics. The dataset has many columns of data, however many of them are duplicates or are very similar and hence here are our chosen variables.

The dataset is high reliable and trustworthy as it is taken from Centre for Disease control and prevention which is a government agency in the United States of America.

## Data
In this section, we will mention our data, and what was the question asked to obtain this data.

### Numerical:

**Physical Health** - Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good?

**Alcohol consumption** - During the past 30 days, how many days per week or per month did you have at least one drink of any alcoholic beverage such as beer, wine, a malt beverage or liquor?

**Mental Health** – Thinking about your mental health, for how many days during the past 30 days was your mental health not good? (0-30 days)

**Age** - Age

### Categorical

**General Health** – Would you say that in general your health is...

**Exercise Rate** - During the past month, other than your regular job, did you participate in any physical activities or exercises such as running, calisthenics, golf, gardening, or walking for exercise? 

**High Cholesterol** – Have you EVER been told by a doctor, nurse or other health professional that your blood cholesterol is high?

**High Blood Pressure** – Have you EVER been told by a doctor, nurse, or other health professional that you have high blood pressure?

**Gender** –  Gender

**Smoking Rate** – Do you now smoke cigarettes every day, some days, or not at all?

**Kidney Disease** – (Ever told) you have kidney disease? Do NOT include kidney stones, bladder infection or incontinence.

**Asthma** – (Ever told) you had asthma?

**Skin Cancer** – (Ever told) you had skin cancer

**Heart Attack** – (Ever told) you that you had a heart attack also called a myocardial infarction?

**Stroke** – (Ever told) you had a stroke?

**Checkup** - About how long has it been since you last visited a doctor for a routine checkup? A routine checkup is a general physical exam, not an exam for a specific injury, illness, or condition.

**Difficulty walking** - Do you have serious difficulty walking or climbing stairs?

**Heart Disease(response)** - (Ever told) you had angina or coronary heart disease?

We have a total of 20 variables, __ of it are numerical while the rest are categorical.

## Problem formulation
​
**Problem statement:** What are some important health factors or life habits in determining the risk of having a heart disease?
​
We want to link the different health factors and habit of individuals and use it to determine the risk of getting heart disease.
​
We will train a model to determine if an individual has heart disease or not. From that, we will be able to analyse the data and siphon out any important information from the different predictors that we have used. From this, we can find its correlation and determine if that health factor or individual habits, is important in relation to heart disease.

## Data Preparation

Our dataset has roughly 300 variables. However, we have reduced this to 18 variables as many of the data is either a duplicate or a very similar question asked to respondents. From the remaining dataset, we chose a variety of health factors as well as life habits of the individuals.

The dataset has a mixture of numerical and categorical data. However, there are much more categorical data than numerical. Many of the categorical data are numbered and hence we had to replace them with their original metric.

We have done this and displayed the data cleaning with graphs to make it easier to visualize

## 2. Data Cleaning

In this section, we will be cleaning the data. Here are some of the steps that will be taken.

1. Selection of variables
2. Renaming of variables
3. Removal of NULL data
4. Removal of duplicate data
5. renaming of categorical variable values
