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

## 📁 Project Structure

mechanism_X.py`: Uploads 10K-record chunks from transactions.csv to S3 every second.
- `mechanism_Y.py`: Consumes chunks from S3, runs PatId1/2/3 pattern logic in PySpark.
- `CustomerImportance.csv`: Importance weights used in PatId1.
- `config.py`: AWS + DB creds.
- `README.md`: This file.

---

### 📁 Output Files
- Location: `s3a://pyspark-assignment-sonu/output/`
- Zipped Final: [📦 Download ZIP](https://pyspark-assignment-sonu.s3.ap-south-1.amazonaws.com/final_submission/final_outputs.zip)

---
