# Kinesis

Amazon Kinesis is a data delivery mechanism. It has four major parts:
1. **Amazon Kinesis Video Streams:**  
Capture, process, and store video streams for analytics and machine learning.

2. **Amazon Kinesis Data Streams:**
Build custom applications that analyze data streams using popular stream-processing frameworks.

3. **Amazon Kinesis Data Firehose:**
Load data streams into AWS data stores.

4. **Amazon Kinesis Data Analytics:**
Process and analyze streaming data using SQL or Java.


For the examination, Kinesis Data Streams and Kinesis Data Firehose are important. 





**Amazon Kinesis Streams**

Captures terabytes data in real time. Data can be analyzed on the fly.  
Real-time dashboards, alerts can be implemented in Kinesis Streams. Streaming procesing can be done in an environment of client's choice like- Kinesis Client Library (KCL), Apache Storm, and Apache Spark Streaming.

**Amazon Kinesis Firehose**

When we need to load streaming data into AWS, we can use **Amazon Kinesis Firehose**. It can capture and load data into S3, Redshift etc. But, analysis will be **near real time** and **NOT real time**. After loading the data into desired destination, usual BI tools and dashboards can be used to analyse data.  Quick implementation of **ELT (Extract -> Load -> Transform)** can be used. 



Read [Kinesis Data Streams](002a-aws-Kinesis-Data-Streams.md) and Kinesis Data Firehose. 