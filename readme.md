# 🔥 Forest Fire Detection using Machine Learning

This project implements a machine learning model to detect forest fires based on various environmental features. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## 📁 Project Structure


forest-fire-detection/
│
├── data/
│ └── forestfire_dataset.csv # Raw dataset
│
├── notebooks/
│ └── forest_fire_analysis.ipynb # Main notebook for EDA + modeling
│
├── src/
│ └── model.py # Optional: model training script
│
├── README.md # Project documentation
├── requirements.txt # List of dependencies
└── .gitignore # Files to ignore in git



## 📊 Dataset Information

- **Source**: [Kaggle / UCI Forest Fire Dataset] (add link if known)
- **Features**:

  - Temperature
  - Relative Humidity
  - Wind
  - Rain
  - Fine Fuel Moisture Code (FFMC)
  - Duff Moisture Code (DMC)
  - Drought Code (DC)
  - Initial Spread Index (ISI)
  - Others...

- **Target**:
  - `Classes` → Binary classification (`fire` = 1, `not fire` = 0)

---

## ✅ Key Features

- Data cleaning (null check, encoding labels)
- Exploratory Data Analysis with visualizations
- Histogram plots using Matplotlib
- Machine Learning Model (Logistic Regression / Random Forest etc.)
- Accuracy and classification report
- Binary class mapping for interpretability

---

## 🚀 how to run

### 1. Clone the repository

git clone https://github.com/nikhilmalgar/forest-fire-detection.git

cd forest-fire-detection

## 2. Install dependencies

pip install -r requirements.txt

## 3. Launch the Jupyter Notebook

jupyter notebook notebooks/forest_fire_analysis.ipynb

## 🧠 Model Training Overview

You can modify the model.py or notebook to:

Train on the Classes column as binary

Visualize performance using confusion matrix

Use train_test_split, StandardScaler, etc.

## 📈 Example Output

Accuracy: 95%

Confusion Matrix

Graphs showing feature distribution

## 🧑‍💻 Author

Nikhil Malagar
B.Tech in CSE (AI & ML) | Passionate about AI, ML, and Full Stack Development

GitHub https://github.com/nikhilmalgar

LinkedIn www.linkedin.com/in/nikhil-malgar-549064262
