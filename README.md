# ❤️ Heart Disease Classification using Decision Tree & Random Forest

This repository presents a classification project using **Decision Tree** and **Random Forest** algorithms to predict the presence of heart disease. The notebook demonstrates end-to-end data analysis, model training, and evaluation on a structured medical dataset.

---

## 📁 File Structure

- `Decision_Tree_and_random_Forest_.ipynb`  
  ➤ Main Jupyter Notebook containing all the code, visualizations, and results.

- `data/heart.csv`  
  ➤ The dataset used for classification, consisting of patient-level attributes and a binary target indicating heart disease.

---

## 🔍 Problem Statement

The objective is to build reliable machine learning models that can accurately classify whether a person is at risk of **heart disease** based on various medical features. The dataset contains numerical and categorical attributes such as age, sex, blood pressure, cholesterol levels, etc.

---

## 🧠 ML Workflow Overview

### 1. 📊 Data Preprocessing

- Load the `heart.csv` dataset
- Check for and handle missing values
- Analyze feature distributions and correlations
- Encode categorical variables
- Split data into **train/test** sets

### 2. 🌲 Model Building

- **Decision Tree Classifier**
  - Trained using Gini Index or Entropy
  - Adjustable `max_depth` and `min_samples_split`

- **Random Forest Classifier**
  - Ensemble of Decision Trees
  - Parameters like `n_estimators`, `max_features` tuned
  - Handles overfitting and improves generalization

### 3. 📈 Model Evaluation

Each model is evaluated using:

- **Confusion Matrix**
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Cross-validation scores**

### 4. 📊 Visualizations

- Feature importance plot
- Confusion matrix heatmap
- Decision tree plot (`plot_tree()` or `graphviz`)

---

## 🔧 Tools & Libraries Used

- **Python 3.x**
- **Pandas** – For data manipulation
- **NumPy** – For numerical operations
- **Seaborn & Matplotlib** – For plotting and visualization
- **Scikit-learn** – For ML models, metrics, and preprocessing

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/heart-disease-classification.git
cd heart-disease-classification
```

2. Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Launch the notebook:

```bash
jupyter notebook Decision_Tree_and_random_Forest_.ipynb
```

---

## 🧠 Insights You’ll Gain

- How decision tree depth and node splitting affect performance
- The power of ensemble methods like Random Forest
- Importance of each feature in predicting heart disease
- Model evaluation using real-world health data

---

## 🧑‍💻 Author

Developed by **Nouhith**  
Feel free to fork, star, or contribute to enhance the analysis!

---
