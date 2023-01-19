# Neural_Network_Charity_Analysis

## Project Overview

AlphabetSoup is a non-profit foundation that raise and donate funds to organizations in different areas. Since not every donation is impactful, I'll be using neural network model to predict with requests are worth donating and which are high risk. Using this model, AlphabetSoup will be able to evaluate diffetent inputs to produce clear decision making results to where make the investments. 
The purpose of this project is to create a binary classifier that is capable of predicting if applicants will be successful, is they are funded by the company. 


## Results

# *Data Preprocessing*
- What variable(s) are considered the target(s) for your model?
The variable columns IS SUCCESSFUL is the target for this model.
- What variable(s) are considered to be the features for your model?
The feature variables of this model are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMN, SPECIAL_CONSIDERATIONS, and ASK_AMT. 
- What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME variables should be removed from the input data. 
# *Compiling, Training, and Evaluating the Model*
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

![](/Images/1.png)

- Were you able to achieve the target model performance?
The original model only achieved 72.61% accuracy with the loss of 55.6% which is not desirable for predicting the outcome of the funding. 

- What steps did you take to try and increase model performance?

I tried to optimize the original model with 5 different approaches:
1 - Dropping more columns. 
2 - Adding more neurons to the hidden layes.
3 - Adding more hidden layers.
4 - Increasing and decresing the number of epochs. 
5 - Using other activation functions on the hidden layers. 

After different attempts, I could not reach the desired 75% accuracy for the model. 

## Summary

The neural network model wasn't able to reach the desired 75% accuracy in predicting the outcome of funding. I recommend using another machine learning model such as 
Supervised Random Forest Classifier since they can work on tabular and nonlinear data.  




