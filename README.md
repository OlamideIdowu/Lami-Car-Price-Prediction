# Car Price Prediction

This project focuses on predicting vehicle prices using regression analysis. The dataset includes various features such as company name, model name, model year, location, engine type, color, assembly, body type, transmission type, registration status, mileage, engine capacity, and price.

## Project Steps
1. **Data Loading**: Load the dataset and perform initial inspection.
2. **Data Cleaning**: Remove unnecessary columns and handle missing values.
3. **Feature Encoding**: Encode categorical variables using Label Encoding.
4. **Feature Scaling**: Scale numerical features for better performance.
5. **Regression Analysis**: Perform Ridge and Lasso regression with hyperparameter tuning using RandomizedSearchCV.
6. **Model Evaluation**: Evaluate and compare the performance of the regression models.

   ## Requirements
The project requires the following libraries:
- pandas==1.4.5
- numpy==1.21.0
- scikit-learn==0.24.2
