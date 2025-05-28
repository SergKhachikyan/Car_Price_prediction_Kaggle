# 🚗 Car Price Prediction – Kaggle Project
This project focuses on predicting the price of used cars based on various features like brand, model, year, fuel type, transmission, and more. The dataset is sourced from Kaggle and includes a wide range of vehicles sold in India.
## 📌 Project Goal
The objective is to build a machine learning model that can accurately predict car prices using relevant features. This involves preprocessing, exploratory data analysis, model training, and evaluation. The target variable is `selling_price`.
## 🧠 Technologies Used
- Python 3.10+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn, xgboost
- Jupyter Notebook
## 📁 Project Structure
Car_Price_prediction_Kaggle/  
├── data/  
│ └── car_data.csv # Dataset  
├── notebooks/  
│ ├── 01_data_analysis.ipynb # Exploratory Data Analysis (EDA)  
│ ├── 02_preprocessing.ipynb # Data Preprocessing  
│ └── 03_modeling.ipynb # Model Training and Evaluation  
├── models/ # Saved models (if any)  
├── requirements.txt # Project dependencies  
└── README.md # Project description
## 🔍 Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Analyze data distribution and summary statistics  
   - Identify correlations and trends  
   - Visualize insights using plots and charts  
2. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical features  
   - Normalize numerical features  
   - Split data into training and testing sets  
3. **Modeling**  
   - Train models such as Linear Regression, Random Forest, XGBoost  
   - Use cross-validation and hyperparameter tuning  
   - Compare models using MAE, RMSE, and R² metrics  
4. **Evaluation**  
   - Evaluate model performance on test set  
   - Plot predictions vs actual values  
   - Analyze feature importance
## 📈 Results
- XGBoost performed best among all tested models  
- R² Score: 0.89 on test data  
- Most influential features: `year`, `present_price`, `kms_driven`, `fuel_type`, `owner`, `seller_type`
## 🚀 How to Run
1. Clone the repository:  
```bash
git clone https://github.com/SergKhachikyan/Car_Price_prediction_Kaggle.git
```
2.Change directory
```
cd Car_Price_prediction_Kaggle
```
3.Install dependencies:
```
pip install -r requirements.txt
```
4.Open Jupyter Notebook and run the notebooks in order:
Untitled.ipynb
