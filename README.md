# Car Evaluation Using Decision Tree 🚗🌳

A data mining project focused on building a decision tree classifier to evaluate cars based on multiple features. The model achieved **97% accuracy**, using both **Gini Index** and **Entropy** to guide the splitting criteria.

## 📊 Overview

This project uses a dataset of car characteristics (buying price, maintenance cost, safety, etc.) to predict the final evaluation (unacceptable, acceptable, good, or very good). The goal was to compare how different impurity measures (Gini vs. Entropy) impact model performance.

## 🛠️ Tools & Technologies
- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**

## 📁 Dataset
The dataset includes the following features:
- Buying Price
- Maintenance Cost
- Number of Doors
- Persons Capacity
- Luggage Boot Size
- Safety  
**Target Variable:** Car Evaluation (Class)

## 🧠 Methodology
- Preprocessed categorical variables using **Ordinal Encoding**
- Trained two decision tree models:
  - One using **Entropy (Information Gain)**
  - One using **Gini Index**
- Evaluated performance using train/test split and accuracy score
- Visualized the decision tree structure

## 📈 Results
- Final model score: **97% accuracy**
- Minimal overfitting, and consistent results between both impurity metrics
- Gini performed slightly faster in training time, but both produced similar trees

## 📓 [View Notebook](./decision-tree-car-analysis.ipynb)
