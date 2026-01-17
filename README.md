# Auto Dataset Cleaning & Preprocessing (Python)

This project focuses on **cleaning, preprocessing, and preparing a large automobile dataset** using **Python**.  
The goal is to transform raw, inconsistent, and noisy vehicle data into a **clean, structured dataset** suitable for analysis and machine learning.

---

## 📌 Project Overview

Real-world datasets are often messy and unreliable.  
This project demonstrates a **systematic data cleaning workflow** applied to an automobile listings dataset containing over **370,000 records**.

The project covers:
- Data inspection and structure analysis
- Handling missing and inconsistent values
- Correcting data types
- Cleaning categorical and numerical variables
- Preparing the dataset for downstream analytics

---

## 📊 Dataset Description

The dataset contains **371,561 vehicle listings** with **20 attributes**, including:

### Key Columns
- `dateCrawled` – Date listing was crawled
- `name` – Vehicle description
- `seller` – Seller type
- `offerType` – Offer classification
- `price` – Vehicle price
- `vehicleType` – Car type (SUV, limousine, etc.)
- `yearOfRegistration`
- `gearbox`
- `powerPS`
- `model`
- `kilometer`
- `fuelType`
- `brand`
- `notRepairedDamage`
- `postalCode`
- `lastSeen`

The dataset initially contains **mixed data types, missing values, and inconsistencies**, making it ideal for data cleaning practice.

---

## 🧹 Data Cleaning Steps

### 🔍 Data Inspection
- Used `.info()`, `.shape()`, and `.dtypes()` to understand structure
- Identified missing values and incorrect data types
- Detected mixed-type columns and memory issues

### 🧾 Handling Missing Values
- Analyzed missing values column-wise
- Retained critical records while handling non-essential nulls
- Cleaned categorical columns with missing entries

### 🔄 Data Type Corrections
- Converted numerical columns stored as objects
- Ensured consistency in:
  - `price`
  - `kilometer`
  - `yearOfRegistration`
  - `powerPS`

### 🏷️ Categorical Data Processing
- Identified all categorical columns automatically
- Extracted unique labels for each category
- Cleaned inconsistent and noisy text values

### 🧼 General Cleaning
- Removed irrelevant or redundant entries
- Standardized column formats
- Prepared a clean DataFrame for analysis or modeling

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Seaborn** – Exploratory visualization
- **Matplotlib** – Data visualization
- **Jupyter Notebook**

---


