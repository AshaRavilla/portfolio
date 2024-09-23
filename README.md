# 🛠️ My Data Engineering and Data Science Portfolio

👋 Hi! I'm **Asha**, a passionate **Data Engineer** with experience in building **scalable data pipelines**, real-time data processing, and cloud infrastructure. This portfolio showcases my key projects, highlighting how I've leveraged tools like **AWS**, **Apache Spark**, **Kafka**, and **Snowflake** to solve complex data challenges.

🔗 [**Explore My GitHub Profile**](https://github.com/AshaRavilla) | [**Contact Me on LinkedIn**](https://www.linkedin.com/in/asha-ravilla/)

## 📑 Table of Contents
- [Data Engineering Projects](#data-engineering-projects)
  - [YouTube Trending Data Pipeline](#1-youtube-trending-data-pipeline)
  - [Kafka Stock Market Data Pipeline](#2-kafka-stock-market-data-pipeline)
  - [Snowflake to S3 Data Transfer](#3-snowflake-to-s3-data-transfer-using-aws-glue)
- [Data Science and Machine Learning Projects](#data-science-and-machine-learning-projects)
  - [Black Friday Sales Prediction](#1-black-friday-sales-prediction)
  - [Link Prediction Project](#2-link-prediction-project)

## Projects

## Data Engineering Projects

| Project Name                           | Description                                                             | Technologies Used                                                                                          | Outcome                                                   |
| -------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [YouTube Trending Data Pipeline](#1-youtube-trending-data-pipeline)    | Automated daily data pipeline for YouTube trending data.                 | ![YouTube API](https://img.shields.io/badge/-YouTube_API-FF0000?style=flat) ![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=flat) ![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=flat) ![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=flat) ![Athena](https://img.shields.io/badge/-Athena-232F3E?style=flat) | Automated data processing workflow, reducing manual intervention by 80%. Improved query time by 40%. |
| [Kafka Stock Market Data Pipeline](#2-kafka-stock-market-data-pipeline)  | Real-time stock market data processing using Kafka.                      | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat) ![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat) ![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=flat) ![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=flat) ![Athena](https://img.shields.io/badge/-Athena-232F3E?style=flat) | Enabled real-time data insights. Reduced latency by 20%. |
| [Snowflake to S3 Data Transfer](#3-snowflake-to-s3-data-transfer-using-aws-glue)     | Data pipeline for transferring large datasets from Snowflake to S3.      | ![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat) ![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=flat) ![Apache Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat) ![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=flat) | Improved pipeline efficiency by 30%. Reduced transfer time. |

---

### 1. [**YouTube Trending Data Pipeline**](https://github.com/AshaRavilla/YouTube-Trending-Data-From-API-to-Analytics)

- **Description:** Developed a scalable data pipeline to ingest, process, and analyze daily trending YouTube video data using the **YouTube API** and **AWS** services, automating the entire workflow from ingestion to analysis.

#### 🛠️ Technologies Used:
![YouTube API](https://img.shields.io/badge/-YouTube_API-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Athena](https://img.shields.io/badge/-Athena-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

#### 💡 Key Contributions:
- Designed and implemented an **ETL pipeline** to ingest trending video data from the **YouTube API** to **AWS S3**.
- Automated the data ingestion process using **AWS Lambda** to trigger workflows based on event-driven architecture.
- Cleansed and transformed the raw data using **AWS Glue** for downstream analysis.
- Built and optimized frequent queries (e.g., inner joins of video and category data) using **AWS Athena**, reducing query time by 40%.

#### 📊 Outcome:
- Fully automated the data processing workflow, reducing manual intervention by 80%.
- Improved data accessibility and query performance, enabling more efficient analysis of trending video content.
  
### 2. [**Kafka Stock Market Data Pipeline**](https://github.com/AshaRavilla/stock-market-kafka-data-engineering-project)

- **Description:** Built a real-time data ingestion pipeline for stock market data using **Apache Kafka**, allowing real-time processing and analysis of streaming data.

#### 🛠️ Technologies Used:
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/-Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

#### 💡 Key Contributions:
- Developed a **real-time data pipeline** for ingesting stock data using **Apache Kafka**.
- Implemented **AWS Glue ETL** for data transformation and processing.
- Used **AWS Athena** for querying the processed data and generating real-time insights.
- Reduced data processing latency by 20% through optimized pipeline design.

#### 📊 Outcome:
- Enabled stock analysts to access and analyze real-time data streams, significantly improving decision-making speed.

### 3. [**Snowflake to S3 Data Transfer using AWS Glue**](https://github.com/AshaRavilla/snowflake-to-s3-data-transfer)

- **Description:** Built a data pipeline to transfer large datasets from **Snowflake** to **Amazon S3** using **AWS Glue** and **Spark**, automating the data extraction, transformation, and loading process.

#### 🛠️ Technologies Used:
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS S3](https://img.shields.io/badge/-AWS_S3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Glue](https://img.shields.io/badge/-AWS_Glue-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Apache Spark](https://img.shields.io/badge/-Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

#### 💡 Key Contributions:
- Developed a **secure and scalable pipeline** to extract data from **Snowflake** and load it into **Amazon S3**.
- Utilized **Apache Spark** within **AWS Glue** for efficient data transformation and processing.
- Automated the data extraction and transfer process using AWS Glue jobs, reducing manual intervention by 80%.
- Ensured data consistency and optimized storage formats for better querying and retrieval.

#### 📊 Outcome:
- Reduced data transfer time by 30% and improved overall pipeline efficiency.
- Streamlined the data flow between **Snowflake** and **S3**, enabling faster downstream analytics.


## Data Science and Machine Learning Projects

| Project Name                           | Description                                                             | Technologies Used                                                                                          | Outcome                                                   |
| -------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [Black Friday Sales Prediction](#1-black-friday-sales-prediction)     | Predicted purchase amounts during Black Friday sales using regression models. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat) ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat) ![XGBoost](https://img.shields.io/badge/-XGBoost-FF6600?style=flat) | Improved model accuracy by 15%. Provided actionable customer insights. |
| [Link Prediction Project](#2-link-prediction-project)           | Research project predicting links between nodes in a network.            | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat) ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat) ![Classification Models](https://img.shields.io/badge/-Classification_Models-1F77B4?style=flat) | Improved model precision by 12%. Published research paper. |

---


### 1. [**Black Friday Sales Prediction**](https://github.com/AshaRavilla/black-friday-sales-prediction)

- **Description:** Developed a regression model to predict purchase amounts during Black Friday sales based on customer demographics and product details, providing insights into purchasing behavior.

#### 🛠️ Technologies Used:
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)

#### 💡 Key Contributions:
- Conducted **exploratory data analysis** (EDA) on customer demographics and purchasing behavior.
- Built and fine-tuned a **regression model** using **Scikit-learn** and **XGBoost** for purchase amount prediction.
- Applied advanced feature engineering techniques, leading to a 15% improvement in model accuracy.

#### 📊 Outcome:
- Provided actionable insights into customer purchasing behavior, helping retailers optimize marketing strategies.
- Improved model accuracy by 15% through advanced feature selection and tuning.
- Reduced data preprocessing time by automating missing value handling and feature scaling.


### 2. [**Link Prediction Project**](https://github.com/AshaRavilla/link_prediction_project)

- **Description:** A research project focused on predicting links between nodes in a network as continuous, missed, new, or no-links, aiming to uncover patterns in organizational relationships.

#### 🛠️ Technologies Used:
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Classification Models](https://img.shields.io/badge/-Classification_Models-1F77B4?style=for-the-badge)

#### 💡 Key Contributions:
- Performed **data cleaning** and **feature engineering** to prepare the dataset for model training.
- Experimented with multiple **classification models** to predict organizational links.
- Co-authored a research paper detailing the findings, focusing on predictive accuracy and model performance.

#### 📊 Outcome:
- Improved model precision for link prediction by 12% after applying advanced feature selection techniques.
- Published research paper presenting insights on network organization and link prediction accuracy.

---

## GitHub Activity

![Asha's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=AshaRavilla&theme=github-light&hide_border=true)

---

## Let's Connect!
If you're interested in discussing my projects or have an exciting opportunity in **Data Engineering**, I'd love to connect.  

📧 **Email**: [ashalatha579@gmail.com](mailto:ashalatha579@gmail.com)  
💼 **LinkedIn**: [Asha Ravilla](https://www.linkedin.com/in/asha-ravilla/)

