
---

# 🎯 Binary Classification on MAGIC Gamma Telescope Dataset

This repository presents a complete pipeline for **binary classification** using the MAGIC Gamma Telescope dataset. The objective is to classify particle types (gamma vs hadron) using various machine learning models and visualize their performance under different hyperparameters.

---

## 📌 Overview

The project includes:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Model training (Logistic Regression, Decision Tree, Random Forest, SVM)
* Hyperparameter tuning
* Precision, Recall, F1-Score analysis
* Visualization of results for interpretability

---

## 📊 Dataset

The **MAGIC Gamma Telescope dataset** is used for classification of signal vs background based on 10 real-valued features.
📁 [UCI MAGIC Data Info](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope)

---

## 🧠 Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)

Each model is evaluated using:

* Confusion Matrix
* Classification Report
* Precision, Recall, F1-Score
* Parameter tuning (e.g., `max_depth`, `n_estimators`, `C`, `kernel`)

---

## 📈 Visualizations

* Histograms comparing feature distributions for each class
* Line plots to observe metric changes across different parameter values
* Bar charts to summarize model performance

---

## 🛠️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/HaseebUlHassan437/binary-classification-on-Magic-dataset-.git
cd binary-classification-on-Magic-dataset-
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
venv\Scripts\activate     # Windows
# or
source venv/bin/activate  # Linux/macOS
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook fcc_MAGIC(dataset).ipynb
```

---

## 📚 Topics Covered

* Binary Classification
* Model Evaluation Metrics
* Data Visualization
* Hyperparameter Tuning
* Exploratory Data Analysis (EDA)

---


---

## 📬 Contact

For questions, feedback, or suggestions:
📧 **[haseebulhassan1172003@gmail.com](mailto:haseebulhassan1172003@gmail.com)**

---
