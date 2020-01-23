# Kickstarter Fundraising Prediction
## Problem Identification
Firstly, we want to identify what factors on the Kickstarter website presentation will influence the success of project.
Secondly, we want to build a model to predict whether a certain project will succeed or fail. 
Finally, we would like to discuss how fund raisers can increase their fund raised by modifying these attributes.

## Data Acquisition
We used Kaggle dataset as our main source: https://www.kaggle.com/parienza/kickstarter. 

This dataset contains 45814 data points and 17 variables which are project id, name, url, category, subcategory, location, status (successful, failed, live, canceled, or suspended), goal (target amount), pledged (actual pledged amount), funded percentage (pledged / goal), backers, funded date, levels (the number of reward levels), reward levels (the reward amount in each level, separated by comma), updates (the number of information or activity updates created by project initiator), comments and duration.

Additionally, we crawled additional information as needed from Kickstarter website using Beautiful Soup, including the video length and number of FAQs of each project. Moreover, since the data is created in 2012, we update some afterwards data to the ongoing project in dataset and cross-validating the raw data.

## Modeling
1. Logistic Regression
2. Trees
3. Linear Regression

# Analysis
Most important features that determine the success of a crowdfunding project:
1. Number of updates of recent production process and new designs during the crowfunding process
2. The rationality of target fundraising amount
3. Number of comments
4. Average rewards promise for a successful crowdfunding
5. Duration of the crowdfunding period
