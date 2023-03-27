# Neural_Network_Charity_Analysis

- Overview of the analysis
- Alphabet Soup is a lending company. In order to determine if applicants will receive funding machine learning and neural networks were used. 

- Results

- Data Preprocessing
- What variable(s) are considered the target(s) for your model?
- 
  The main variable of focus IS_SUCCESSFUL was the objective for this model.
 


- What variable(s) are considered to be the features for your model?
-
  Additional variables that were the focus of this model was 
  
  APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS.

- What variable(s) are neither targets nor features, and should be removed from the input data?

  Two variables were dropped  from the model EIN and NAME.

- Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

Three neurons and three layers were used for testing purposes.

1st attempt 90, 40, 20

2nd attempt 70, 15, 15

3rd attempt 50, 25, 25

Relu was selected because it runs faster. Sigmoid was choosen for testing purposes as well. The goal was to reach or exceed 75% accuracy.

- Were you able to achieve the target model performance?

No
- What steps did you take to try and increase model performance?

Adding a third layer and changing the numbers to reach 75% proved to be unsuccessful. 


- Summary 
 The DeepLearning_Tabular is recommended because it reached 87% accuracy with very little loss.
 
 
