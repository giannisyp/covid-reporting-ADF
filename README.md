# Covid19 Prediction/Reporting with Azure Data Factory

This is a project that uses Azure Data Factory to create ETL pipelines for Covid19 data analysis

Project Architecture

![photo2](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/631d3817-cdff-4771-a90d-61c8eea1a45c)


1. It uses automated pipelines to ingest data from the European Center for Disease Prevention and Control

2. Uses ADF pipelines for Data Transformation to make data viable for reports and understanding
For some of the transformations processes azure data factory's data flow was used which is its own compute and for the rest Databricks notebooks.

![photo3](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/b5dfb18d-4e24-48ab-93bb-320dac4b9aa0)
![photo4](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/e0c7d5be-1f24-4da7-91a8-5984b882f7aa)



4. And finally for pipelines for Loading the appropriate data into databases for later use.

Finally a couple visualizations are made for reporting 

![photo5](https://github.com/giannisyp/covid-reporting-ADF/assets/119696474/b0bd7289-2a20-4157-a817-394502cafb97)

