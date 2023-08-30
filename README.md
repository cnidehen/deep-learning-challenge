# deep-learning-challenge
Module 21 Challenge

Source Data:  

deep-learning-challenge/Resources/charity_data.csv at main · cnidehen/deep-learning-challenge (github.com)

Primary Project Notebook: 

deep-learning-challenge/deep_learning_challenge.ipynb at main · cnidehen/deep-learning-challenge (github.com)

Optimization Notebook: 

deep-learning-challenge/AlphabetSoupCharity_Optimisation.ipynb at main · cnidehen/deep-learning-challenge (github.com)

Saved Models: 

deep-learning-challenge/Results at main · cnidehen/deep-learning-challenge (github.com)




# Overview

The deep-learning-challenge was designed to predict whether applicants will be successful if funded by nonprofit Alphabet Soup. Neural net deep learning model was used to analysis the 34,000 organisations that have received funding from Alphabet Soup over the years.
Tensorflow Keras was used to complete the analysis generating highly accurate outcome. It was used to build and compile a neural net model based on the number of features with the number of layers and neurons set and generated 73.8% accuracy.

# Variables

•	EIN and NAME—Identification columns

•	APPLICATION_TYPE—Alphabet Soup application type

•	AFFILIATION—Affiliated sector of industry

•	CLASSIFICATION—Government organisation classification

•	USE_CASE—Use case for funding

•	ORGANIZATION—Organisation type

•	STATUS—Active status

•	INCOME_AMT—Income classification

•	SPECIAL_CONSIDERATIONS—Special considerations for application

•	ASK_AMT—Funding amount requested

•	IS_SUCCESSFUL—Was the money used effectively


# Result

•	Preprocessing

1.	The only target variable in the dataset is IS_SUCCESSFUL.
2.	These features were used for the analysis- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
3.	EIN and NAME are identifications for the specific businesses that received funding over the year.
   
•	Compiling, Training, and Evaluating the Model

1.	I used 3 hidden layers for the optimisation after the initial two did not achieve 75% target point.The neurons were varied according to desired epection of 75% target result. Relu and sigmoid were interchangebly used at diffrenet optimisation point. 
3.	The model reached a target accuracy of 73.8%.

# Summary

The overall best predictive accuracy of 73.8% is close to the target of 75%, but it is still not quite there. These could have been as a result of 
•	that the attempted optimization methods for the model were not rigorous enough.
•	It is also possible that some of the feature variables are not actually contributing to the model's accuracy. 
•	Also, possible that the model is overfitting the training data. By taking these steps, we can improve the accuracy of the TensorFlow model and achieve the target of 75% or higher.

