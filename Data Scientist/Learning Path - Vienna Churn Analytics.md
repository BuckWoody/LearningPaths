# Learning Path - Customer Churn Prediction using Vienna

## Audience: Data Scientist, Developer, Architect
## Type: Solution

### Summary
The aim of this solution is to demonstrate predictive churn analytics using Vienna. This solution provides an easy to use template to develop churn predictive data pipelines for retailers. The template can be used with different datasets and different definitions of churn. Retailers can avoid customer churn by using these predictions combined with proper marketing strategies. 


### Lesson Path

| Objective |	Concept	| Technologies | Level | Pre-Requisites | Ignite Deliverable
| --- |	---	| --- | ---  | ---  | --- 
| Data Preparation: Ingestion | Perform ingestion of user information and activity data using datasource wizard. Modify .dprep for performing customization of data prepreation steps.| Vienna | Intermediate | Python | Tutorial
| Data Preparation: Data Cleaning and Merging | Using custom scripts functionality in the datasource wizard, perform deduping, resolve missing values and join datasets using Transforms feature of the datasource wizard | Vienna | Intermediate | Python | Tutorial
| Data Preparation: Churn Labeling | Add column to perform label dataset (churners/non-churners) using either code snippet or GUI features of the datasource wizard | Vienna | Intermediate | Python | Tutorial
| Data Preparation: Feature Engineering | Generate derived features using 'Derive column by example' in the wizard or code snippets as scripts | Vienna | Intermediate | Python | Tutorial
| Experimentation and Model Building: Churn Classification | Integrate third-party libraries (such as scikit-learn and azureml) to develop regression and tree based classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Experimentation and Model Building: Parameter Sweeps for Churn Classification | Perform parameter sweeps by triggering the execution from the previous step to identify "best model" | Vienna | Intermediate | Python | Tutorial
| Compare churn models | Evaluate different classifiers for predicting churn | Vienna | Intermediate | Python (including external libraries) | Tutorial
| Operationalization and consumption of Churn models | Deploy the churn models either either locally or remotely. Pass realtime commands utilizing az ml service | Vienna, Azure CLI , Azure Machine Learning CLI component | Intermediate | Python | Tutorial
