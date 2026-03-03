# Cirrhosis Patient Survival Prediction
This project utilizes machine learning to predict the survival outcomes of patients with cirrhosis. By analyzing clinical and biochemical features, the system classifies patient status to assist in medical prognosis and risk assessment.

## 🚀 Project Overview
Cirrhosis is a late-stage liver disease where healthy liver tissue is replaced with scar tissue. This project implements a data-driven approach to predict patient survival using a variety of classification algorithms, ensuring high reliability through rigorous preprocessing and evaluation.

## 🛠️ Technical Workflow

**Data Integrity**: Comprehensive validation to identify and handle duplicate entries and null values.
**Feature Engineering**:
**Label Encoding**: Converted categorical string features into numerical formats for model compatibility.
**Correlation Analysis**: Used heatmaps to identify key relationships between clinical features and survival status.
**Visualization**: Employed histograms and scatterplots to uncover data patterns and distributions.
**Handling Overfitting**: Utilized **Learning Curves** to monitor model performance and ensure generalization on unseen data.
**Imbalance & Overflow Correction**: Specific adjustments were made to the Random Forest and Decision Tree models to resolve overflow issues and stabilize training.

## 🤖 Models Implemented
The project evaluates and compares three primary classifiers:

**Support Vector Machine (SVM)**: Effective for high-dimensional clinical data.
**Random Forest**: An ensemble method used to improve predictive accuracy and control over-fitting.
**Decision Tree**: Provides a clear, interpretable logic for clinical decision-making.

## 📊 Evaluation Metrics
Models were assessed using a comprehensive suite of metrics:

**Accuracy Score**: Overall correctness of the model.
**Confusion Matrix**: Visualized to assess performance across different classes (survived vs. deceased).
**Learning Curves**: To validate that the model is learning effectively from the training set without memorizing noise.

## 🧰 Tech Stack

**Python**: Core programming language.
**Pandas & NumPy**: Data manipulation and numerical analysis.
**Matplotlib & Seaborn**: Statistical data visualization.
**Scikit-Learn**: Machine learning modeling, preprocessing, and evaluation.
