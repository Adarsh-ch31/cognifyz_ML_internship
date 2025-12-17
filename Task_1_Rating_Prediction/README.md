# Restaurant Rating Prediction

## Objective
Predict the aggregate rating of restaurants using machine learning regression techniques.

## Dataset
The dataset contains information about restaurants including location, pricing, services, and customer engagement.

## Approach
- Removed data leakage features (rating text and color)
- Handled missing values
- Encoded categorical variables
- Trained a Linear Regression model
- Evaluated using MSE and R²

## Results
- Mean Squared Error: ~1.32
- R² Score: ~0.42

## Key Insights
- Online delivery and price range positively influence ratings
- Popularity (votes) has a small positive impact
- Coefficients of categorical variables were interpreted cautiously

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab
