# Cuisine Classification

## Objective
To classify restaurants based on their primary cuisine using machine learning techniques.

## Dataset
The dataset contains restaurant details such as location, pricing, services, and ratings.
Since cuisines are multi-label, only the primary cuisine was considered for classification.

## Approach
- Extracted primary cuisine from the cuisine column
- Removed rare cuisines to handle class imbalance
- Encoded categorical variables
- Trained a baseline Logistic Regression model
- Improved performance using a Random Forest classifier

## Results
- Logistic Regression accuracy: ~31%
- Random Forest accuracy: ~36%

The Random Forest model performed better for common cuisines such as North Indian,
Chinese, and Fast Food. Performance for rare cuisines was limited due to class imbalance.

## Challenges
- Large number of cuisine categories
- Class imbalance
- Multi-label nature of the original cuisine data

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab
