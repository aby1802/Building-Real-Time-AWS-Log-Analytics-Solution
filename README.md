# Building-Real-Time-AWS-Log-Analytics-Solution
Business Problem

The common big data use case that we are going to take is “Log Analytics” where there is a requirement for analysing the log data which comes from various sources such as websites, mobile devices, sensors and applications. The tracking of application availability, fraud detection, and SLA monitoring can be achieved using log analytics. Automated trigger can be setup. The logs from different sources can be transformed to common format for easy query execution.

![Screenshot 2022-12-30 133217](https://user-images.githubusercontent.com/106943371/210048153-22b1f0d7-9a5b-44ff-9353-ae8914605464.jpg)

Solution by using AWS Native Services:

As now a days various applications are running over the cloud so the logs from these applications can be parsed and stored in S3. End to end log analytics solution that collects, ingests, processes and loads both the batch data and streaming data. Processed data will be available to users in near real time. The solution is highly reliable, cost effective, scales automatically to varying data volumes and require almost no IT administration.

Services that we are going to use:

Amazon S3 – This is easy to use service with a simple web services interface to store and retrieve any amount of data from anywhere on the web. It is a safe place to store the files. The data is spread across multiple devices and facilities, this is object based service and the file size can be from 0 bytes to 5 TB for uploading. There is unlimited storage and the files are stored in buckets.

AWS IAM – This is nothing but identity and access management which enables us to manage access to AWS services and resources securely. We can create and manage AWS users and groups, use permissions to allow and deny their access to AWS resources. It is a feature of AWS with no additional charge.

AWS EC2 – It is a service which provides resizable compute capacity in cloud and designed to make web-scale cloud computing easier. We can launch instances with a variety of operating systems.

AWS kinesis firehose – In this the delivery stream is the underlying entity of firehose. Use the firehose by creating a delivery stream to a specified destination and send the data to it. The record is the data of interest which is our data producer sends to a delivery stream which can be large as 1000KB. The data producers send records to a delivery stream.

AWS Glue – It is a fully managed ETL service in which we can categorise our data, clean it, enrich it and move it reliably between various data stores. It is simple and cost effective.

AWS Athena – It is an interactive query service for S3 in which there is no need to load data it stays in S3. It is server less and supports many data formats e.g CSV, JSON, ORC, Parquet, AVRO.

AWS Cloud Watch – It monitors our AWS resources and applications that we run on AWS in real time.
