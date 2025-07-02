#  🎓 Optimising Direct Marketing through Data-Driven Analytics and Predictive Models

This repository contains all materials developed for my MSc Research Thesis in **Artificial Intelligence for Business** at the **National College of Ireland**. The project explores how data-driven techniques can optimise direct marketing strategies, with a focus on **customer segmentation** and **predictive modelling**.

---

## 🎯 Project Overview

The primary objective of this research was to enhance the effectiveness of direct marketing campaigns by:

- Preparing and exploring the data through **Exploratory Data Analysis (EDA)**
- Identifying profitable customer segments using **K-means Clustering**
- Predicting customer responses with **Logistic Regression**, **Decision Tree**, and **K-Nearest Neighbours (KNN)**
- Following the **CRISP-DM** methodology to ensure a structured, business-focused approach

The project uses a **real-world dataset** from **iFood**, Brazil’s largest food delivery platform.

---

## 📁 Repository Structure

```
├── case/           # Project and business case overview
├── data/           # Raw, cleaned, and processed datasets
├── notebooks/      # Jupyter notebooks for EDA, clustering, classification, environment info
├── report/         # EDA profiling report (ydata-profiling)
├── figures/        # Visual assets and results
├── MSc-Final-Project.pdf   # Final MSc thesis report
└── README.md       # This file
```

---

## 🧪 Methodology

This project followed the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) methodology:

- **Business Understanding** – Framing the marketing challenge for iFood
- **Data Understanding** – Performing EDA using tools like `ydata-profiling`
- **Data Preparation** – Cleaning, transforming, and engineering features; addressing imbalance
- **Modelling** – Applying clustering and classification algorithms
- **Evaluation** – Using performance metrics and cost-benefit analysis
- **Deployment** – Translating insights into marketing strategy recommendations

---

## 🛠 Design Specification

The implementation was carried out using **Python** in **Jupyter Notebooks**, leveraging libraries such as:
- `pandas`, `numpy`, `matplotlib`, `seaborn` for data handling and visualisation
- `scikit-learn` for machine learning and preprocessing
- `ydata-profiling` for automated EDA

![Design Specification](https://github.com/user-attachments/assets/4ef44731-7e99-458e-af78-b9e7c34ad9c3)

---


## 📊 Key Results

### 🔍 Exploratory Data Analysis (EDA)

Visualisations helped uncover key relationships in the dataset, such as the link between income, education level, and customer response behaviour.

![image](https://github.com/user-attachments/assets/7902f33b-8c70-4e29-a2ac-1b1ecf1688cd)

*Income distribution by education level and demographic characteristics*

---

### 📌 Customer Segmentation

Using **K-means clustering**, customers were segmented into **3 distinct groups** based on demographics, spending, and behaviour:

![image](https://github.com/user-attachments/assets/b91d8967-6b68-405b-9a2a-4d213f47a447)

*Boxplots of key metrics across customer clusters*

| Cluster | Profile |
|---------|---------|
| 0 | Low income, young, high number of children, low campaign response |
| 1 | High income, all age groups, high spending, strong campaign engagement |
| 2 | Mid-level income, middle-aged, moderate campaign response |

---

### 🤖 Predictive Modelling

Three models were compared to predict customer responses to a campaign:

- **Logistic Regression**
- **Decision Tree**
- **K-Nearest Neighbours (KNN)**

Performance was evaluated using **accuracy**, **precision**, **recall**, **ROC AUC**, and **average precision**.

![image](https://github.com/user-attachments/assets/3fd9488b-802b-45e3-b46e-949d2725da50)

*Performance comparison across key metrics*


After **hyperparameter tuning**, **Logistic Regression** proved to be the most balanced model.

![image](https://github.com/user-attachments/assets/23632066-fcf3-48a1-9b58-5761c1079234)

*Logistic Regression performance after tuning*


![image](https://github.com/user-attachments/assets/c53308e2-adb4-4c33-b4f1-b0c4c3b46b3f)

*Confusion Matrix of the optimised model on the test set*

---

### 💰 ROI Impact

- **Baseline Campaign** (contacting everyone): Net **loss** of **586MU**
- **Model-Based Campaign** (contacting only predicted responders): Net **profit** of **183MU**

This demonstrates how predictive modelling can significantly reduce costs and improve the ROI of marketing campaigns.

---

## 📘 Full Report

The complete MSc thesis, including literature review, methodology, implementation, and results, is available here:  
📄 **[MSc-Final-Project.pdf](./MSc-Final-Project.pdf)**

---

## 📌 Future Improvements

- Explore ensemble learning and deep learning models
- Incorporate real-time campaign response data
- Develop a web dashboard for marketers to use model outputs

---

## 👩‍💻 Author

**Karla Priscila Vale de Sousa**  
MSc in Artificial Intelligence for Business  
National College of Ireland  
Supervisor: Victor Del Rosal

---
