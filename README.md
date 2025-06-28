# traffic_accident_risk_prediction
# 🚦 Traffic Accident Risk Prediction Using Machine Learning

This project focuses on predicting the **severity level** of road accidents in India using **machine learning models** trained on historical accident data. The goal is to help reduce accidents and save lives by identifying high-risk scenarios based on factors like driver, environment, road conditions, and time.

---

## 📌 Problem Statement

Road accidents are a major cause of fatalities and injuries in India. To proactively prevent accidents, we aim to predict the **severity** of an accident before it occurs, using features such as:
- Time of the day
- Road & weather conditions
- Driver demographics
- Vehicle type and traffic control factors

The output is a classification of accident severity: **Fatal**, **Serious**, or **Minor**.

---

## 🔍 Project Approach

- **Type**: Supervised Machine Learning – **Classification**
- **Algorithms Used**: 
  - Logistic Regression
  - Random Forest Classifier
- **Workflow**:
  1. Data cleaning and preprocessing
  2. Exploratory Data Analysis (EDA)
  3. Feature engineering
  4. Model training & evaluation
  5. Future: Real-time data integration & deployment

---

## 📊 Dataset Information

- **Source**: Synthesized from real datasets including:
  - Ministry of Road Transport & Highways (MoRTH)
  - Open Government Data (OGD) India
  - State police/transport accident records
- **Update Frequency**: Annually (Last update: March 2025)
- **Key Attributes**:
  - Accident timing: Year, Month, Day, Time
  - Severity levels: Fatal, Serious, Minor
  - Vehicle & driver info: Age, gender, license status, alcohol use
  - Road, weather, and environmental factors
- **Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/khushikyad001/india-road-accident-dataset-predictive-analysis)

---

## 🛠️ Tools & Technologies Used

- **Python** – Core programming language
- **pandas, numpy** – Data handling and preprocessing
- **matplotlib, seaborn** – Data visualization and EDA
- **scikit-learn** – Machine learning models and metrics
- **VS Code** – Development environment
- **Git & GitHub** – Version control and code sharing

> These tools enable efficient transformation of raw accident data into valuable risk predictions.

---

## 📘 Notebooks

- [`EDA Notebook`](notebooks/eda.ipynb): Data cleaning, preprocessing, and insightful visualizations.
  - Includes graphs for accident severity by time, weather, and road type
  - Extracted features like `Hour`, simplified weather categories, and removed nulls

<!-- Add screenshot below (optional) -->
<!-- ![EDA Preview](outputs/eda_visual_sample.png) -->

---

## 🤖 Model Training & Results

🚧 *Coming Soon...*

The next phase will include:
- Model training (Random Forest & Logistic Regression)
- Performance metrics: Accuracy, Precision, Recall, Confusion Matrix
- Final model saved in `models/` folder
- Output predictions from new data in `scripts/predict.py`

---

## 📦 Project Structure

```bash
traffic-accident-risk-prediction/
├── data/                     # Raw dataset (CSV)
├── notebooks/                # Jupyter notebooks
│   ├── eda.ipynb             # EDA and preprocessing
│   └── model_training.ipynb  # (Upcoming) ML model training
├── models/                   # Trained model (pickle)
├── scripts/                  # Prediction script
├── outputs/                  # Charts, graphs, confusion matrix
├── README.md                 # Project overview
