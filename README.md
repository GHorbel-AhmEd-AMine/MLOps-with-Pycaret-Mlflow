# MLOps-with-Pycaret-Mlflow
Integrating MLOps in our machine learning experiments using PyCaret and MLflow 


## PyCaret
 
1) PyCaret is an open-source, low-code machine learning library and end-to-end model management tool built-in Python for automating machine learning workflows. It is known for its ease of use, simplicity, and ability to quickly and efficiently build and deploy end-to-end ML prototypes.

2) PyCaret is an alternate low-code library that can replace hundreds of code lines with few lines only. This makes the experiment cycle exponentially fast and efficient.

![image](https://user-images.githubusercontent.com/39995021/174984290-9f100186-6ef3-46a1-ae16-6d0b8450c655.png)


## MLflow
 
MLflow is an open-source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry. MLflow currently offers four components:


![image](https://user-images.githubusercontent.com/39995021/174984383-c66e5d50-f33e-45c4-8b9a-a96d522f47b1.png)


## The machine learning lifecycle

-- Business Problem — This is the first step of the machine learning workflow. It may take from few days to a few weeks to complete, depending on the use case and complexity of the problem. It is at this stage, data scientists meet with subject matter experts (SME’s) to gain an understanding of the problem, interview key stakeholders, collect information, and set the overall expectations of the project.

-- Data Sourcing & ETL — Once the problem understanding is achieved, it then comes to using the information gained during interviews to source the data from the enterprise database.

-- Exploratory Data Analysis (EDA) — Modeling hasn’t started yet. EDA is where you analyze the raw data. Your goal is to explore the data and assess the quality of the data, missing values, feature distribution, correlation, etc.

-- Data Preparation — Now it’s time to prepare the data model training. This includes things like dividing data into a train and test set, imputing missing values, one-hot-encoding, target encoding, feature engineering, feature selection, etc.

-- Model Training & Selection — This is the step everyone is excited about. This involves training a bunch of models, tuning hyperparameters, model ensembling, evaluating performance metrics, model analysis such as AUC, Confusion Matrix, Residuals, etc, and finally selecting one best model to be deployed in production for business use.

-- Deployment & Monitoring — This is the final step which is mostly about MLOps. This includes things like packaging your final model, creating a docker image, writing the scoring script, and then making it all work together, and finally publish it as an API that can be used to obtain predictions on the new data coming through the pipeline.

![image](https://user-images.githubusercontent.com/39995021/174984773-a70dd153-cd4a-437c-9564-a82aab4744e6.png)



## What is MLOps?
 
MLOps is an engineering discipline that aims to combine machine learning development i.e. experimentation (model training, hyperparameter tuning, model ensembling, model selection, etc.), normally performed by Data Scientist with ML engineering and operations in order to standardize and streamline the continuous delivery of machine learning models in production.

![image](https://user-images.githubusercontent.com/39995021/174985130-f2e173b0-6da3-4fc5-8001-478b77300639.png)
![image](https://user-images.githubusercontent.com/39995021/174985060-f7d90837-6387-4b8c-9bbd-d52e8c7960cc.png)
![image](https://user-images.githubusercontent.com/39995021/174985001-04b4b9ad-20ca-46e7-ae25-0630b76b84fe.png)
![image](https://user-images.githubusercontent.com/39995021/174984847-4a7befe4-b618-4308-b204-b2fdb2d00e3d.png)


## Référence : 

[Pycaret example](https://www.kdnuggets.com/2021/05/easy-mlops-pycaret-mlflow.html)
