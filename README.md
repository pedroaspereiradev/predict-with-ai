# 🏦 Bank Credit Score Classification

An end-to-end machine learning project designed to analyze bank client data and automatically classify their credit scores. This system helps financial institutions streamline their credit risk assessment process and make data-driven decisions.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Technologies Used](#technologies-used)
- [Machine Learning Models](#machine-learning-models)
- [Results & Evaluation](#results--evaluation)

## 🔍 Project Overview
Assessing credit risk is one of the most critical operations in the banking sector. Traditionally, this process involves manual verification, which is time-consuming and prone to human error. 

This project implements a Machine Learning solution to automatically classify a client's credit score based on their financial and personal history. 

## ⚙️ Problem Statement
The goal is to provide the bank with a robust model capable of ingesting raw client profiles and generating one of three risk labels:
* 🔴 **Poor:** High-risk profile.
* 🟡 **Standard:** Medium-risk profile.
* 🟢 **Good:** Low-risk profile.

## 🛠️ Technologies Used
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas
* **Machine Learning:** Scikit-Learn
* **Algorithms:** Random Forest Classifier, K-Nearest Neighbors (KNN)

## 🤖 Machine Learning Models
To solve this classification problem, two primary algorithms were trained and compared:

1. **Random Forest Classifier:** An ensemble learning method that operates by constructing multiple decision trees. It is highly robust against overfitting and handles non-linear financial data exceptionally well.
2. **K-Nearest Neighbors (KNN):** A distance-based classifier that categorizes clients based on how closely their financial behaviors resemble those of their nearest neighbors in the dataset.
