# P.Vaishnavi-24MBMA29_GE372
##  **E-Commerce Data Pipeline and Customer Analytics**

**Capstone Project | MBA (Business Analytics) | University of Hyderabad**

---

###  **Overview**

This project presents a complete **end-to-end data analytics pipeline** for the **E-Commerce industry**, developed on the **Databricks platform** using the **Bronze–Silver–Gold architecture**.

The system processes raw transaction data, refines it through multiple transformation layers, and generates advanced analytical insights across five key business use cases.

This capstone demonstrates how scalable data engineering and analytics workflows can transform retail data into actionable intelligence for better business decisions.

---

###  **Objectives**

* To design and implement a structured **data pipeline** using Databricks.
* To analyze customer purchase behavior and predict future trends.
* To segment customers based on purchasing patterns and spending levels.
* To identify potential churners and recommend high-value products.
* To calculate **Customer Lifetime Value (CLTV)** for strategic decision-making.

---

###  **Project Architecture**

The project follows the **Medallion Architecture (Bronze–Silver–Gold)**, ensuring data quality, consistency, and reusability at every stage.

| Layer                | Description                                                                                                           | Output                                 |
| :------------------- | :-------------------------------------------------------------------------------------------------------------------- | :------------------------------------- |
|  **Bronze Layer**  | Ingests raw data from CSV files into Databricks for initial storage.                                                  | Raw Delta Tables                       |
|  **Silver Layer**   | Cleans, validates, and transforms the ingested data by removing duplicates, handling nulls, and standardizing schema. | Enriched Clean Tables                  |
|  **Gold Layer**    | Creates analytical feature tables and generates insights for business use cases.                                      | Final ML-Ready Tables & Visualizations |
|  **Master Runner** | Automates execution of the three layers sequentially.                                                                 | Streamlined Workflow                   |

---

###  **Project Structure**

```
 E-Commerce-Analytics-Capstone
├── pipeline/
│   ├── bronze_pipeline.ipynb
│   ├── silver_pipeline.ipynb
│   ├── gold_pipeline.ipynb
│   └── master_runner.ipynb
├── data/
│   └── ecommerce_capstone_dataset_1000.csv
├── reports/
│   └── Ecommerce_Capstone_Project_Report.docx
└── README.md
```

---

###  **Use Cases Implemented**

#### 1️ **Purchase Prediction**

Predicts how frequently customers make purchases and estimates total spending based on their transaction history.

#### 2️ **Customer Segmentation**

Segments customers into High-Value, Medium-Value, and Low-Value clusters using RFM (Recency, Frequency, Monetary) analysis.

#### 3️ **Product Recommendation**

Identifies products frequently purchased together, forming the foundation for a collaborative recommendation system.

#### 4️ **Customer Lifetime Value (CLTV) Prediction**

Estimates the total revenue a customer is likely to generate over their lifetime using purchase behavior metrics.

#### 5️ **Churn Prediction**

Identifies customers at risk of leaving the platform by analyzing engagement frequency and transaction recency.

---

###  **Visualizations and Insights**

The analytical dashboards were created using **Databricks Visualization Editor** to represent meaningful business insights:

*  **Bar Charts:** Top-spending customers and category-wise sales trends.
*  **Pie Charts:** Distribution of churned vs active customers.
*  **Horizontal Charts:** Customer segment breakdowns.
*  **Scatter Plots:** Relationship between CLTV and average order value.
*  **Line Charts:** Purchase trends over time.

Together, these visuals provide a holistic understanding of customer behavior and purchasing patterns.

---

###  **Technologies and Tools**

| Category        | Tools / Platforms               |
| :-------------- | :------------------------------ |
| Cloud Platform  | Databricks Community Edition    |
| Data Processing | Apache Spark (PySpark)          |
| Storage         | Databricks File System (DBFS)   |
| ML / Analytics  | Spark MLlib                     |
| Visualization   | Databricks Visualization Editor |
| Documentation   | MS Word, GitHub                 |

---

###  **Key Outcomes**

* Successfully built a modular **Bronze–Silver–Gold pipeline** for scalable analytics.
* Generated structured datasets supporting five strategic business insights.
* Improved interpretability through **interactive Databricks visualizations**.
* Automated pipeline orchestration using a **Master Runner notebook**.
* Produced a formal project report detailing methodology, analysis, and findings.

---

### 🏁 **Conclusion**

This project demonstrates how **Big Data Analytics and PySpark** can empower businesses to transform large volumes of raw e-commerce data into actionable insights.
The integration of Databricks’ collaborative environment and Medallion architecture ensures **data reliability, modularity, and real-world applicability**.

It stands as a complete academic and practical showcase of combining **data engineering, analytics, and visualization** to support data-driven decision-making in the retail sector.

---

### **Future Enhancements**

* Real-time data ingestion using **Apache Kafka**.
* Deep learning models for **churn and recommendation**.
* Integration with Power BI or Tableau for advanced dashboards.
* Expansion of dataset and inclusion of **multi-channel e-commerce analytics**.

---

###  **Author**

**P. Vaishnavi**
MBA (general) – School of Management Studies
**University of Hyderabad**
📧 *[vaishnavipatkula@gmail.com](mailto:vaishnavipatkula@gmail.com)*

---

###  **Under the Guidance of**

**sree lakshmi**
School of Management Studies, University of Hyderabad
