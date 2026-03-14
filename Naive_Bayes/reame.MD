# Naive Bayes Classification Analysis

This project explores the **Naive Bayes** probabilistic machine learning algorithm, covering its theoretical foundations and practical implementation in Python.

## 📂 Project Overview
* **Definition**: A probabilistic classifier based on **Bayes' Theorem** used to discriminate between objects based on certain features.
* **The "Naive" Assumption**: Assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.
* **Mathematical Foundation**: Calculates posterior or conditional probability $P(c|x)$ from $P(c)$, $P(x)$, and $P(x|c)$.

## 🚀 Key Features
* **Theoretical Foundations**: Detailed explanations of Bayes' Theorem and the logic behind frequency and likelihood tables.
* **Practical Implementation**: Includes a basic Gaussian model and a real-world application using the **Titanic dataset**.
* **Optimization Insights**: Highlights the algorithm's strength in multi-class problems and scenarios with minimal feature collinearity.

## 🛠️ Technical Workflow
1. **Model Types**: Covers three `scikit-learn` implementations: Gaussian, Multinomial, and Bernoulli.
2. **Data Preparation**: Separates the Titanic dataset into 24 independent features and the target variable.
3. **Training & Prediction**: Utilizes `model.fit()` on a training set of 712 records.

## 📈 Pros & Cons
| Pros | Cons |
| :--- | :--- |
| Fast for real-time and multi-class predictions. | Independence assumption rarely holds in real life. |
| Requires less training data than complex models. | Known as a "bad estimator" for raw probability. |
| Excels with categorical input variables. | Suffers from "Zero Frequency" issues if data is missing. |
