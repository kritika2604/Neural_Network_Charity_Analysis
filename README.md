# Neural_Network_Charity_Analysis
Module 19: Neural Networks and Deep Learning Models

# Overview of the analysis: 

This project uses machine learning and neural networks, the features in the provided dataset to help creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Resources : 
[Alphabet Soup Charity dataset](https://github.com/kritika2604/Neural_Network_Charity_Analysis/blob/main/Resources/charity_data.csv)

This CSV contains data for more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

# Results: 
## Data Processing
- Target variables for the model - "IS_SUCCESSFUL" column
- The features of the model: All independent variables (columns), except the target variable and the columns EIN and NAME.

## Compiling, Training, and Evaluating the Model
- Hidden layers used: 2  activation model of ReLU for hidden layers and sigmoid funciton for output layer as input data is positive nonlinear for binary classification.
<img width="384" alt="image" src="https://user-images.githubusercontent.com/94858846/171048137-a79d2434-a872-46be-8ceb-cbfca99a1f1f.png">

**Model has loss of 56.21% and accuracy of 72.51%**

I was unable to reach the target model performance in this case. 


 
