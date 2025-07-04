# Wine Quality Prediction

This project is a machine learning model for predicting wine quality based on physicochemical tests. The dataset is sourced from the [UCI Machine Learning Repository], and this notebook walks through data preprocessing, exploratory data analysis, model training, and evaluation.

## 📁 Project Structure

* `winequality.ipynb`: Jupyter notebook containing the full analysis and model development.
* `winequality.csv`: Wine quality dataset (not included here, expected to be downloaded separately).

## 🧪 Features

The dataset includes the following features:

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Free sulfur dioxide
* Total sulfur dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality (target variable)

## 📊 Exploratory Data Analysis (EDA)

* Distribution of wine quality scores
* Correlation heatmaps to understand feature relationships
* Boxplots to explore outliers and variance in data

## ⚙️ Preprocessing

* Null value checks
* Feature scaling using `StandardScaler`
* Data splitting into training and test sets

## 🤖 Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)

Each model is evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

## 🏆 Results

The best model was selected based on performance metrics on the test set. Hyperparameter tuning was optionally applied using `GridSearchCV`.

## 📌 Requirements

Install the dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook winequality.ipynb
   ```
2. Run all cells sequentially to load the data, train models, and view results.

## 📈 Future Improvements

* Use ensemble learning (e.g., XGBoost, Gradient Boosting)
* Deploy model as a web app
* Perform feature selection and dimensionality reduction


