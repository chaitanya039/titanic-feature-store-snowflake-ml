# 🚢 Titanic ML Feature Store Pipeline – Vistora AI-ML Assignment

This project demonstrates end-to-end **feature engineering**, **Snowflake feature store integration**, and **ML model training** using the Titanic dataset.

---

## 📁 Project Structure

| Folder / File               | Description |
|----------------------------|-------------|
| `data/Titanic-Dataset.csv` | Raw Titanic dataset used for processing |
| `notebooks/`               | Jupyter Notebook with detailed implementation |
| `scripts/snowflake_create_table.sql` | SQL script to create feature store table in Snowflake |
| `scripts/snowflake_insert_features.py` | Python script to extract, transform, and insert features |
| `scripts/model_training.py` | Loads features and trains Random Forest model |
| `presentation/VISTOra_AIML.pdf` | Slide deck for the assignment presentation |
| `README.md`                | Project documentation |

---

## ⚙️ Setup Instructions

### Prerequisites

- Python 3.8+
- Snowflake account (trial is fine)
- Packages:
  - `pandas`, `numpy`, `sklearn`, `snowflake-connector-python`