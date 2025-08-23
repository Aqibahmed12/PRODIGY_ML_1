# 🏠 Task-01: House Price Prediction using Linear Regression

## 👨‍💻 Author
**Aqib Ahmed**

---

## 📌 Project Description
This project uses a **Linear Regression model** to predict the sale prices of houses based on three key features:

- **Square Footage** (`GrLivArea`)  
- **Number of Bedrooms** (`BedroomAbvGr`)  
- **Number of Bathrooms** (`FullBath`)  

The goal is to build a simple yet effective model that demonstrates how linear regression can be applied to real-world datasets.

---

## 📂 Dataset
- **Name:** House Prices – Advanced Regression Techniques  
- **Source:** [Kaggle Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  
- **Files Used:**  
  - `train.csv` → Training data  
  - `test.csv` → Testing data  
  - `data_description.txt` → Description of features  

---

## ⚙️ Steps Involved
1. Load dataset using Pandas.  
2. Select features: `GrLivArea`, `BedroomAbvGr`, `FullBath`.  
3. Handle missing values.  
4. Split dataset into training and testing sets.  
5. Train Linear Regression model.  
6. Evaluate model using **RMSE** and **R² Score**.  
7. Visualize **Actual vs Predicted Prices** and **Residuals**.  
8. Predict the price of a custom house.  

---

## 📊 Model Evaluation
- **Intercept:** 52,261.75  
- **Coefficients:**  
  - `GrLivArea`: +104.03  
  - `BedroomAbvGr`: -26,655.17  
  - `FullBath`: +30,014.32  
- **RMSE:** ~52,976  
- **R² Score:** 0.634 (explains ~63% of variation in prices)  

---

## 📈 Visualizations
### Actual vs Predicted Prices  
Shows how close predictions are to real house prices.  

### Residual Plot  
Shows errors (residuals) distributed around zero line.  

---

## 🚀 Tech Stack
- **Python**  
- **Pandas / NumPy** → Data handling  
- **Matplotlib / Seaborn** → Visualization  
- **Scikit-Learn** → Linear Regression  

---

## 🏆 Results
- The model demonstrates how simple linear regression can predict house prices.  
- With only **3 features**, the model achieves **63% accuracy (R² = 0.634)**.  
- Performance can be improved by adding more features like `OverallQual`, `YearBuilt`, `Neighborhood`.  

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/PRODIGY_ML_1.git
   cd PRODIGY_ML_1
  
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
  
5. Run the notebook:
   ```bash
   jupyter notebook Task-01_HousePricePrediction.ipynb


