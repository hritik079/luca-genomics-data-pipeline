# 🧬 LUCA-Genomics Data Engineering & Predictive Analytics Suite

An enterprise-grade, end-to-end bioinformatics data pipeline and predictive analytics platform designed to analyze and model genomic data regarding the Last Universal Common Ancestor (LUCA).

## 🚀 Project Overview
This repository houses a production-grade data pipeline that transforms raw multi-study literature into structured, actionable insights. By integrating **Data Engineering**, **Relational Warehousing**, **Statistical Modeling**, and **Machine Learning**, the suite provides robust exploratory and predictive analytics on prokaryotic genomes and protein consensus scores.

---

## 🛠️ Key Features & Architecture

* **Automated ELT Pipeline:** Ingests, cleans, and standardizes multi-source raw datasets using Python and Pandas.
* **Relational Star Schema Warehouse:** Structured via SQLite, featuring normalized dimensions and fact tables (`dim_proteins`, `fact_consensus`, `dim_pathways`, `fact_genomes`) ensuring zero redundancy.
* **Predictive Machine Learning:** Implements a **Random Forest Classifier** to predict universal core proteins with automated feature importance evaluation.
* **Interactive Visualization:** Multi-panel dashboard suite utilizing Plotly for dynamic, publication-ready data representation.
* **Enterprise Practices:** Built-in logging frameworks and automated database health and integrity audits.

---

## 📁 Repository Structure

```text
├── mysql_powerbi_tables/         # Processed CSV fact and dimension tables
├── luca_analytics.db             # SQLite Relational Data Warehouse
├── luca_executive_dashboard.html # Interactive Plotly visualization suite
├── app.py / notebook             # Core ingestion, modeling, and audit scripts
└── README.md                     # Project documentation
