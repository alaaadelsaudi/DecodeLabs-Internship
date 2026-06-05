# 📱 Mobile Price Classification Project - Decodelabs Internship

An end-to-end Machine Learning classification project built during my Data Science internship at **Decodelabs**. This project successfully implements the comprehensive data science pipeline across 5 key core tasks to predict mobile phone price ranges based on technical specifications.

## 📌 Project Overview
The objective of this project is to build a robust multi-class predictive model that classifies mobile phones into four distinct price categories (`0: Low Cost`, `1: Medium Cost`, `2: High Cost`, `3: Very High Cost`) based on features like RAM, Battery Power, Internal Memory, and Camera Pixels.

---

## 🛠️ Internship Tasks Implemented

### 🔹 Task 1: Data Collection & Dataset Understanding
* Loaded the official `train.csv` dataset and explored its shape, feature counts, and categorical structures.
* Understood feature definitions (e.g., `battery_power`, `ram`, `px_height`, etc.) and mapped their importance.

### 🔹 Task 2: Data Cleaning & Preprocessing
* Inspected the dataset for missing values (`isnull().sum()`) and handled data quality assurance.
* Checked for and removed structural duplicates to ensure robust, leak-free training.
* Validated data types to ensure compatibility with scientific libraries.

### 🔹 Task 3: Exploratory Data Analysis (EDA)
* Generated statistical calculations (`describe()`) to capture the distribution boundaries of the features.
* Derived statistical correlations to find key business drivers affecting market pricing.

### 🔹 Task 4: Data Visualization
* Created visual charts including a target class count plot to confirm standard data balance.
* Designed correlation heatmaps to observe inter-feature relations.
* Plotted a comprehensive **Boxplot (RAM vs Price Range)** to explicitly capture how memory boundaries dictate pricing.

### 🔹 Task 5: Predictive Model Building & Evaluation
* Segregated features and targets, split data into an 80-20 train-test ratio, and balanced numerical spreads using `StandardScaler`.
* Built and optimized a **Random Forest Classifier** model.
* Validated results utilizing detailed precision, recall, and f1-score matrices.

---

## 📊 Performance Results & Key Insights
* **Model Accuracy:** `89.25%` 🎯
* **Key Insight 1:** **RAM** proved to be the single most influential driver for price classification. Clear independent tier increments were visually captured during EDA.
* **Key Insight 2:** The model showed balanced precision and recall scores across all four pricing categories (ranging from `0.78` to `0.96`), ensuring high real-world reliability.

---

## 🚀 Technologies & Packages Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

