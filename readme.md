# Real Estate Data Streaming & Analytics Pipeline

## Project Overview

This project demonstrates an end-to-end **Real Estate Data Streaming & Analytics Pipeline** built with a variety of technologies, including **Python**, **Bright Data**, **Apache Kafka**, **Cassandra**, and **Power BI**. The pipeline is designed to extract real-time property data, process it efficiently, store large datasets, and visualize key insights for market analysis.

### Key Technologies:
- **Python**
- **Bright Data (Web Scraping)**
- **Apache Kafka**
- **Apache Spark**
- **Cassandra**
- **Power BI**

---

## Architecture

![Screenshot 2024-08-29 183426](https://github.com/user-attachments/assets/dc7bdcc8-a4fb-4b73-aa7a-fc85e1c36199)


### Components:
1. **Bright Data (WebSocket Data Extraction)**:
   - Real-time property data is extracted using Bright Data’s WebSocket API.
   
2. **Apache Kafka (Data Streaming)**:
   - The data is streamed in real-time to **Apache Kafka** using a master-worker architecture built with **Docker**.
   
3. **Apache Spark (Data Processing)**:
   - **Apache Spark** processes the streamed data to ensure it's efficiently handled and transformed for storage.
   
4. **Cassandra (Data Storage)**:
   - The processed data is stored in **Cassandra**, a distributed NoSQL database optimized for large-scale real-time data.

5. **Power BI (Visualization)**:
   - **Power BI** is used to create visual dashboards, helping analyze property trends and extract valuable insights from the data.

---

## Features

- **Real-time Data Extraction**: Uses **WebSocket** to continuously gather live property data.
- **Scalable Data Streaming**: Built with **Apache Kafka** for scalable and fault-tolerant data streaming.
- **Big Data Processing**: Real-time data processing using **Apache Spark** to handle large volumes of property data.
- **Efficient Storage**: **Cassandra** is used to store data for fast access and scalability.
- **Market Insights**: Visualize property trends and insights with **Power BI** for decision-making.

---

## Setup Instructions

### Prerequisites

- **Docker**: For containerizing the application components.
- **Kafka**: For streaming real-time data.
- **Cassandra**: For data storage.
- **Power BI**: For data visualization.
- **Python 3.x**: To run the data extraction and processing scripts.
