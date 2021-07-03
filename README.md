# Edu_Tech_Analysis_Insights

In this school project, I create insights for product strategy decisions by building a data pipeline with Docker, Kafka, ZooKeeper, Hadoop. Using Spark and SQL for data transformation and exploration.

For the Analysis Report and Insights see the following:

1. Edu_Tech_Insights.ipynb : The report describes my queries and spark SQL to answer business questions that I selected. It describes my assumptions, thinking, what the parts of the pipeline do, what is given, what I set up. It also provides a discussion about the data, any data issues and ways to resolve these issues.


Under the skh folder you will find:

a) docker-compose.yml : Used to spin up the pipeline

b) spark_history.txt and spark_history2.txt : my history files, the former shows 99% of the queries run in the report and history2.txt was primarily used to identify the difference in number of records vs distinct number of user_exam_ids.

c) zilingh8-history.txt and zilingh8-history2.txt :  
- the docker history.txt file shows all actions that were used for the report. 
- history2.txt was used to spin up the container cluster for a specific action mentioned above for the spark file.
