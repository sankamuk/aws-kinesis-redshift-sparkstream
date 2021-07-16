# Spark Structured Streaming Data Pipeline from AWS Kinesis to AWS Redshift

## Overview

Spark Structured Streaming data pipeline. Pushes data from Kinesis Stream to a Redshift Cluster. The pipeline keeps data backup in S3 per day basis for easy replaying of data in case required.

> Note currently the teraform automation supports `EC2` based deployment but in case the in future the scale up required `EMR` can be choosen to deploy the pipeline.

## Deliverable details:

- `Pyspark Structured Streaming script` to execute the pipeline.
- `Bootstrap script` to setup an EC2 host to execute the pipeline.
- `Teraform directory` to host teraform scripts to setup and configure EC2 host for pipeline.

## Todo

- Cross account Kinesis connectivity.
- Better monitoring and logging setup.
