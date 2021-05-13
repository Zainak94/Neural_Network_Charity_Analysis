# Neural_Network_Charity_Analysis
# Overview of the analysis: 
The purpose of this analysis was to create a neural network model which will determine whether applicants will be successful if they are funded by Alphabet Soup. There are 34000 organizations that have received funding from Alphabet soup over the years. The data set contains the following: 

•	EIN and NAME—Identification columns

•	APPLICATION_TYPE—Alphabet Soup application type

•	AFFILIATION—Affiliated sector of industry

•	CLASSIFICATION—Government organization classification

•	USE_CASE—Use case for funding

•	ORGANIZATION—Organization type

•	STATUS—Active status

•	INCOME_AMT—Income classification

•	SPECIAL_CONSIDERATIONS—Special consideration for application

•	ASK_AMT—Funding amount requested.

•	IS_SUCCESSFUL—Was the money used effectively.

# Results: 

## Data Preprocessing:

We have targeted for the model is “IS_Successful” Flag. 

These are the features used for the model: 

•	APPLICATION_TYPE—Alphabet Soup application type

•	AFFILIATION—Affiliated sector of industry

•	CLASSIFICATION—Government organization classification

•	USE_CASE—Use case for funding

•	ORGANIZATION—Organization type

•	STATUS—Active status

•	INCOME_AMT—Income classification

•	SPECIAL_CONSIDERATIONS—Special consideration for application

•	ASK_AMT—Funding amount requested.

•	EIN - for identification purposes.

•	Name column was removed from the dataset. I have encountered some of the issues while checking the accuracy of my model. 

## Removing EIN and Names Column: 

![Neural_Network_Charity_Analysis](https://github.com/Zainak94/Neural_Network_Charity_Analysis/blob/main/Resources/HiddenLayer1.PNG).

![Neural_Network_Charity_Analysis](https://github.com/Zainak94/ Neural_Network_Charity_Analysis/blob/main/Resources/Accuracy1.PNG).

## Compiling, Training, and Evaluating the Model

•	I have added 3 layers. Tried it with 2 layers as well but then did 3 layers.   

![Neural_Network_Charity_Analysis](https://github.com/Zainak94/Neural_Network_Charity_Analysis/blob/main/Resources/HiddenLayers2.PNG).

![Neural_Network_Charity_Analysis](https://github.com/Zainak94/Neural_Network_Charity_Analysis/blob/main/Resources/HiddenLayer3.PNG).

•	I was unable to achieve the accuracy of the model. I wanted to try couple of ideas, but I was unable to go through them due to memory error. I had to remove name to process the accuracy. I tried removing some of the other columns from the data set so I can achieve the accuracy, but the main 2 columns were EIN and Name. I tried removing EIN but due to memory error my model could not run. 

![Neural_Network_Charity_Analysis](https://github.com/Zainak94/Neural_Network_Charity_Analysis/blob/main/Resources/Accuracy2.PNG).

# Summary: 

Overall, this project was a bit challenging for me due to some issues, but I believe if I were able to run the model by dropping EIN column, I would be able to achieve accuracy. Adding layers helps the accuracy. 

