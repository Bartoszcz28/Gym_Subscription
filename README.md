# Gym Subscription Analysis Project

![image](https://github.com/Bartoszcz28/Gym_Subscription/assets/82092858/0e581b8f-4015-4e2e-b944-3be255261468)

## Project Description
This project aims to analyze gym subscription data and predict which potential customers are likely to purchase a gym membership. We utilize customer data, such as age, gender, hobby, and other factors, to create a predictive model for potential customers.

## Project Objectives
The primary objectives of this project are:

- Predicting which customers are more inclined to purchase a gym membership.
- Optimizing marketing efforts and tailoring offers to customer needs.
- Understanding the factors influencing customer purchase decisions regarding gym subscriptions.

## Repository Contents
- **GymSubscription**: Main data analysis file.
- **Data_Impout_hobby**: The file in which contains ways to fill in missing data for the hobby variable. 
- **data**: A folder containing the input data for the project.
- **models**: A folder containing the project-trained models.

## Authors
- Bartosz Czarnecki

## Sample Results


### The project includes:
* Import libraries and dataset
* Descriptive analysis of the data
* Feature engineering, data cleaning
    * Division of the dataset into training and test datasets
    * Handling missing data
* Logistic Regression
* XGBoost
* Decision trees
* Decision trees with RFE
* Suport Vector Machine (SVM)

As a result of the analysis, we discovered that the target group is single men, a group with the highest ratio of exercising to non-exercising people. Unfortunately, based on hobbies and occupation, we are not able to determine whether advertising should be targeted at this group, because the data on hobbies and occupation are too varied to clearly determine their influence on whether a person exercises at the gym.

The highest accuracy was achieved using the XGBoost model was about **86%**.

In the diagram below we can also observe that the number of acquaintances that a person has is also very important, most people in the target group have about 200 friends.

![output](https://github.com/Bartoszcz28/Gym_Subscription/assets/82092858/9a7e6525-162d-403e-b4bb-3d6897983d51)


