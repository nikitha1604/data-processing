# 🧠 Data Processing Techniques – Final Assessment

This project demonstrates a complete end-to-end data processing workflow, combining **batch**, **real-time**, **incremental**, and **in-memory** data analytics using modern big data tools.

---

## 📁 Folder Structure

- Data_Preprocessing: Spark preprocessing code & sample dataset
- RealTime_Data_Streaming: Kafka producer & consumer for streaming data
- Incremental_Data_Processing: CDC incremental processing with Kafka
- InMemory_Data_Processing: Spark in-memory analytics


---

## ⚙️ Tools & Technologies Used

| Tool / Library | Purpose |
|----------------|----------|
| **Apache Spark** | Distributed data preprocessing & in-memory computation |
| **Apache Kafka** | Real-time data streaming & change data capture (CDC) |
| **Python** | Core programming language |
| **pyspark** | Spark integration for data transformation |
| **kafka-python** | Kafka producer/consumer implementation |
| **scikit-learn** | ML-based preprocessing & feature scaling |



## 🚀 Key Functionalities

### 🔹 Data Preprocessing
- Cleans, normalizes, and transforms raw datasets using **Spark DataFrames**.  
- Handles missing values, data type conversions, and feature encoding.

### 🔹 Real-Time Data Streaming
- Uses **Kafka Producer** to simulate live data feeds.  
- **Kafka Consumer** processes messages in real time for monitoring and transformation.

### 🔹 Incremental Data Processing (CDC)
- Implements **Change Data Capture** to process only updated or new records.  
- Uses Kafka topics to track and stream incremental updates efficiently.

### 🔹 In-Memory Data Processing
- Performs high-speed analytics using **Spark’s caching and in-memory RDDs**.  
- Benchmarks performance gains with caching and persistence strategies.

---

## 🧩 Project Highlights

- ✅ Modular architecture supporting both **batch** and **streaming** pipelines  
- ⚡ Optimized Spark transformations for **performance efficiency**  
- 🔄 Real-time data handling with **Kafka** integration  
- 💾 In-memory computation for **fast analytics**  
- 🧱 Ready for **enterprise-scale data engineering** environments  

---

## 🧰 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Data_Processing_Techniques.git
   cd Data_Processing_Techniques
Install required dependencies

pip install pyspark kafka-python scikit-learn
Start Kafka & Zookeeper servers
(Ensure Apache Kafka is installed and running locally)


zookeeper-server-start.sh config/zookeeper.properties
kafka-server-start.sh config/server.properties
Run modules as needed

# Example: Run Spark preprocessing
python Data_Preprocessing/spark_preprocessing.py

# Example: Start real-time streaming
python RealTime_Data_Streaming/kafka_producer.py
python RealTime_Data_Streaming/kafka_consumer.py
📊 Example Use Cases
Real-time analytics dashboards

ETL pipelines for data warehousing

Streaming data monitoring and anomaly detection

Incremental machine learning model updates

👩‍💻 Author
Nikitha J
Data Engineering | Big Data | Machine Learning Enthusiast
