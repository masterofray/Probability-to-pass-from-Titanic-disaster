# Titanic Problem from Kagle

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of **Machine 
Learning** to predict which passengers survived the tragedy.

## Workflow stages

The **Problem workflow** goes through seven stages described in the Data Science Solutions book.

1. Question or problem definition.
2. Acquire training and testing data.
3. Wrangle, prepare, cleanse the data.
4. Analyze, identify patterns, and explore the data.
5. Model, predict and solve the problem.
6. Visualize, report, and present the problem solving steps and final solution.

The workflow indicates general sequence of how each stage may follow the other. However there are use cases with exceptions.

- We may combine mulitple workflow stages. We may analyze by visualizing data.
- Perform a stage earlier than indicated. We may analyze data before and after wrangling.
- Perform a stage multiple times in our workflow. Visualize stage may be used multiple times.
- Drop a stage altogether. We may not need supply stage to productize or service enable our dataset for a competition.

## Question/Problem Definition

**Predict for any passenger survived the sinking of the Titanic or not from feature data given.**
For each in the test set, we must predict a 0 or 1 value for **die** or **survive**, respectively.

##### Note :
Knowing from a training set of samples listing passengers who survived or did not survive the Titanic disaster, can our model determine based on a given test dataset not containing the survival information, if these passengers in the test dataset survived or not.

##### Highlights :
- On April 15th, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. Translated 32.5% survival rate.
- One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. *If we know number of lifeboats in every deck or number of jacket in every room, it may help us to determine this causal to surviving probability*.
- Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class. This said that there is anomali in the fact instead of first assumption : *all people have same change to suviving*.

## Workflow goals

The data science solutions workflow solves for seven major goals.

- **Classifying**
- **Correlating**
- ~~Converting~~
- **Completing**
- **Correcting**
- **Creating**
- **Charting**

## Tutorials Machine Learning:

We have some tutorials from Kagle to use Machine Learning :

1. Use pandas for data manipulation
2. Use matplotlib and seaborn for data visualization
3. Learn to build models with scikit-learn
4. Use cross-validation to make sure your model generalizes to new data (i.e., it doesn’t "overfit")
5. The basics of feature engineering and data visualization
6. How to deal with missing values in the dataset
7. How to train a random forest classifier to make a prediction
8. Use parameter tuning and grid search to select the best performing model out of several different classification algorithms 
9. Learn how to the extremely popular XGBoost algorithm
10. Use the fundamental skill of "ensembling" to combine the predictions of several models
11. Use a visualization of a decision tree algorithm to compare different models
12. Determine how features contribute to prediction accuracy