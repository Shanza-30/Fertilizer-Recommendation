# Fertilizer Recommendation ML Project 🌾🤖

## Project Overview
This project predicts the most suitable fertilizer for crops based on soil conditions, crop type, and environmental factors. It is designed to help farmers make data-driven decisions to improve crop yield.

**Dataset:** [Fertilizer Recommendation Dataset - Kaggle](https://www.kaggle.com/datasets/miadul/fertilizer-recommendation-dataset/data)

**Target Variable:** `Fertilizer Name` (Classification Problem)


## Features
- Temperature
- Humidity
- Moisture
- Soil Type
- Crop Type
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- **NPK Ratio** (Engineered Feature)
- **Moisture Level** (Dry, Medium, Wet)

---

## Model
- Random Forest Classifier (Best Performing Model)
- Hyperparameter tuning for optimal accuracy
- Cross-validation for robust evaluation
- Feature importance visualization

**Final Accuracy:** ~95% (depending on dataset split)

---

## Steps Performed
1. Data Loading & Cleaning
2. Exploratory Data Analysis (Graphs: Distribution, Correlation, Moisture Level)
3. Feature Engineering (NPK Ratio & Moisture Level)
4. Encoding Categorical Variables
5. Train-Test Split
6. Model Training (Tuned Random Forest)
7. Model Evaluation (Accuracy, Classification Report, Confusion Matrix)
8. Model Saving (`fertilizer_model.pkl`)

---

## Graphs Included
- Fertilizer Distribution
- Temperature Distribution
- Correlation Heatmap
- Moisture Level Distribution
- Confusion Matrix
- Feature Importance

---
