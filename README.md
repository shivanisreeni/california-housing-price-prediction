California Housing Price Prediction – Linear Regression

This project uses the California Housing dataset from kaggle to build a Linear Regression model that predicts housing prices based on various demographic and geographic features. It follows a complete machine learning workflow from preprocessing to model evaluation.

##Dataset
The dataset is loaded from `housing.csv` and includes features like:
- Median income
- Housing age
- Total rooms & bedrooms
- Population
- Proximity to ocean
- Longitude and Latitude
- Household
- Median house value
  
##Workflow
1. Imported and cleaned the dataset  
2. Handled missing values 
3. Applied Label Encoder to encode categorical variable  
4. Split the data into training and testing sets  
5. Trained a Linear Regression model  
6. Evaluated model using **R² Score** and **Mean Squared Error**

##Results
Evaluation metrics:  
R² Score:0.613706888649953  

##Tech Stack
- Python  
- NumPy, pandas  
- scikit-learn  
- seaborn, matplotlib  
- Google Colab



