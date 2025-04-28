# Diabetes <img src="images/blue_circle.svg" width="20" height="20" alt="Diabetes Symbol"> Data Analysis Project

## Overview
This project analyzes the Pima Indian Diabetes Dataset to explore glucose as a predictor of diabetes risk. The analysis uses Python for data cleaning, visualization, and logistic regression modeling.

## Project Structure
```
diabetes_da_project/
├── data/
│   └── diabetes_dataset.csv
├── images/
│   ├── blue_circle.svg
│   ├── diabetes.png
│   ├── splom.png 
│   ├── parallel.png
│   ├── lr_curve.png
│   └── lr_plane.png
├── diabetes_da_project.ipynb
├── README.md
└── requirements.txt
```

## Dataset
The analysis uses the Pima Indian Diabetes Dataset, which contains health metrics for Native-American women from the Gila River Indian Community. Features include:
- Pregnancies
- Glucose levels
- Blood pressure
- Skin thickness
- Insulin levels  
- BMI
- Diabetes pedigree function
- Age
- Diabetes outcome (0/1)

## Analysis Approach
1. Data cleaning and validation
2. Exploratory data analysis 
3. Visualization using:
   - Histograms
   - Correlation matrices
   - Pairplots
   - Interactive 3D plots
4. Logistic regression modeling:
   - Model 1: Glucose vs Outcome
   - Model 2: Glucose + Insulin vs Outcome
   - Cross-validation testing

## Key Findings
- Glucose levels strongly predict diabetes risk
- Model achieved ~73% accuracy using glucose alone
- Adding insulin as predictor did not significantly improve model performance 
- Higher glucose levels correlate with increased diabetes risk

## Requirements
```python
numpy
pandas  
matplotlib
seaborn
plotly
statsmodels
scikit-learn
patsy
```

## Usage
1. Clone this repository: `git clone https://github.com/timo-barker/diabetes_da_project.git`
2. Install required packages: `pip install -r requirements.txt`
3. Open `diabetes_da_project.ipynb` in Jupyter