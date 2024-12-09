# Restaurant Rating Prediction

This project uses machine learning to predict restaurant ratings based on several features such as location, cuisine, price range, number of reviews, and opening year. It utilizes a Gradient Boosting Regressor model from `scikit-learn` to predict ratings and evaluate the model's performance.

## Project Overview

The goal of this project is to generate synthetic restaurant data and build a predictive model that estimates the rating of a restaurant. The generated dataset includes features such as:

- **Location**: The city where the restaurant is located (e.g., New York, San Francisco).
- **Cuisine**: The type of cuisine (e.g., Chinese, Italian, Japanese).
- **Number of Reviews**: The number of reviews the restaurant has received.
- **Price Range**: The general price range (e.g., Cheap, Moderate, Expensive).
- **Opening Year**: The year the restaurant was established.

The model uses these features to predict a restaurant's **rating**, which is a numerical score between 1 and 5.

## Dependencies

This project requires the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
