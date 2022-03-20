# Streaming data processing with Azure Databricks

## Event Hubs and Spark Structured Streaming
Azure Event Hubs is a scalable real-time data ingestion service that processes millions of data in a matter of seconds. It can receive large amounts of data from multiple sources and stream the prepared data to Azure Data Lake or Azure Blob storage.

Azure Event Hubs can be integrated with Spark Structured Streaming to perform processing of messages in near real time. We can query and analyze the processed data as it comes by using a Structured Streaming query and Spark SQL.

## Databricks Notebooks
**1.  Structured-Streaming-Concepts**  
  -  Stream data from a file and write it out to a distributed file system
  -  List active streams
  -  Stop active streams
    
**2.  Time-Windows**
  - Use sliding windows to aggregate over chunks of data rather than all data
  - Apply watermarking to throw away stale old data that you do not have space to keep
  - Plot live graphs using display
  
**3.  Streaming-With-Event-Hubs**  
  - Establish a connection with Event Hubs in Spark
  - Subscribe to and configure an Event Hubs stream
  - Parse JSON records from Event Hubs

See more from [Process streaming data with Azure Databricks structured streaming](https://docs.microsoft.com/en-us/learn/modules/process-streaming-data-azure-databricks-structured-streaming/)
