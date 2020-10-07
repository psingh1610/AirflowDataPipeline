# AirflowDataPipeline

This project automates and monitors ETL data pipelines for music app Sparkify to extract song and user log data and load into analytics table songplays for further analysis in Redshift

The structure of the project is as follows:

Dags: Contains all the tasks and task dependencies to schedule ETL process
Operators: Operators contain the ETL process
Helpers: This contains SQL queries for inserting loading data in analytics table.
