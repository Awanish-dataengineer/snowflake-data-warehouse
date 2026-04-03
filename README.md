# ❄️ Snowflake Data Warehouse — Star Schema & Query Optimization

## 📌 Project Overview
Production-grade Snowflake data warehouse design
covering star schema modeling, advanced SQL query
writing, and performance optimization techniques.
Built across healthcare and retail domains processing
large scale datasets with high reliability.

## 🏗️ Architecture

Raw Data (CSV/API/S3)
↓
Snowflake Staging
↓
Dimension Tables
(dim_patient, dim_date,
dim_product, dim_store)
↓
Fact Tables
(fact_readmission,
fact_sales, fact_campaign)
↓
BI Reporting Layer

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Snowflake | Cloud Data Warehouse |
| SQL | Query Writing & Optimization |
| DBT | Data Transformation |
| Python | Data Ingestion Scripts |
| AWS S3 | Raw Data Storage |
| Git | Version Control |

## 📊 Key Features
- ✅ Star schema design — facts & dimensions
- ✅ Snowflake clustering keys for performance
- ✅ Advanced SQL query optimization
- ✅ Micro-partition pruning techniques
- ✅ Multi-cluster warehouse configuration
- ✅ Role-based access control (RBAC)
- ✅ Time Travel for data recovery
- ✅ Processes 500K+ records with 99%+ uptime

## 📁 Project Structure

├── schema/
│   ├── dimensions/       # Dimension table DDLs
│   ├── facts/            # Fact table DDLs
│   └── staging/          # Staging table DDLs
├── sql/
│   ├── queries/          # Optimized SQL queries
│   ├── performance/      # Query tuning scripts
│   └── validation/       # Data quality checks
├── ingestion/
│   └── load_data.py      # Python loading scripts
├── config/
│   └── warehouse.sql     # Warehouse configuration
├── tests/                # Query test scripts
└── README.md

## 🔑 Key Achievements
- Designed star schema processing **500K+ patient**
  records with 99%+ data availability
- Reduced query processing time from **2 hours
  to 30 minutes** using clustering keys
- Supported **100+ business metrics** for retail
  Key Driver Analysis
- Processed **1TB–10TB** of data with optimized
  warehouse configuration
- Received **"Innovative Coder" Award** for
  Snowflake query optimization

## 📬 Contact
**Awanish Kumar** — Senior Data Engineer
- 📧 awshi91@gmail.com
- 🔗 linkedin.com/in/awanish-kumar-4621a1a1
