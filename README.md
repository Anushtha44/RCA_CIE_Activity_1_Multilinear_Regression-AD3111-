# Bengaluru House Price Prediction using Multiple Linear Regression

## 📌 Project Overview
This project implements Multiple Linear Regression to estimate house prices in Bengaluru, India, using numerical features of residential properties. It was completed as part of RCA CIE Activity 1.

The project focuses on understanding the mathematical foundation of regression, performing manual calculations, implementing regression using Scikit-learn, evaluating model performance, and analyzing regression assumptions.

## 🎯 Objectives
- Understand the mathematical foundation of Multiple Linear Regression.
- Perform manual regression calculations using the Normal Equation.
- Verify manually calculated coefficients using Scikit-learn.
- Compare Single Linear Regression and Multiple Linear Regression.
- Evaluate models using regression metrics.
- Analyze correlation, multicollinearity, and residuals.

## 📊 Dataset
**Dataset Name:** Bengaluru House Price Dataset

The dataset contains residential property information from Bengaluru, India.

### Target Variable
- `price` – House price in lakhs.

### Selected Predictors
- `total_sqft` – Total area of the property in square feet.
- `bedrooms` – Number of bedrooms.
- `bath` – Number of bathrooms.
- `balcony` – Number of balconies.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Google Colab / Jupyter Notebook

## 🧹 Data Preprocessing
The following preprocessing steps were performed:

- Inspected dataset structure and statistical information.
- Identified missing values.
- Converted `total_sqft` values into numerical format.
- Handled square-footage ranges using their midpoint.
- Extracted bedroom count from the `size` column.
- Removed duplicate records.
- Filtered unrealistic square-footage values.
- Handled missing predictor values using median imputation.

## 🧮 Methodology

### 1. Manual Multiple Linear Regression
- Selected a small sample of observations.
- Constructed the design matrix.
- Calculated regression coefficients using the Normal Equation approach.
- Calculated a sample prediction and residual.

### 2. Library Verification
Manually calculated regression coefficients were compared with coefficients obtained using Scikit-learn.

### 3. Model Comparison
The following models were implemented:

- Single-feature Linear Regression using square footage.
- Multiple Linear Regression using square footage, bedrooms, bathrooms, and balconies.

### 4. Model Evaluation
Models were evaluated using:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score
- Adjusted R² Score

### 5. Diagnostic Analysis
- Correlation matrix and heatmap.
- Variance Inflation Factor (VIF).
- Residual-versus-predicted plot.
- Residual histogram.
- Actual-versus-predicted plot.
- Regression assumptions analysis.

## 📈 Results

| Model | MAE | MSE | RMSE | R² |
|---|---|---|---|---|
| Single Linear Regression | [Insert] | [Insert] | [Insert] | [Insert] |
| Multiple Linear Regression | [Insert] | [Insert] | [Insert] | [Insert] |

**Best-performing model on test data:** [Insert model name]

## 🔍 Key Observations
- [Insert observation about model comparison.]
- [Insert observation about predictor correlations.]
- [Insert observation about VIF.]
- [Insert observation about residual analysis.]

## ⚠️ Limitations
- Location and neighborhood information were not included in the selected model.
- Amenities and property quality were not considered.
- Outliers may influence regression coefficients.
- The model assumes approximately linear relationships.
- Predictions outside the training-data range may be unreliable.

## ▶️ How to Run the Project
1. Download or clone this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Upload the dataset if required.
4. Run all notebook cells sequentially.
5. Review the model outputs, evaluation metrics, and visualizations.

## 📁 Project Structure

```text
RCA-CIE-Activity-1/
│
├── RCA_CIE_Activity1_Multiple_Linear_Regression.ipynb
├── Bengaluru_House_Data.csv
└── README.md
```



*This project was completed for academic learning purposes.*
