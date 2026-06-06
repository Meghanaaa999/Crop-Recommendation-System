# 🌾 Crop Recommendation System

## 📖 Overview

The Crop Recommendation System is a Machine Learning project that recommends the most suitable crop for cultivation based on soil nutrients and environmental conditions.

The system analyzes factors such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH level, and rainfall to predict the best crop for farmers.

This project applies data preprocessing, visualization, feature engineering, and multiple machine learning algorithms to achieve accurate crop predictions.

---

## 🎯 Objectives

- Recommend the best crop based on soil and weather conditions.
- Help farmers make data-driven agricultural decisions.
- Improve crop yield and productivity.
- Compare different machine learning models for prediction.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- Fast-ML

### Machine Learning Algorithms
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Dataset Features

The dataset contains the following attributes:

| Feature | Description |
|----------|-------------|
| N | Nitrogen Content |
| P | Phosphorus Content |
| K | Potassium Content |
| Temperature | Temperature (°C) |
| Humidity | Relative Humidity (%) |
| pH | Soil pH Value |
| Rainfall | Rainfall (mm) |
| Label | Recommended Crop |

---

## 🔍 Project Workflow

### 1. Data Collection
- Loaded crop recommendation dataset using Pandas.

### 2. Data Preprocessing
- Checked missing values.
- Checked duplicate records.
- Removed outliers.
- Identified constant features.

### 3. Data Visualization
- Box plots
- Distribution plots
- Correlation heatmaps
- Feature analysis using Plotly and Seaborn

### 4. Feature Engineering
- Feature scaling using MinMaxScaler.
- Feature standardization using StandardScaler.

### 5. Model Training
The following machine learning models were trained and evaluated:

- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

### 6. Model Evaluation
- Accuracy Score
- Classification Report
- Cross Validation

### 7. Prediction
The trained model predicts the most suitable crop based on user input values.

---

## 📂 Project Structure

```text
Crop-Recommendation-System/
│
├── Crop_Recommendation_Project.ipynb
├── Crop_recommendation.csv
├── README.md
│
├── images/
│   ├── heatmap.png
│   ├── boxplot.png
│   └── accuracy_comparison.png
│
└── requirements.txt
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Crop-Recommendation-System.git
cd Crop-Recommendation-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Crop_Recommendation_Project.ipynb
```

---

## 📈 Models Used

| Model | Purpose |
|---------|----------|
| KNN | Crop Classification |
| Decision Tree | Crop Classification |
| Random Forest | Crop Classification |

---

## 🌱 Sample Input

```python
N = 90
P = 42
K = 43
Temperature = 20.87
Humidity = 82.00
pH = 6.50
Rainfall = 202.93
```

### Predicted Crop

```text
Rice
```

---

## 📷 Results

The project includes:

- Feature distribution analysis
- Correlation heatmaps
- Outlier detection
- Accuracy comparison graphs
- Crop prediction output

---

## 🔮 Future Enhancements

- Web Application using Flask
- Weather API Integration
- Fertilizer Recommendation System
- Crop Yield Prediction
- Disease Detection Module
- Mobile Application

---

## 👩‍💻 Author

**Meghana Arthimalla**

B.Tech Student | Machine Learning Enthusiast

GitHub: https://github.com/your-github-username

---

## ⭐ If you found this project useful, please give it a star on GitHub!

This version looks professional and is suitable for placement, resume projects, and GitHub portfolios.

give simply dont give author 
# 🌾 Crop Recommendation System

## Overview

This project uses Machine Learning to recommend the most suitable crop based on soil nutrients and environmental conditions. It helps farmers make better decisions for improved agricultural productivity.

## Features

- Crop prediction based on soil and weather data
- Data preprocessing and cleaning
- Outlier detection and removal
- Data visualization
- Multiple machine learning models
- Performance comparison of models

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn

## Dataset Attributes

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

## Machine Learning Models

- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Scaling
5. Model Training
6. Model Evaluation
7. Crop Prediction

## Installation

```bash
git clone https://github.com/your-username/Crop-Recommendation-System.git
cd Crop-Recommendation-System
```

Install required libraries:

```bash
pip install -r requirements.txt
```

## Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Crop_Recommendation_Project.ipynb
```

## Output

The system predicts the most suitable crop based on the given input values.

## Future Improvements

- Weather API Integration
- Fertilizer Recommendation
- Crop Yield Prediction
- Web Application Development
