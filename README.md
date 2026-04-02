# 🚗 Car Evaluation Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **evaluation of cars** based on multiple features such as buying price, maintenance cost, number of doors, seating capacity, luggage boot size, and safety.

The goal is to build a **classification model** that can automatically determine whether a car is:

* Unacceptable
* Acceptable
* Good
* Very Good

---

## 🎯 Objectives

* Perform **data cleaning and preprocessing**
* Apply **Exploratory Data Analysis (EDA)**
* Convert categorical data into numerical format
* Train multiple **Machine Learning models**
* Compare model performance and accuracy
* Build a reliable prediction system

---

## 📂 Dataset Information

* Dataset Name: **Car Evaluation Dataset**
* Source: Kaggle
* Type: Classification

### 🔑 Features:

| Feature  | Description                          |
| -------- | ------------------------------------ |
| buying   | Buying price (low, med, high, vhigh) |
| maint    | Maintenance cost                     |
| doors    | Number of doors                      |
| persons  | Seating capacity                     |
| lug_boot | Luggage boot size                    |
| safety   | Safety level                         |

### 🎯 Target:

* car_acceptability (unacc, acc, good, vgood)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

* Handled missing values (if any)
* Encoded categorical variables using **Label Encoding**
* Feature selection

### 2️⃣ Exploratory Data Analysis (EDA)

* Count plots for categorical features
* Correlation analysis
* Class distribution visualization

### 3️⃣ Model Building

Applied multiple ML algorithms:

* Decision Tree Classifier 🌳
* Random Forest Classifier 🌲
* Support Vector Machine (SVM)
* Logistic Regression

---

## 📊 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Decision Tree       | ~95%     |
| Random Forest       | ~94%     |
| SVM                 | ~94%     |
| Logistic Regression | ~92%     |

> ✅ **Best Model:** Decision Tree Classifier

---

## 📈 Sample Visualization

![Comparison](https://github.com/Purva1812/car-evaluation/blob/main/assets/Acc%20Comparison.png?raw=true)

```

---

## 🧠 Key Insights

* Safety feature has a strong impact on car acceptability
* Cars with higher capacity and safety tend to be rated better
* Random Forest performs best due to handling categorical patterns effectively

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/car-evaluation-prediction.git

# Navigate to project folder
cd car-evaluation-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📁 Project Structure

```
car-evaluation-prediction/
│
├── data/
│   └── car_data.csv
├── notebooks/
│   └── Car_Evaluation.ipynb
├── assets/
│   └── confusion_matrix.png
├── requirements.txt
└── README.md
```

---

## 💡 Future Improvements

* Hyperparameter tuning
* Deploy model using Flask/Streamlit
* Add real-time prediction UI
* Use advanced boosting algorithms (XGBoost, LightGBM)

---

## 👩‍💻 Author

**Purva Naikwadi**
Mechatronics Engineer | Data Science Enthusiast

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
✅ Help you **upload this to GitHub step-by-step**
✅ Add **100% accuracy optimized code (interview-ready)**
