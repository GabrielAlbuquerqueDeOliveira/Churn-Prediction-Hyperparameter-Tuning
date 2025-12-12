# 📞 Telco Customer Churn-Prediction + ML Hyperparameter Tuning & Model Optimization 📋
This project focuses on developing a strategically optimized Machine Learning model to predict customer churn. Using a Random Forest Classifier combined with advanced hyperparameter tuning and threshold optimization, the model identifies at-risk customers with high precision and recall. The project emphasizes the Precision–Recall trade-off and demonstrates how threshold adjustments can significantly increase business impact by reducing missed churn cases.

---


## 📁 Project Structure

| Path | Description |
|---|---|
| [`Telco_Customer_Churn.ipynb`](https://github.com/GabrielAlbuquerqueDeOliveira/Churn-Prediction-Hyperparameter-Tuning/blob/main/Telco_Customer_Churn.ipynb) | The main notebook containing data preprocessing, hyperparameter tuning, performance evaluation, and threshold optimization

---

## 🚀 Features

- Data Preprocessing: Cleaning and preparing the Telco dataset, converting numeric fields such as TotalCharges, and applying One-Hot Encoding to categorical variables.

- Hyperparameter Tuning: Systematic optimization of the Random Forest model using RandomizedSearchCV to maximize the F1-Score. 🎛️

- Performance Validation: Evaluation using ROC Curve and AUC to measure the model’s predictive power independently of the classification threshold.

- Threshold Optimization: Adjusting the decision threshold from 0.50 to 0.3245, prioritizing Recall and increasing the detection of actual churners from 51% to 77%.

- Error Analysis: Applying the Analyze the Best Models and Their Errors methodology to inspect feature importance and understand which attributes most influence churn. 🔬

- Business Impact Analysis: Visualizing the reduction in False Negatives, demonstrating how the optimized model prevents missed churn opportunities and increases retention potential.

---


## 📦 Dataset
The dataset used in this project is the Telco Customer Churn dataset, originally provided by IBM Sample Data Sets.

It contains 7,043 customers, including:

Demographic information

Account and contract details

Service usage patterns

The dataset is publicly available on Kaggle.

---

## ▶️ How to Run
1. Clone this repository:

```bash
git clone https://github.com/GabrielAlbuquerqueDeOliveira/Telco-Customer-Churn-Prediction-Optimization-and-Machine-Learning-.git
cd Telco-Customer-Churn-Prediction-Optimization-and-Machine-Learning-
```
2. Install the dependencies (recommended: use a virtual environment):
```bash

pip install -r requirements.txt
```
3. Run the notebook:

Open the file Telco_Churn_Optimization.ipynb directly in Jupyter Notebook or JupyterLab.

---

## 🛠️ Technologies Used
Python 3.10+

Pandas & NumPy

Scikit-learn

Matplotlib & Seaborn

Jinja2

---

## 👤 Author

Developed by Gabriel Albuquerque de Oliveira
🔗 GitHub
📧 gabriel.ooo@hotmail.com
💼 LinkedIn

---


## 📄 License

This project is licensed under the terms of the MIT License.

```
MIT License

Copyright (c) 2025 Gabriel Albuquerque

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
```

## 🤝 Contributions
Contributions are welcome! Feel free to open issues or pull requests with suggestions and improvements.
