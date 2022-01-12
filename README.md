#### Aim
The aim of the project is to build a graphical model using Bayesian Belief Network to identify whether a patient has heart disease or not. The dataset used is Cleveland Clinic heart disease dataset. The dataset consists of 303 records across 14 attributes with one of the attribute showing presence (1,2,3,4) or absence (0) of heart disease. The graphical model will be used for classification. I will also be learning parameters and structure of the model from data. So the two techniques that I will be discussing in this project will be:

- Technique 1: Learning parameters on a given model structure
- Technique 2: Learning the structure of the model from data
 
Below are the main steps I will pe performing:

i. The dataset will be inspected for data quality, issues like missing values and conversion of attribute values from continuous to discrete etc. will be handled.

ii. Learning model parameters using MaximumLikelihood Estimator and Bayesian Estimator. The hyperparameters will be tuned and the resulting best model on the basis of log likelihood score will be trained.

iii. Learning the structure of the network using Hill-Climb Search Algorithm. Different scoring methods will be evaluated to get the best network structure. We will then be learning the CPTs from the data and model will be trained.

iv. Testing will be performed on the models identified in ii. and iii. and the best model will be identified using appropriate performance metrics.

#### Objective
Objective 1: To develop a graphical model using Bayesian Belief Network to classify whether a patient has heart disease or not

Objective 2: Learn the model parameters using different techniques like Maximum Likelihood Estimator and Bayesian Estimator

Objective 3: Learn the structure of the network using different scoring techniques of Hill-Climb Search Algorithm
