# Enterprise Batch Pipeline with PySpark

## 📖 Project Overview
This project implements an Enterprise-Scale Batch Data Processing Pipeline using PySpark.  
The pipeline processes raw transactional data into structured, partitioned, and curated datasets ready for analytical use.

The system follows a layered data architecture approach:
- Raw Layer
- Clean Layer
- Curated Layer

---

## 🎯 Objectives
- Process large-scale transactional datasets efficiently.
- Perform data cleaning and transformation using PySpark.
- Implement partitioning strategies for performance optimization.
- Generate business-ready aggregated insights.

---

## 🏗️ Project Structure
bigdata-project/
│
├── scripts/ # PySpark ETL scripts
├── data/ # Raw data (ignored in Git)
├── logs/ # Log files (ignored in Git)
├── .gitignore # Git ignore configuration
└── README.md # Project documentation


---

## ⚙️ Technologies Used

- Python 3.x
- PySpark
- Apache Spark
- Parquet Format
- Linux / Ubuntu Environment

---

## 🔄 Pipeline Architecture

### 1️⃣ Raw Layer
- Original dataset ingestion.
- Stored in structured format.

### 2️⃣ Clean Layer
- Data cleansing
- Handling null values
- Standardizing schema
- Stored in partitioned Parquet format

### 3️⃣ Curated Layer
- Aggregated datasets:
  - Average transaction value
  - Revenue by category
  - Top selling products

---

## 📊 Output Examples

The pipeline generates:
- Partitioned datasets by product category
- Revenue summary tables
- Aggregated business metrics

---

## 🚀 How to Run

Activate virtual environment:

```bash
source venv/bin/activate

Run Spark job: python scripts/your_script_name.py

🧹 Git Best Practices Applied

Large files excluded using .gitignore
Parquet outputs excluded
Virtual environment excluded
Clean repository structure maintained

👩‍💻 Author

Mahdalina
Enterprise Big Data Engineering Project
2026


---

# 🔥 Cara Pakai

1. Buat file:
   ```bash
   nano README.md
2. Paste isi di atas

3. Save → CTRL+O → Enter → CTRL+X

4. Commit & push:
git add README.md
git commit -m "Add professional README"
git push
