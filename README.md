<div align="center">

# Banknote Authentication

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20ML%20Repository-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-1abc9c?style=for-the-badge)

Binary classification of banknotes as **authentic or forged**
using statistical features extracted from banknote images.

**0 → Authentic**  
**1 → Forged**

</div>

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Methodology](#methodology)
- [Model Performance](#model-performance)
- [Key Findings](#key-findings)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [References](#references)

---

## About the Project

<!-- Write this after you have explored the problem more. -->

### What this project covers

<!-- Fill this in as the project develops. -->

---

## Dataset

| Property | Details |
|----------|---------|
| **Source** | UCI Machine Learning Repository |
| **Samples** | |
| **Features** | |
| **Target** | Authentic / Forged |
| **Missing Values** | |
| **Feature Type** | Numerical |

---

## Exploratory Data Analysis

<!-- Add observations and selected visualizations here later. -->

---

## Methodology

The project follows a structured machine-learning workflow:

```text
Raw UCI Data
        │
        ▼
Data Loading & Validation
        │
        ▼
Exploratory Data Analysis
├── Feature distributions
├── Relationships between variables
└── Target distribution
        │
        ▼
Train / Test Split
        │
        ▼
Preprocessing
        │
        ▼
Model Training
├── K-Nearest Neighbors
└── Logistic Regression
        │
        ▼
Cross-Validation & Model Comparison
        │
        ▼
Final Evaluation
├── Accuracy
├── Precision
├── Recall
└── F1-score