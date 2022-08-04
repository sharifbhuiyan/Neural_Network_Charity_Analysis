## **<h1 align="justify"> Neural_Network_Charity_Analysis**
  	
---
## Overview of the project: 
<p align="justify">The purpose of the project to help Alphabet Soup foundation to predict where to make investments. To perform analysis on applicant datasets getting from foundation, a deep-learning neural networks model with the TensorFlow platform in Python has been created. <p>
	
---

<p align="justify">This project consists of four technical analysis deliverables. <p>

- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model
- Deliverable 4: A Written Report on the Neural Network Model (README.md)
	

### Resources
- Data Source: [charity_data.csv](https://github.com/sharifbhuiyan/Neural_Network_Charity_Analysis/blob/main/Resources/charity_data.csv)
- Software: Python 3.7 and accompanying Anaconda package, Conda 4.8.4, Jupyter Notebook

## Data Preprocessing:
	
<p align="justify">

- As part of the data preprocessing, at first the non-beneficial ID columns 'EIN' and 'NAME' have been dropped.
- Since “IS_SUCCESSFUL” column contains binary data which is our decision column, has been considered as a target variable for neural network.
- Remaining columns are considered as categorical variable. The OneHotEncoder has been used to perform fit and transform the categorical variables. After that encoded categorical variables have been split into training and testing datasets.
	
<p>	

	
## Compiling, Training, and Evaluating the Model:
	

- Two hidden layers have been made for our model are 80 and 30. And the output layer has been made of single neuron.
- In order to increase the speed of training process, an activation function for input layers “relu” has ben used and “sigmoid” for output layer.
- To compile the model, “adam” as the optimizer and “binary_crossentropy” as the loss function has been used. 
- The average model accuracy is 73% which was not satisfactory to get the outcome. To boost up the performance, several initiatives have been taken, like increase the number of neurons, increase the number of layers, different activation function. The ultimate result is, we got the same performance as like before. 
	
	
## Summary:
- Since we achieved 73% accuracy on an average, whereas we need at least 75% accuracy, that deep learning neural network model is not appropriate for better performance. It would better try with  supervised machine learning model like Random Forest Classifier.
