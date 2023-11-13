# Covid19 Prediction/Reporting with Azure Data Factory

This is a project that uses Azure Data Factory to create ETL pipelines for Covid19 data analysis

Project Architecture

![photo2](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/30777348-fedd-4aa6-b20b-9d5b8fe390aa)


1. It uses automated pipelines to ingest data from the European Center for Disease Prevention and Control

2. Uses ADF pipelines for Data Transformation to make data viable for reports and understanding
For some of the transformations processes azure data factory's data flow was used which is its own compute and for the rest Databricks notebooks.

4. And finally for pipelines for Loading the appropriate data into databases for later use.

Finally a couple visualizations are made for reporting 

![image](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/84ee118c-6139-44a8-b847-27e181c680d9)
