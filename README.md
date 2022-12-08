# Neural_Network_Charity_Analysis

# Overview
	The purpose of the analysis of this data is to determine what factors determine whether an applicant charity will be successful if funded with Alphabet Soup.

# Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
## Data Preprocessing
-	The IS_SUCCESSFUL variable is used as a target
-	The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT are used as features for the model
-	The EIN and Name variables are neither features not targets and are removed from the model
## Compiling, Training, and Evaluating the Model
- I used three deep layers with 36, 18, and 9 neurons respectively. I used a sigmoid activation function as the target goes between 0 and 1. 
- I was unable to achieve the target model performance.
- To achieve the model performance, I tried changing the number of neurons, changing the number of hidden layers, and changing the activation function. 
# Summary
The model was able to predict if an application would be successful about 72% of the time. 
## Recommendation
I would recommend using a Logistic Regression model on the data as it will make it easier to understand what factors influence successful applications and there are not enough features to make the complexity of a neural network model worth it.
