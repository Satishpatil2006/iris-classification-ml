# Iris Classification Using Machine Learning

## 📌 Project Overview

This project implements supervised machine learning classification using the Iris dataset. It compares Logistic Regression and Decision Tree classifiers to predict the species of Iris flowers based on their measurements.

## 🎯 Objectives

* Understand supervised machine learning classification.
* Perform exploratory data analysis (EDA).
* Apply feature scaling using StandardScaler.
* Train and test two classification models.
* Evaluate model performance using classification metrics.
* Visualize confusion matrices and decision boundaries.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib
* Jupyter Notebook

## 📊 Dataset

The Iris dataset contains measurements of three Iris flower species:

* Setosa
* Versicolor
* Virginica

The features include sepal length, sepal width, petal length, and petal width.

Dataset source: https://github.com/mwaskom/seaborn-data/blob/master/iris.csv

## ⚙️ Methodology

1. Load the Iris dataset using Pandas.
2. Perform exploratory data analysis using pairplots.
3. Split the dataset into 80% training data and 20% testing data.
4. Scale features using StandardScaler.
5. Train Logistic Regression and Decision Tree models.
6. Evaluate both models using accuracy, precision, recall, and F1-score.
7. Visualize confusion matrices and decision boundaries.
8. Compare the performance of both models.

## 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The actual evaluation results are generated when the notebook is executed.

## 📁 Project Structure

```text
iris-classification-ml/
├── iris_classification_comparison.ipynb
└── README.md
```

## ▶️ How to Run

1. Download or clone this repository.
2. Open `iris_classification_comparison.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required libraries if necessary:
   `pip install pandas numpy scikit-learn seaborn matplotlib`
4. Run all notebook cells.
5. Review the evaluation metrics and visualizations.

## ✅ Conclusion

This project demonstrates how supervised machine learning models can classify Iris flower species. It compares Logistic Regression and Decision Tree classifiers using standard evaluation metrics and visualizations.

## 👨‍💻 Project Type

Machine Learning Classification Project
