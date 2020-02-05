![AWS Data Services and Machine Learning](https://github.com/lynnlangit/Hello-AWS-Data-Services/blob/master/images/aws-data-services.png)

## AWS Data Services

This is a set of scripts and instructions designed to help you quickly set up and load key AWS data services for demo and learning purposes.  The goal is to get a 'Hello World' implementation set up quickly. These samples use the Navicat client (14-day free trial) for RDS and Redshift.  I recommend using the now-available Jupyter Notebook to quickly connect to EMR.  Samples include the following AWS Data Services:  
  - AWS RDS Aurora and MySQL
    - Creates, load and SQL queries for **Northwind** database tables
  - AWS Redshift and Redshift Spectrum
    - Creates, loads and SQL DW queries for **Customers star schema** source database tables
  - AWS EMR with Spark
    - Creates and run test **CalcPi** PySpark job on cluster
  - AWS Athena
    - Creates, loads and SQL queries for **ElbLogs** (AWS sample) using service
  - AWS DynamoDB
    - Creates, adds and NoSQL query for **Music** JSON data into table
  - AWS Kinesis, including Kinesis Analytics
 
Includes simple scripts as follows:
   - awscli scripts 
   - AWS SDK node.js scripts 
  
## AWS Machine Learning 

Includes information about using machine learning servers and services, including the following:  
  - AWS Machine Learning AMI for EC2
  - AWS SageMaker
  - MxNet on Databricks using AWS
  - AWS EMR with Spark ML

NOTES on the examples:
   - All are set to run in the 'us-east-1' AWS region.
   - All were prepared on an OSX laptop.
   - Machine Learning 'Hello World' example is `mnist` (probablistic image classification -> into 10 classes using images of handwritten digits)

---

I have a large number of cloud and data courses on LinkedIn Learning.  Below is a summary chart of my most popular courses for AWS Data topics.  Just search on the course title (or my name) on the [LinkedIn Learning site](https://www.linkedin.com/learning/search?entityType=COURSE&keywords=lynn%20langit) to view these courses.

![AWS top courses](https://github.com/lynnlangit/Hello-AWS-Data-Services/blob/master/images/top.png)
