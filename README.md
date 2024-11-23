# PRODIGY_TrackCode_Task_01  

This project involves building a **Linear Regression Model** to predict house prices based on their features, using the **Ames Housing Dataset**.

---

## 🛠️ Features  

- **Data Preprocessing:** Handles missing values and performs one-hot encoding for categorical variables.  
- **Feature Selection:** Uses relevant features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) to predict `SalePrice`.  
- **Model Training:** Implements a Linear Regression model after scaling features.  
- **Model Evaluation:** Evaluates performance using metrics like MSE, RMSE, MAE, and R² score.  
- **Visualization:** Includes scatter plots, heatmaps, and actual vs. predicted price comparison.

---

## 📊 Dataset  

**Dataset Name:** Ames Housing Dataset (`train.csv`)  
**Source:** [Kaggle - Ames Housing Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  

The dataset contains the following relevant columns:  
- **GrLivArea:** Above-grade living area in square feet.  
- **BedroomAbvGr:** Number of bedrooms above ground.  
- **FullBath:** Number of full bathrooms.  
- **SalePrice:** Target variable representing the house price.  

---

## 🔍 Steps in the Project  

1. **Data Loading:**  
   - Load the dataset and handle missing values.  

2. **Feature Engineering:**  
   - Fill missing values using median and mode.  
   - Apply one-hot encoding to categorical variables.  
   - Log-transform the target variable `SalePrice` for better model fitting.  

3. **Data Preprocessing:**  
   - Scale features using `StandardScaler`.  
   - Split data into training and test sets.  

4. **Model Training:**  
   - Train a Linear Regression model on the scaled training data.  

5. **Evaluation:**  
   - Calculate evaluation metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score.  

6. **Visualization:**  
   - Scatter plot for Actual vs. Predicted SalePrice.  
   - Correlation heatmap to analyze relationships between features.  

---

## 📈 Results  

- **Model Performance:**  
  - **Mean Squared Error (MSE):** 0.0723  
  - **Root Mean Squared Error (RMSE):** 0.2689  
  - **Mean Absolute Error (MAE):** 0.1979  
  - **R² Score:** 0.6125  

---

## 🔧 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/niamat-sirrou/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
