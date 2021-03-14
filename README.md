# Titanic ML competition

## Introduction

In this competition, we are expected to use some machine learning techniques to predict which passengers survived the Titanic shipwreck.

the dataset is from Kaggle compatition. The data has been split into two groups: **Train** and **Test** sets.

This competition is known as ***Titanic*** which is an on-going competition.

On April 15, 1912, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we are asked to build a predictive model(s) that answer the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

The training set is used to build the machine learning models. Our model will be based on “features” like passengers’ gender and class. We may also use feature engineering to create new features.

The test set is used to see how well our model performs on unseen data. For each passenger in the test set, we use the trained model to predict whether or not the passengers survived the sinking of the Titanic.

## Data set

The data set includes features as follows:

**survival:**	binary-class includes survival	passengers (0 = died, 1 = survived)

**pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

**sex:** Sex

**Age:** Age in years

**sibsp:** number of siblings / spouses aboard the Titanic

**parch:** number of parents / children aboard the Titanic

**ticket:** Ticket number

**fare:** Passenger fare

**cabin:** Cabin number

**embarked:** Port of Embarkation	(C = Cherbourg, Q = Queenstown, S = Southampton)

## Outline

The work will be done in 6 major steps as follows:

1. Import libraries and packages
2. Describe the train and test set (descriptive analytics)
3. Prepare data for modelling (data preprocessing, feature engineering, feature selection)
4. Predictive modelling (modelling, model evaluation, model selection)
5. Get the test set and make it ready-to-use (preparation)
6. Create Submission File to Kaggle Competition

**Note:** In this project, the ground truth for test set is not available. So, the model selection phase is considered as the model evalution score. In this case, the best model would be selected based on the best evaluation score.

## Final Result

The best accuracy score obtained in this project is around 0.83 using *XGBoost* model. This score achieved the top 2% among all competitors in this worldwide competition!
