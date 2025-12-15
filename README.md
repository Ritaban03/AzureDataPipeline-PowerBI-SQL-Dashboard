Azure End-to-End Data Engineering & Analytics Pipeline (Azure + Power BI)

This project demonstrates an end-to-end Azure-based Data Engineering and Analytics pipeline, designed to simulate a real-world advisory and enterprise analytics use case.

The solution covers data ingestion, storage, transformation, modeling, and visualization, leveraging Microsoft Azure services and Power BI to deliver actionable business insights.

Note: This repository is forked from an open-source project and has been customized, extended, and documented by Ritaban Banerjee for learning and portfolio demonstration purposes.

🔍 Business Use Case (Advisory Context)

The objective of this project is to design a scalable analytics solution for an e-commerce business, enabling stakeholders to track orders, revenue, customer behavior, seller performance, and delivery efficiency.

The architecture and KPIs are aligned with how consulting and advisory teams deliver data-driven insights to business clients.

🏗️ Solution Architecture

Data Flow:

Raw transactional data ingested from CSV files

Stored in Azure Blob Storage

Structured tables created in Azure SQL Database

Data modeled using star schema

KPIs and insights delivered through Power BI dashboards

🔗 Project Overview

Data Source: 9 CSV files (Olist E-Commerce Dataset)

Storage Layer: Azure Blob Storage

Database Layer: Azure SQL Database

Transformation Layer: Power BI Power Query & SQL

Data Modeling: Star Schema with Calendar Table

Analytics & Visualization: Power BI (DAX, Reports, Dashboards)

📁 Folder Structure
AzureDataPipeline-PowerBI-SQL-Dashboard/
│
├── Data/                 # Raw CSV files
├── Images/               # Power BI dashboard screenshots
├── Power BI/
│   ├── Measures/         # DAX measures
│   └── Report/           # Final Power BI (.pbix)
├── SQL/                  # Azure SQL table creation scripts
└── README.md

📊 Key KPIs & Metrics
Orders & Fulfillment

Total Orders

Delivered vs Cancelled Orders

On-Time Delivery %

YTD / MTD Orders

Revenue

Total Revenue

Average Revenue per Order

Revenue Trends (MTD / YTD)

Installment Analysis

Customers

Unique Customers

Returning Customers

Revenue per Customer

Products & Sellers

Revenue per Seller

Orders per Seller

Product Category Performance

Reviews & Satisfaction

Average Review Score

5-Star Review %

Response Time Metrics

🧠 Key DAX Measures

All DAX logic is documented under:

/Power BI/Measures


Measures include:

Time Intelligence (MTD, YTD)

Revenue Aggregations

Customer Segmentation

Delivery Performance Metrics

📈 Visual Insights

High-resolution dashboard screenshots are available under /Images, including:

Executive Dashboard – Revenue, Orders, Category Performance, Geo Insights

Order Fulfillment Dashboard – Delivery timelines, order status, fulfillment efficiency

These dashboards are designed to mirror executive-level reporting used in consulting engagements.

🚀 Technologies Used

Microsoft Azure

Azure Blob Storage

Azure SQL Database

Power BI

Power Query

DAX

Data Modeling

SQL

Git & GitHub

🔧 Customizations & Enhancements

The following customizations have been made / are planned as part of this fork:

Enhanced documentation for advisory-style explanation

KPI alignment with business stakeholder reporting

Dataset and transformation logic updates (in progress)

Future integration with Azure Data Factory for automated ingestion

👨‍💻 Maintainer

Ritaban Banerjee
Aspiring Azure Data Engineer | Data & Analytics | Advisory

🔗 GitHub: https://github.com/Ritaban03

🙏 Original Credit

Original project created by Ajay Danam
(Data Analyst | BI Developer)

This fork is used strictly for educational and portfolio purposes, with full credit retained.

