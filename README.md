# End-to-End-Chest-Disease-Classification


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml





## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)



##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/chest-Disease-Classification-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=entbappy \
MLFLOW_TRACKING_PASSWORD=6824692c47a4545eac5b10041d5c8edbcef0 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/chest-Disease-Classification-MLflow-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9353c5b10041d5c8edbcef0

```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)



# AWS-CICD-Deployment-with-Jenkins

## 1. Login to AWS console.

## 2. Create IAM user for deployment

	#Policy:

	1. AmazonEC2ContainerRegistryFullAccess

	2. AmazonEC2FullAccess

	


