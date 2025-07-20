# Telco Customer Churn Prediction  

This project analyzes customer data from a fictional Telco company and builds a predictive model to identify customers likely to churn.  

## Project Overview  

**Dataset**  
- ~7,000 customers with demographic, service, billing, and churn details  

**EDA (Exploratory Data Analysis)**  
- Explored churn distribution  
- Analyzed key drivers such as contract type, billing, and service usage  
- Visualized categorical and numerical feature relationships with churn  

**Modeling**  
- Most data was categorical, so OneHotEncoder was used for convering categorical values into numeric values
- RandomForestClassifier was selected for its robustness  
- RandomizedSearchCV was applied for hyperparameter tuning  
- The final model was saved using Pickle for future use  

## Tech Stack  

- **Python**  
- **Pandas, NumPy** for data manipulation  
- **Matplotlib, Seaborn** for visualization  
- **Scikit-learn** for encoding, model building, and hyperparameter tuning  
- **Pickle** for saving the model

