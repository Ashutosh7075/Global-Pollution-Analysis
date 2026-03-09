# Global Pollution Analysis and Energy Recovery

## Overview
This project analyzes global pollution data and explores how pollution sources such as industrial waste and CO2 emissions can contribute to energy recovery. The project uses data preprocessing, exploratory data analysis (EDA), and machine learning models to understand pollution trends and predict energy recovery potential.

## Dataset
The dataset contains information about:
- Air Pollution Index
- Water Pollution Index
- Soil Pollution Index
- Industrial Waste (in tons)
- CO2 Emissions (in MT)
- Renewable Energy (%)
- Plastic Waste Produced
- Energy Consumption Per Capita
- Population
- GDP Per Capita
- Energy Recovered (in GWh)

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset using pandas
- Checked dataset information and statistical summary
- Handled missing values
- Encoded categorical variables such as country names
- Normalized pollution indices using StandardScaler

### 2. Exploratory Data Analysis (EDA)
Visualizations used:
- Correlation heatmap
- CO2 emissions trend over years
- Industrial waste distribution using box plots
- Scatter plot between industrial waste and energy recovery

### 3. Feature Engineering
Created new features such as:
- Energy consumption per capita adjusted with population

### 4. Machine Learning Models

#### Linear Regression
Used to predict **Energy Recovered (in GWh)** based on:
- Air Pollution Index
- CO2 Emissions
- Industrial Waste

Evaluation metrics:
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

#### Logistic Regression
Used to classify pollution severity levels into:
- Low
- Medium
- High

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results
The analysis shows that pollution indicators such as industrial waste and CO2 emissions can help estimate energy recovery potential. The classification model successfully categorizes pollution levels, which can assist policymakers in identifying regions with high environmental risk.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure
Global-Pollution-Analysis
│
├── Global_Pollution_Analysis.ipynb
├── Global_Pollution_Analysis_dataset.csv
└── README.md

## Conclusion
Waste-to-energy technologies can help reduce environmental pollution while generating useful energy. Machine learning models can assist in understanding pollution patterns and predicting energy recovery opportunities.
