# Real-time Fraud Dectection


2019 MSBA 6330 / MSBA 6320 Trends Marketplace

**Real-time Anomaly Detection Using Amazon Sagemaker, Lambda, and Quicksight**

Group members: Zheming Lian, Jiahui Jiang, Shunshun Miao, Pahal Patangia, Fazel Tabassum, Chuchen Xiong


## Project Description

Our team focuses on anomaly detection that is a technique used to identify rare items, events, or observations which raise suspicion by differing significantly from most of the data you are analyzing. There are a wide range of applications in different industries including abnormal purchases in retail, cyber intrusions in banking, fraudulent claims in insurance, unusual machine behavior in manufacturing, and even detecting strange patterns in network traffic that could signal an intrusion. We will use Credit Card Fraud dataset from Kaggle to apply anomaly detection. We will use Amazon SageMaker to train the model offline, predict the streaming data and store it in S3, and update the model based on new data. After getting the prediction, we use Quicksight to vizualize the result and use SNS to send notification to users.

## Handout

## Files

**1.fraud-detection-using-machine-learning.template**

Set up the configuration in CloudFormation

**2.sagemaker_fraud_detection.ipynb**

Train the model in Sagemaker

**3.fraud_testing_resample.ipynb**

Prepare the steaming data to predict

**4.creditcard_sample.csv**

Sample data

## Inference

https://s3.amazonaws.com/solutions-reference/fraud-detection-using-machine-learning/latest/fraud-detection-using-machine-learning.pdf
