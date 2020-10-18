# Kinesis Data Streams

From whereever you read, the information will always be a subset of official documentation. Read official documentation of [Kinesis Data Streams.](https://docs.aws.amazon.com/kinesis/?id=docs_gateway)

**Streaming Data**

Streaming Data is used when multiple sources (counts in thousands) simulatneously send continious data, in small amounts(Kbs). Sources may vary from mobile devices, sensors, e-commerce platforms, servers etc. 

When these data needs to be processed sequentially and incremently, we can use data streaming. Using streaming data analysis, one can look into the current situations of any kind of continiously changing processes. 

It is easy to confuse between **batch data** and **streaming**. Primary differences are:

|               | Batch                 |  Stream
|---------------|---------------------|------------------------|
| Scope | All data altogether|Rolling time, Most recent data.
|Size|Large|Small/Micro pieces
|Performance|Minutes or in hours| Millisecond latency
|Analyses| Complex| Simple

**Examples of Streaming Software:** 
    - Kinesis in AWS
    - Apache Kafka
    - Apache Flume
    - Apache Spark Streaming
    - Apache Storm (On EC2 and EMR)

