# Molecular Solubility Prediction using Machine Learning

This project focuses on predicting the aqueous solubility of chemical compounds, a critical parameter in drug discovery and material science. Using the **Delaney (ESOL) Dataset**, I developed a regression model that correlates physicochemical descriptors with measured solubility.

## Overview
The goal of this project was to transition from raw chemical data to a predictive tool. I leveraged **RDKit** for molecular processing and **Scikit-Learn** for machine learning, achieving a robust model capable of explaining molecular behavior through data.

## Tech Stack
* **Language:** Python 3.x
* **Chemistry Informatics:** RDKit
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (StandardScaler, Linear Regression)
* **Visualization:** Matplotlib, Seaborn

## Methodology
1. **Data Cleaning:** Normalization of compound identifiers and removal of invalid SMILES structures.
2. **Exploratory Data Analysis (EDA):** Visualization of chemical property distributions and correlation heatmaps.
3. **Feature Engineering:** Selection of key descriptors including Molecular Weight, Polar Surface Area (PSA), and H-Bond Donors.
4. **Data Preprocessing:** Implementation of `StandardScaler` to ensure feature parity.
5. **Modeling:** Trained a Linear Regression model with an 80/20 train-test split.

## Key Results
* **Training R²:** 0.68
* **Test R²:** 0.69
* **Main Insight:** **Polar Surface Area (PSA)** was identified as the most influential positive predictor of solubility, highlighting the critical role of surface polarity in solute-solvent interactions.



## How to use
1. Clone the repository
   ```bash
   git clone [https://github.com/LeonettMoon/Solubility.git](https://github.com/LeonettMoon/Solubility.git)
