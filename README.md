# ETL_using_dataproc
This repo demonstrates how to set up a ELT pipeline to extract data from source (.xlxs file), process it and store it in cloud storage, make the processed data available on HIVE/BQ for further analysis

# Technologies Used:

1. Dataproc
2. Pyspark
3. BigQuery

# Dataproc Commands used

While setting up Dataproc we will also use default Workflow template
Workflow Template :- 
    a. Allows us to define a reusable workflow to process data using a series of Dataproc Jobs
    b. It helps automate the management of clusters and job execution.

For our exercise, we will use short-lived cluster.
    - A short lived cluster will only be active during the execution of jobs and will delete itself once job execution is complete.

