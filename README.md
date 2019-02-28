## AIM	: To Identify the People's opinion on mobile phones Like or Unlike using Perceptron over 91mobiles.com datasets.
	: ( PadhAI: Perceptron - Like Unlike Classification )
	: ( Can you tell whether a mobile phone will be LIKED by people or NOT? )

### Author	
		: caffeine110
		: Kaggle : Gaurav Gahukar, UG73HQV8Q


### Introduction
This is a Solution for PadhAI Competition hosted on Kaggle.
This code Is Not the Actual code Submited on Kaggle, It is optimised and well organised. 
This problem is solved using the Perceptron Model.

### Task :
The goal is to identify the people's opinion on mobile phones using Perceptron.
The data points are scraped from 91mobiles.com

### Keywords 
Keywords : Perceptron Model, Data Analysis, Satastics, Numpy, Pandas.

## Tools
PreRequirements :
		 LIBRARIES	: Pandas,Numpy, Sklearn, matplotlib, csv.
		 IDE		: Spyder, Jupyter
###
Abstract

## procedure to run
Procedure : 
	Open the kernel04a6252e21.ipynb file.
	This file Includes Code with a proper documentation


## Evaluation Plan
As this is a Logistic Regression problem
We have to find Accurracy_Score using Sklearn.Metrics

Model Accuracy for Training dataset :  0.7536656891495601 

Accuracy on Public Test Dataset is : 0.80000

Accuracy on Private Test Dataset  : 0.86904


### key Metrics :
Mean Square Error (MSE)—
	It is the mean of the square of the errors.

Absolute errorse(AE)—
	It is a difference between two continues variables


## Optimisation :

### Parameter Tuning
	Tuned No of epoches from 100 to 15000
	Learning Rate from 0.1 to 0.0001

	Initial Accuracy Score when model starts learning >>
		Model Accuracy at epoch No. 0 is : 0.6217008797653959 
		Model Accuracy at epoch No. 1 is : 0.6920821114369502

	Is Optimised to >>
		Model Accuracy at epoch No. 14998 is : 0.750733137829912 
		Model Accuracy at epoch No. 14999 is : 0.7536656891495601

	Model Accuracy for Training dataset :  0.7536656891495601 
	Accuracy on Public Test Dataset is : 0.80000
	Accuracy on Private Test Dataset  : 0.86904

