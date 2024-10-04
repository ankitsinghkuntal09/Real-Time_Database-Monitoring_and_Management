
# Real-Time Data Pipeline Using-Kafka

## Project Overview
This project implements a real-time data pipeline using `Apache Kafka`, Python's `psutil` library for metric collection, and `SQL Server` for data storage. The pipeline collects metrics data from the local computer, processes it through Kafka brokers, and loads it into a SQL Server database. Additionally, a real-time dashboard is created using `Power BI`, providing a user-friendly interface for monitoring the collected metrics.

## Technologies Used
- **Python:** Utilized the psutil library for collecting metrics data and Kafka Python client for producing and consuming messages.
- **Apache Kafka:** Implemented a distributed streaming platform to handle real-time data processing and communication between producers and consumers.
- **Apache Zookeeper:** Used for coordinating and managing Kafka brokers.
- **SQL Server:** Stored and managed the collected metrics data in a relational database.
- **Power BI:** Connected to the SQL Server database to visualize real-time metrics and create the dashboard.


# Conclusion
This project demonstrates an effective implementation of a real-time data pipeline using Apache Kafka, Python, SQL Server, and Power BI. It allows seamless collection, processing, and visualization of system metrics, enabling users to gain valuable insights into system performance.

