# Backpack Price Prediction 🎒

This project aims to predict the prices of backpacks based on various attributes like brand, material, size, and more. It was developed using Python and popular data science libraries.

## Project Overview
The goal is to build a regression model that accurately estimates the price of a backpack given its specifications.

## Dataset Features
- **Brand**: Brand of the backpack.
- **Material**: Material used (Leather, Canvas, Nylon, Polyester).
- **Size**: Small, Medium, Large.
- **Compartments**: Number of compartments.
- **Laptop Compartment**: Whether it has a dedicated space for a laptop.
- **Waterproof**: Waterproofing status.
- **Style**: Backpack, Tote, Messenger.
- **Color**: Various colors.
- **Weight Capacity (kg)**: Maximum weight the backpack can carry.
- **Price**: Target variable.

## Workflow
1. **Data Cleaning**: Handled missing values using statistical distribution-based imputation for categorical variables.
2. **Feature Engineering**: 
    - Label Encoding for categorical features.
    - Polynomial Features (Degree 2) to capture non-linear relationships.
3. **Modeling**:
    - Simple Linear Regression.
    - **Polynomial Regression** (optimized for better accuracy).
4. **Submission**: Predictions are saved in `sub_poly.csv`.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
