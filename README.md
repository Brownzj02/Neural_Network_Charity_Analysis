# Neural Network Charity Analysis

In this analysis, we are analyzing a csv file with over 34,000 organizations that have received funding from Alphabet Soup. Creating a neural model network, we are attempting to determine and/or predict how sucessful future applicants can be. Alphabet Soup wants to utilize this data to vet which organizations they will donate to in the future to reduce the amount of funds misused. 

## Results:

- Data Preprocessing
  - The IS_SUCCESSFUL column is the column we are focusing on for the predictions.
  
- Below are the features considered for my model
  - APPLICATION_TYPE          
  - AFFILIATION               
  - CLASSIFICATION            
  - USE_CASE                  
  - ORGANIZATION              
  - INCOME_AMT                
  - SPECIAL_CONSIDERATIONS 
  
- The dropped columns "EIN" and "NAME" have been removed from the input data.

## Compiling, Training, and Evaluating the Model:

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - There are four hidden layers in total. The first hidden layer contains 80 neurons and the second contains 30.
  
- Were you able to achieve the target model performance?
  - In this analysis we were not able to obtain target performance of 75%, falling short at 69.83%.
  
- What steps did you take to try and increase model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
