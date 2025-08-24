# 🏦 Bank Dataset EDA

This project performs **Exploratory Data Analysis (EDA)** on a bank dataset comprising customer demographics, credit profiles, and transaction history.

---

## 📁 Dataset Overview

The data is stored in a compressed zip file: `datasets.zip`, which contains:

- `customers.csv` – Basic customer information (e.g., age, gender, region)
- `credit_profiles.csv` – Credit-related metrics (e.g., credit score, limits)
- `transactions.csv` – Detailed transaction history (e.g., amount, merchant category)

These datasets can be analyzed independently or joined for richer insights.

---

## 🔍 Project Goals

- Understand the structure and relationships within and across the datasets
- Identify data quality issues (e.g., missing values, duplicates, outliers)
- Analyze customer behavior, spending patterns, and credit profiles

---

## 🛠️ Tools Used

- `pandas` – Data loading, cleaning, transformation
- `numpy` – Numerical operations
- `matplotlib` – Visualization
- `seaborn` – Statistical data visualization
- `warnings` – Suppress noisy outputs

---
## 📦 File Structure
    python
    
    .
    ├── datasets.zip
    ├── eda_bank_dataset.ipynb
    ├── README.md
    ├── requirements.txt



## 🚀 Getting Started

1. Clone the repository

    ```bash
    git clone https://github.com/koh-jiahao/bank-dataset-eda.git
    cd bank-dataset-eda


2. Install dependencies

    ```bash
    pip install -r requirements.txt

3. Extract the data

    ```bash
    unzip datasets.zip

4. Run the analysis

    ```bash
    jupyter notebook
