
# Data Engineering project | Market Basket Analysis Project
The following project is a Data Engineering project on Big Data and creating the data pipelines to make sure that the specific persona gets the required data. The platforms used are Amazon S3 (Storage purpose) and Apache Spark DataBricks (Compute purpose). The python module by the name PySpark is heavily used for data reading, writing and transformation. Three personas that this project covers are Data Engineer, Data Scienctist and Business Analyst. Data Engineer is reposnsible for creating and modifying the flow and access to the data for two other personas. The Cleaned and final notebooks are following:
_Notebooks as per the different personas:_
- [Business Analyst Notebook Link](https://github.com/nvyas1-git/Data-Engineering-Project/blob/main/BusinessAnalystNotebook.ipynb)
- [Data Engineer(Testing) Notebook Link](https://github.com/nvyas1-git/Data-Engineering-Project/blob/main/DataEnggtest_notebookS3.ipynb)
- [Data Scientist Notebook Link](https://github.com/nvyas1-git/Data-Engineering-Project/blob/main/DataScientistNotebook.ipynb)

__As the data is read from Amazon S3 storage, the credentials file is kept abstracted. For reproducing the same project, required changes are necessary while mounting S3 bucket.__

# Dataset Description
The dataset is about the events occurred on an e-commerce website by different users. There are mainly three types of events (View, Cart, Purchase). There are other features on the events such as time, commodity etc. The data of the span of two months (Oct and Nov) is of 15 GB. In this project we have covered a single month. The source of the dataset is [here](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store). 

# Business Question/Problem Statement
Predicting the presence of matter (Drug/ Alcohol) in the person's body involved in the crash is the problem statement. This project can be a potential alternative to confirm the presence of the results of drug test takes time or not possible to conduct. According to the 4th Amendment, the police need a warrant or to develop probable cause that the person is intoxicated, the person involved in the crash can deny taking a blood/breath test. This is the reason why we will find very few records on drugs and alcohol. Based on the historical data, we can develop the instinct and we can eliminate the time delay to confirm the presence of the matter. We will be tuning the Logistic Regression and Random Forest model based on the accuracy metrics.

Developing the Data Pipelines which reads the data from Amazon S3 to Databricks platform. Creating an environment for different personas where these personas will get access to the data as per their requirements.  



# Proposed Data Flow
<img src="https://github.com/nvyas1-git/Data-Engineering-Project/blob/main/images/proposedDataFlow.png" width="100%">

### Work in Progress:
__If the output does not seem proper in notebook, please try checking these databricks notebook links:___

__Notebooks as per the different personas:___
- [Data Scientist Notebook Link](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/864361961989879/3525027352491473/4321021158414790/latest.html)
- [Business Analyst Notebook Link](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/864361961989879/3525027352491471/4321021158414790/latest.html)
- [Data Engineer(Testing) Notebook Link](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/864361961989879/3256384997207093/4321021158414790/latest.html)
