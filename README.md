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

Loom Videos:
1- https://www.loom.com/share/dd21dfe1e0d845cbbe8f637d7357bc2b?sid=839de8b4-3411-4c28-8d31-01816762f980(explaining the code)
2- https://www.loom.com/share/6d4a402ca3cc48b8bc8bbdb096f4677a?sid=19374e34-4fa1-42bd-bd40-336ed8fe1601(Architecture of X and Y explanation)
3- https://www.loom.com/share/0b70a90dec3d4ff1b0be3ffd6af7a8c3?sid=b26e341a-72cc-4ad9-a85c-d9c8341eb1ff(setup explanation)
4-https://www.loom.com/share/a33f0e80f2e64204950ae9b5b0a8f907?sid=8dffe34c-da93-4436-8897-a19412dc908f(howing a live running demo of the above in action.
)
