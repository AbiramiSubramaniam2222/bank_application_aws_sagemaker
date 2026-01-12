
**Bank Application – AWS SageMaker Deployment
Overview**

This project demonstrates how a Machine Learning model can be trained, deployed, and monitored using AWS SageMaker. The notebook walks through an end-to-end ML workflow, focusing on cloud deployment rather than only local model training.

The goal of this project is to understand how ML models are productionized on AWS using managed services like SageMaker.

**Key Objectives**

Understand AWS SageMaker architecture

Train a machine learning model on SageMaker

Deploy the model as a real-time endpoint

Perform inference using the deployed endpoint

Monitor logs and performance using AWS tools

**Technologies Used**

Python

AWS SageMaker

Amazon S3

IAM Roles

Jupyter Notebook

Scikit-learn

**Workflow**

**1)Data Preparation**

Load and preprocess the dataset

Upload data to Amazon S3

**2)Model Training**

Configure SageMaker training job

Train the model using managed infrastructure

**3)Model Deployment**

Deploy the trained model as a SageMaker endpoint

Enable real-time predictions

**4)Inference****

Send input data to the endpoint

Receive predictions from the deployed model

**Monitoring**

View logs using CloudWatch

Track endpoint performance

**What I Learned**

How SageMaker manages training and deployment without manual server setup

How IAM roles and permissions are required for secure access

How models are deployed as scalable endpoints

The difference between demo deployments and production-ready setups.

**Future Improvements**

Add model versioning

Enable data drift monitoring

Add CI/CD pipeline for automated deployment

Improve security and cost optimization

##This project was used to practically explore AWS SageMaker workflows, including model training, deployment, and monitoring.
