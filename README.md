# Overview of the project

# Architectural Diagram
![plot](./images/Architecture.PNG)
<p align="center">Figure 1: Architectural Diagram</p>

# Main steps
## Step 1: Authentication
I skip this part because I am using Udacity provided lab.

## Step 2: Automated ML Experiment
In this step, I built an AutoML experiment using the bank marketing data. 
Figure 2-1 shows the bank marketing dataset has been uploaded to the Azure ML Studio and is available for model training use.
![plot](./images/2-1.PNG)
<p align="center">Figure 2-1: Bank Marketing Data</p>
![plot](./images/2-2.PNG)
Figure 2-2 shows the created AutoML experiment has completed.
<p align="center">Figure 2-2: AutoML Experiment Status</p>
Figure 2-3 shows the best model from the AutoML experiment.
![plot](./images/2-3.PNG)
<p align="center">Figure 2-3: Best Model</p>

## Step 3: Deploy the Best Model
Figure 3 shows the best model has been deployed in the Azure AutoML Studio.
![plot](./images/2-3.PNG)
<p align="center">Figure 3: Deployed Best Model</p>

## Step 4: Enable Application Insights
Figure 4-1 shows the application insights has been enabled for the deployed model so the logging can be tracked.
![plot](./images/4-1.PNG)
<p align="center">Figure 3: Application Insights Enabled</p>
Figure 4-2 shows the logs has been captured for the deployed model.
![plot](./images/4-2.PNG)
<p align="center">Figure 3: Captured Logs</p>

## Step 5: Swagger Documentation
Figure 5 shows the swagger documentation.
![plot](./images/4-2.PNG)
<p align="center">Figure 3: Captured Logs</p>

## Step 6: Consume Model Endpoints
## Step 7: Create, Publish and Consume a Pipeline

# Future improvement
# Screencast link
<a href="https://www.google.com/" target="_blank">Screencast video</a>

# Dataset
https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv


