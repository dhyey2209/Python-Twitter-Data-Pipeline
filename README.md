# Twitter Data Pipeline with Airflow, Python, and AWS

This project presents a complete data engineering pipeline that captures, transforms, and stores Twitter data.

## Architecture Overview

The data pipeline is constructed with the following components:

- **Twitter API**: For extracting tweets in real-time.
- **Python**: To apply transformation logic to the data.
- **Apache Airflow**: For orchestrating the ETL tasks on a scheduled basis, hosted on Amazon EC2.
- **Amazon EC2**: Serves as the robust compute service to run our Airflow scheduler and workers.
- **Amazon S3**: As the durable data storage solution for the processed results.

![Project Overview](https://github.com/dhyey2209/Twitter-Data-Pipeline/blob/main/Images/Screenshot%202024-02-13%20122905.png)
