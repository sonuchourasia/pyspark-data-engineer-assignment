# PySpark Data Engineer – Assignment

**👤 Developer:** Sonu Chourasia  
**📝 Role:** PySpark Data Engineer – Offline Assignment Submission  
**📧 Submission Email:** hiring@devdolphins.com  

---

## 🧩 Problem Statement

Detect patterns from transaction data in real time using a two-mechanism architecture:

- **Mechanism X:** Uploads transaction data in chunks (10,000 rows per second) to S3.
- **Mechanism Y:** Consumes these chunks, detects specified patterns, and writes results back to S3.
- **PostgreSQL** is used to track upload state.

---

## 🔧 Technologies Used
- PySpark on Databricks
- AWS S3
- PostgreSQL (state tracker)
- GitHub

## 📂 Project Structure
- `Assignment_Dev_dolph.py` – contains full Mechanism X + Y logic
- `.gitignore` – hides `.env`, data files, etc.
- `README.md` – project setup & usage

## 🛠️ Setup Instructions
1. Set AWS credentials as environment variables:
AWS_ACCESS_KEY_ID=AKIARSF3WSEJI2XYV6PB
AWS_SECRET_ACCESS_KEY=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
AWS_REGION=ap-south-1
