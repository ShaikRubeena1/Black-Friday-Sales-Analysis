# Black Friday Sales Prediction and Customer Purchase Analysis

**Project Overview**

This project focuses on analyzing customer purchasing behavior during Black Friday sales and building machine learning models to predict purchase amounts.
The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

The goal is to identify key factors influencing customer spending and develop predictive models that can estimate purchase amounts accurately.

**Dataset Information**

The dataset contains customer demographic information, product details, and purchase records collected during Black Friday sales.

**Features**
- User_ID
- Product_ID
- Gender
- Age
- Occupation
- City_Category
- Stay_In_Current_City_Years
- Marital_Status
- Product_Category_1
- Product_Category_2
- Product_Category_3
- Purchase (Target Variable)
  
**Project Workflow**

1. Data Preprocessing
- Handled missing values
- Removed unnecessary columns
- Encoded categorical variables
- Prepared data for machine learning models

2. Exploratory Data Analysis (EDA)
- Gender-wise purchase analysis
- Age group analysis
- City category analysis
- Marital status analysis
- Product category analysis
- Purchase distribution analysis
  
3. Feature Engineering
- Label Encoding
- Data Transformation
- Feature Selection
- 
4. Model Building

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
  
5. Model Evaluation

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
  
**Model Performance**
- Model	R²   Score
- Gradient Boosting Regressor	0.639
- Random Forest Regressor	0.590
- Decision Tree Regressor	0.376
- Linear Regression	0.160
  
**Best Performing Model**

Gradient Boosting Regressor

R² Score: 0.639
Demonstrated the highest predictive performance among all tested models.

**Key Business Insights**

- Customer demographics significantly influence purchasing behavior.
- Certain age groups contribute more to total sales.
- Product categories show varying purchase trends.
- City categories impact overall spending patterns.
- Machine learning models can effectively predict customer purchase amounts.
  
**Technologies Used**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

  
**Project Structure**

Black-Friday-Sales-Prediction-and-Analysis/
│
├── BlackFriday_Analysis.ipynb
├── README.md
├── BlackFriday.csv
└── images/


**Future Improvements**

- Hyperparameter tuning
- Advanced feature engineering
- XGBoost implementation
- Model deployment using Flask or Streamlit
- Interactive dashboard creation

**Author**
Shaik Rubeena
Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

**Connect With Me**
Feel free to connect and provide feedback on this project.
