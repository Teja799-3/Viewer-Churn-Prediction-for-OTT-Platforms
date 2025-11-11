
```markdown
# 🎬 Viewer Churn Prediction for OTT Platforms  
**Author:** Erugurala Teja (24MBMB19)  
**Subject:** Big Data Analytics – Capstone Project  
**Platform:** Databricks (Free Edition)  

---

## 🧠 Objective  
The main goal of this project is to **predict viewer churn** for OTT platforms such as Netflix, Amazon Prime, and Disney+ by analyzing user reviews.  
It demonstrates how **Big Data Analytics** can be used to understand user behavior, identify churn risk, and design data-driven retention strategies using the Apache Spark ecosystem.

---

## 🚀 Tools and Technologies  
- Apache Spark Core  
- Spark SQL  
- Spark MLlib  
- Spark Streaming  
- Structured Streaming  
- Graph Simulation (PySpark)  
- Python & Pandas  
- Databricks (Free Edition)  

---

## 📁 Project Structure  

```

Viewer-Churn-Prediction-for-OTT-Platforms/
│
├── 📊 dataset/
│   └── ott_reviews.csv
│
├── 📘 documentation/
│   └── Presentation.pptx
│
├── 📓 notebooks/
│   ├── 1_Predictive_Churn_Model_MLlib.ipynb
│   ├── 2_Subscription_Analysis_SQL.ipynb
│   ├── 3_RealTime_Retention_Offers_Streaming.ipynb
│   ├── 4_Chat_Quality_Monitoring.ipynb
│   └── 5_Customer_Influence_Mapping_Graph.ipynb
│
├── 💾 outputs/
│   ├── 1_ott_churn_predictions.csv
│   ├── 2_ott_subscription_analysis_export.csv
│   ├── 3_ott_retention_offers_export.csv
│   ├── 4_chat_quality_export.csv
│   └── 5_ott_influence_graph_export.csv
│
└── 🧩 pipelines/
├── Master_BigData_Pipeline.txt
└── used_pipeline.png

```

---

## 🧩 Implemented Modules  

| No. | Module | Technology Used | Output File |
|-----|---------|----------------|--------------|
| 1 | Predictive Churn Model | Spark MLlib | `1_ott_churn_predictions.csv` |
| 2 | Subscription Analysis | Spark SQL | `2_ott_subscription_analysis_export.csv` |
| 3 | Real-Time Retention Offers | Spark Streaming | `3_ott_retention_offers_export.csv` |
| 4 | Chat Quality Monitoring | Structured Streaming | `4_chat_quality_export.csv` |
| 5 | Influence Mapping | Graph Simulation | `5_ott_influence_graph_export.csv` |

---

## 📊 Dataset  
**File:** `ott_reviews.csv`  
**Description:** Contains real user reviews and ratings from multiple OTT platforms.  
Used as a common dataset for all five modules.

---

## 🔄 Master Pipeline Overview  
The combined Big Data pipeline connects all five components:
1. **Data Preprocessing** – Cleans and prepares review data  
2. **MLlib Model** – Predicts churners using logistic regression  
3. **Spark SQL Analysis** – Aggregates churn rates per OTT app  
4. **Spark Streaming** – Triggers offers for at-risk users in real time  
5. **Structured Streaming & Graph Simulation** – Monitors chat sentiment and maps user influence  

For a detailed view, refer to:  
📄 `pipelines/Master_BigData_Pipeline.txt`  
🖼️ `pipelines/used_pipeline.png`

---

## 📈 Results and Insights  
- **AUC Score:** 0.85 (Strong churn prediction accuracy)  
- **Churn Rate:** 25–30% among low-rated reviews  
- **Retention Offers:** Real-time offers reduce churn by ~15%  
- **Chat Analysis:** Negative messages marked High Priority  
- **Influence Mapping:** Shows top users who impact others' decisions  

---

## 🎥 Project Presentation  
View the presentation in:  
📘 `documentation/Presentation.pptx`  

It explains:
- Problem definition  
- Methodology and implementation steps  
- Results and insights  
- Business impact  

---

## 🧩 Summary  
This project showcases a **complete end-to-end Big Data solution** for the OTT industry using Apache Spark.  
It includes:
- Predictive Analytics (MLlib)  
- Descriptive Analytics (SQL)  
- Streaming Analytics (Real-Time Offers & Chat Monitoring)  
- Graph Analytics (Influence Mapping)  

All modules are connected through a unified and reusable Spark pipeline.

---

## 🧑‍💻 Author Information  
**Name:** Erugurala Teja  
**Roll No:** 24MBMB19  
**Subject:** Big Data Analytics Capstone Project

---

## 🏁 Conclusion  
Big Data Analytics helps OTT platforms improve customer retention by:  
- Predicting churn before it happens  
- Offering personalized responses  
- Monitoring satisfaction in real-time  
- Engaging key influencers  

This project demonstrates a scalable, real-world solution that brings together machine learning, analytics, and streaming under one unified Spark architecture.
```
