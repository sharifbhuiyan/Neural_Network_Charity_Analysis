# Neural_Network_Charity_Analysis

## **<h1 align="justify"> Credit_Risk_Analysis**
  	
---
## Overview of the project: 
<p align="justify">In this project, we use Python to build and evaluate several machine learning models to predict credit risk.
We adopted the following procedure:
. <p>
	
---

<p align="justify">This project consists of four technical analysis deliverables. <p>

- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis
	

### Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Python 3.7 and accompanying Anaconda package, Conda 4.8.4, Jupyter Notebook

## Random Over Sampler model:
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS1.png
</p>  
	

- Calculation of the confusion matrix.
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS2.png
</p>  
		
- Imbalanced classification report

<p align="center">	
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS3.png
</p>  
	

- The balanced accuracy score is 62%. The high_risk precision is about 1% only with 60% sensitivity which makes a F1 of 2% only. Low_risk precision is almost 100% with a sensitivity of 68%.

	
	
	
## SMOTE model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM1.png
</p>  
	
- Calculation of the confusion matrix.

<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM2.png
</p>  

- Imbalanced classification report
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM3.png
</p>  
	

- The balanced accuracy score is 65%. The high_risk precision is about 1% only with 64% sensitivity which makes a F1 of 2% only. Low_risk precision is almost 100% with a sensitivity of 66%.
	

## ClusterCentroids model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL1.png
</p>  
	
- Calculation of the confusion matrix	
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL2.png
</p>  
	
- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL3.png
</p>  
	

- The balanced accuracy score is 51%. The high_risk precision is about 1% only with 57% sensitivity which makes a F1 of 1% only. Low_risk precision is almost 100% with a sensitivity of 45%.
	
## SMOTEENN model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn1.png
</p>  
	
- Calculation of the confusion matrix	
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn2.png
</p>  
		
- Imbalanced classification report
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn3.png
</p>  
	

- The balanced accuracy score is 62%. The high_risk precision is about 1% only with 69% sensitivity which makes a F1 of 2% only. Low_risk precision is almost 100% with a sensitivity of 54%.
	

## BalancedRandomForestClassifier model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR1.png 
</p>  
	
- Calculation of the confusion matrix
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR2.png
</p>  

- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR3.png
</p>  
	

- The balanced accuracy score is 79%. The high_risk precision is about 4% only with 67% sensitivity which makes a F1 of 7% only. Low_risk precision is almost 100% with a sensitivity of 91%.
	
## EasyEnsembleClassifier model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC1.png
</p>  
	
- Calculation of the confusion matrix	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC2.png
</p>

- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC3.png
</p>  
	

- The balanced accuracy score is 93%. The high_risk precision is about 7% only with 91% sensitivity which makes a F1 of 14% only. Low_risk precision is almost 100% with a sensitivity of 94%.
