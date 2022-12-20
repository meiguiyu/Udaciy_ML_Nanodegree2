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
Figure 2-2 shows I created an AutoML experiment using the bank marketing data set and it has completed.
<p align="center">Figure 2-2: AutoML Experiment Status</p>
Figure 2-3 shows the best model is able to be retrieved from the AutoML experiment.
![plot](./images/2-3.PNG)
<p align="center">Figure 2-3: Best Model</p>

## Step 3: Deploy the Best Model
In this step, I deployed the best AutoML model.
Figure 3-1 shows the best model has been displayed with explanation enabled in the Azure AutoML Studio.
![plot](./images/3-1.PNG)
<p align="center">Figure 3-1: Best Model</p>
Figure 3-2 shows the best model is being deployed using ACI with authentication enabled in the Azure AutoML Studio.
![plot](./images/3-2.PNG)
<p align="center">Figure 3-2: Deploying Best Model</p>
Figure 3-3 and 3-4 show the best model has been deployed successfully in the Azure AutoML Studio.
![plot](./images/3-3.PNG)
<p align="center">Figure 3-3: Deployed Best Model1</p>
![plot](./images/3-4.PNG)
<p align="center">Figure 3-4: Deployed Best Model2</p>

## Step 4: Enable Application Insights
In this step, I enabled the logging for the deployed model.
Figure 4-2 shows the application insights has been enabled for the deployed model so the logging can be tracked.
![plot](./images/4-2.PNG)
<p align="center">Figure 4-2: Application Insights Enabled</p>
Figure 4-3 and 4-4 show the logs has been captured for the deployed model.
![plot](./images/4-3.PNG)
<p align="center">Figure 4-3: Captured Logs1</p>
![plot](./images/4-4.PNG)
<p align="center">Figure 4-4: Captured Logs2</p>

## Step 5: Swagger Documentation
In this part, I set up swagger to consume the model endpoint.
Figure 5-2 shows the swagger docker is up and running.
![plot](./images/5-2.PNG)
<p align="center">Figure 5-2: Swagger docker</p>
Figure 5-4 and 5-5 show the swagger.sh and serve.py files are running.
![plot](./images/5-4.PNG)
<p align="center">Figure 5-4: API service1</p>
![plot](./images/5-5.PNG)
<p align="center">Figure 5-5: API service2</p>
Figure 5-6 shows the API content for the deployed model.
![plot](./images/5-6.PNG)
<p align="center">Figure 5-6: API content</p>

## Step 6: Consume Model Endpoints
In this step, I used swagger to consume the model endpoint.
Figure 6-2 shows the API endpoint and primary are updated using the deployed model.
![plot](./images/6-2.PNG)
<p align="center">Figure 6-2: Endpoint.py</p>
Figure 6-3 shows the returned response from the endpoint using a sample intput payload.
![plot](./images/6-3.PNG)
<p align="center">Figure 6-3: Consume model endpoint</p>

## Step 7: Create, Publish and Consume a Pipeline
In this part, I created, published, and consumed a pipeline for the created experiment.
Figure 7-1 and 7-2 show a pipeline has been created for the yum-experiment in the jupyter notebook and has been running successfully.
![plot](./images/7-1.PNG)
<p align="center">Figure 7-1: Create a pipeline1</p>
![plot](./images/7-2.PNG)
<p align="center">Figure 7-2: Create a pipeline2</p>
Figure 7-4 and 7-5 show the pipleline has been published successfully with an active status.
![plot](./images/7-4.PNG)
<p align="center">Figure 7-4: Published pipeline1</p>
![plot](./images/7-5.PNG)
<p align="center">Figure 7-5: Published pipeline2</p>

# Future improvement
# Screencast link
<a href="https://www.youtube.com/watch?v=ukJf9IzUs34" target="_blank">Screencast video</a>

# Dataset
https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv


