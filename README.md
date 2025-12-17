# 🧠 Neural Networks for Simultaneous Auction Optimization

> **Application of Multi-Layer Perceptron (MLP) models to predict verification outcomes in complex simultaneous auctions.**

[![Python](https://img.shields.io/badge/Made_with-Python-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

## ⚠️ Important Technical Notice
> **The `.ipynb` notebook file is currently under review due to technical issues. I strongly recommend consulting the [Final Report (PDF)](Aplicação%20de%20Redes%20Neurais%20para%20otimização%20de%20processos%20de%20leilões%20simultâneos.pdf), which contains the complete source code, methodology, and full analysis.**

---

## 🎯 Project Overview

This project explores the use of **Artificial Neural Networks** to optimize the verification process of simultaneous multi-round auctions (often used for frequency spectrum sales). 

The "Auction Verification" problem involves complex calculations to ensure the validity of bids and outcomes. By training a regression model, we aim to predict these outcomes, potentially replacing costly computational verification with rapid machine learning predictions.

### 📂 Repository Contents

| File | Description |
|------|-------------|
| **[`Final Report.pdf`](Aplicação%20de%20Redes%20Neurais%20para%20otimização%20de%20processos%20de%20leilões%20simultâneos.pdf)** | The complete documentation, including the Python code snippets, theoretical background, and interpretation of results. |
| *`notebook.ipynb`* | *(Currently unavailable - Under Maintenance)* |

---

## 🛠️ Methodology & Data

The project utilizes the **"Auction Verification"** dataset from the **UCI Machine Learning Repository**.

### 1. Model Architecture
* **Algorithm:** `MLPRegressor` (Multi-Layer Perceptron).
* **Goal:** Regression analysis to predict process capacity and verification time.
* **Environment:** Python (Google Colab).

### 2. Feature Analysis
We analyzed the impact of various auction parameters on the model's predictions, such as:
* `property.price`: The valuation of the auctioned item.
* `property.product`: The type/category of the product.
* `process.capacity`: Capacity constraints of the bidders.

---

## 📊 Key Findings

The model revealed which variables are most critical for the auction mechanism:

1.  **Top Predictors:** The variables `property.price`, `property.product`, and `process.b1.capacity` showed the highest influence on the predictions (average impact > 0.20).
2.  **Winner Impact:** The identity of the winner (`property.winner`) also played a significant role (impact ~0.15).
3.  **Optimization Potential:** The results suggest that Neural Networks can effectively approximate the complex logic of auction verification, offering a faster alternative to traditional algorithmic verification.

---

## 👥 Authors

* **Lauro Aguiar**
* **José Pedro**
* **Miguel**
* **Rafael Alves**

---
*This is an academic project developed for the Market Intelligence course (Economics) at Ibmec.*
