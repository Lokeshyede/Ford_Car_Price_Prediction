# 🚗 Ford Car Price Prediction

##  Overview
This project predicts the price of Ford cars based on features such as **model**, **year**, **mileage**, **fuel type**, **engine size**, and more.  
It includes **Exploratory Data Analysis (EDA)**, **data preprocessing**, **model training**, and **evaluation**.  

The final tuned model — **Random Forest Regressor** — achieves high accuracy and stable results across cross-validation folds.

---

## Results
| Model                     | R² Score | RMSE (£) | MAE (£) | MAPE (%) |
|---------------------------|----------|----------|---------|----------|
| Baseline: Linear Regression | 0.819    | 2,015.19 | 1,360.54| 13.33    |
| Random Forest (Tuned)       | 0.937    | 1,186.02 | 818.89  | 7.12     |

- **Cross-validation R²:** 0.935 ± 0.003  
- **Residual Mean:** -18.92 → close to zero (low bias)  
- Example prediction for a Ford Fiesta (2019, Manual, 15k miles, Petrol): **£14,623.92**


---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Joblib  

---

## 📂 Project Structure
Ford_Car_Price_Prediction/
│
├── Ford_Car_Price_Prediction.ipynb # Main notebook
├── ford.csv # Dataset
├── requirements.txt # Dependencies
└── Readme.md

## Future Improvements
Test Gradient Boosting models (XGBoost, LightGBM)

Apply log transformation to target variable for skew reduction

Add more domain-specific features (e.g., car age, mileage/year)

## Contact
Created by LOkesh yede
🔗 LinkedIn [www.linkedin.com/in/lokeshyede]
