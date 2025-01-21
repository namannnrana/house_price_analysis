# house_price_analysis
# House Price Prediction using Multiple Linear Regression

## 📌 Project Overview
This project implements **Multiple Linear Regression** to predict **house prices** (MEDV) based on various features from the **Boston Housing dataset**. The model is trained and evaluated using **Scikit-learn**.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset
The dataset contains various features such as:
- **CRIM** - Per capita crime rate
- **ZN** - Proportion of residential land zoned for large lots
- **INDUS** - Proportion of non-retail business acres
- **CHAS** - Charles River dummy variable
- **NOX** - Nitrogen oxide concentration
- **RM** - Average number of rooms per dwelling
- **AGE** - Proportion of owner-occupied units built before 1940
- **DIS** - Weighted distance to employment centers
- **RAD** - Accessibility to radial highways
- **TAX** - Property tax rate
- **PTRATIO** - Pupil-teacher ratio
- **B** - Proportion of Black residents
- **LSTAT** - Percentage lower status population
- **MEDV** - Median house value (Target Variable)

## 🔄 Data Preprocessing
1. **Exploratory Data Analysis (EDA)**
   - Scatter plots for each feature vs. **MEDV**.
   - Correlation heatmap to identify multicollinearity.
   - Boxplot to detect outliers in **MEDV**.
2. **Feature Engineering**
   - Standardization using **StandardScaler**.
   - Removal of highly correlated features if needed.
3. **Splitting the Dataset**
   - **80% Training**, **20% Testing**.

## 📊 Model Training
- Implemented **Multiple Linear Regression** using `sklearn.linear_model.LinearRegression`.
- Computed **model coefficients** and **intercept**.

## 🎯 Model Evaluation
- **Root Mean Squared Error (RMSE)**:
  - Train RMSE: *[Replace with computed value]*
  - Test RMSE: *[Replace with computed value]*
- **R² Score**:
  - Train R² Score: *[Replace with computed value]*
  - Test R² Score: *[Replace with computed value]*

