
# Viewer Churn Prediction for OTT Platforms

Author: Erugurala Teja
Roll Number: 24MBMB19
Subject: Big Data Analytics Capstone Project
Institution: [University of Hyderabad]

---

## Project Objective

This project analyzes user behavior on OTT platforms and predicts viewer churn using the Apache Spark ecosystem. The goal is to identify customers likely to unsubscribe and help platforms take timely action through data-driven insights.

All modules are implemented on Databricks Free Edition using Apache Spark Core, SQL, MLlib, Streaming, Structured Streaming, and Graph Simulation.

---

## Project Structure

### dataset
ott_reviews.csv

### documentation
Presentation.pptx

### notebooks
1_Predictive_Churn_Model_MLlib.ipynb
2_Subscription_Analysis_SQL.ipynb
3_RealTime_Retention_Offers_Streaming.ipynb
4_Chat_Quality_Monitoring.ipynb
5_Customer_Influence_Mapping_Graph.ipynb

### outputs
1_ott_churn_predictions.csv
2_ott_subscription_analysis_export.csv
3_ott_retention_offers_export.csv
4_chat_quality_export.csv
5_ott_influence_graph_export.csv

### pipelines
Master_BigData_Pipeline.txt
used_pipeline.png

---

## Technologies Used

Apache Spark Core for distributed data processing
Spark SQL for analytics and aggregations
Spark MLlib for machine learning model development
Spark Streaming for real-time offer triggering
Structured Streaming for chat sentiment monitoring
Graph Simulation for user influence mapping
Databricks Free Edition for cloud execution
Python and Pandas for preprocessing and data handling

---

## Description of Components

Dataset
The ott_reviews.csv file contains real OTT app reviews with columns such as user name, review text, app name, and rating score. The same dataset is used for all notebooks to maintain consistency.

Documentation
The Presentation.pptx file explains the project objectives, methodology, implementation, and insights. It is used during the final viva and demonstration.

### Notebooks
1_Predictive_Churn_Model_MLlib.ipynb – Builds a logistic regression model to predict user churn.
2_Subscription_Analysis_SQL.ipynb – Analyzes subscription trends and churn rate using Spark SQL.
3_RealTime_Retention_Offers_Streaming.ipynb – Triggers retention offers for at-risk users through Spark Streaming.
4_Chat_Quality_Monitoring.ipynb – Performs sentiment detection in live chats using Structured Streaming.
5_Customer_Influence_Mapping_Graph.ipynb – Simulates graph analytics to identify influential users and clusters.

Outputs
Each module produces a CSV output file showing analytical results or model predictions. These are saved inside the outputs folder.

Pipelines
The Master_BigData_Pipeline.txt file explains the end-to-end workflow.
The used_pipeline.png image visually represents the unified data flow connecting all modules.

---

## Steps to Run

1. Upload all files into your Databricks workspace.
2. Ensure the ott_reviews.csv dataset is accessible at /Volumes/workspace/default/dataset/ott_reviews.csv.
3. Open the notebooks one by one in the given order.
4. Execute each notebook to generate outputs inside the outputs folder.
5. Review results and insights in the generated CSV files.

---

## Summary of Workflows

The pipeline starts with data ingestion and cleaning.
Then text data is processed and transformed into features for machine learning.
A predictive churn model identifies users who are likely to leave the platform.
Spark SQL modules analyze subscription patterns and calculate churn rates.
Real-time streaming logic automatically triggers retention offers for low-rated users.
Structured streaming monitors chat messages for sentiment and service priority.
Finally, graph simulation maps customer influence and community relationships.

All components work together as a single Big Data pipeline, showcasing both batch and real-time analytics for OTT platforms.

---

## Insights and Results

The average churn rate observed is between twenty-five to thirty percent.
Low user ratings and negative reviews strongly indicate potential churn.
Personalized offers can significantly reduce churn percentages.
Sentiment analysis helps prioritize customer support and improve service quality.
Influence mapping identifies top users who shape public opinions about OTT content.

---

## Conclusion

This project demonstrates how Big Data Analytics helps OTT platforms retain users and improve satisfaction. By integrating machine learning, SQL analytics, real-time streaming, and graph-based influence mapping in a single environment, it delivers actionable insights from large-scale viewer data.

