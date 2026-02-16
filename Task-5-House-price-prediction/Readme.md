# House Price Prediction using Machine Learning

A complete machine learning project to predict house prices in Pakistan (or similar markets) based on property features such as area, number of bedrooms, bathrooms, location preferences, furnishing status, and more.

Built as part of an internship/task using the **zafarali27/house-price-prediction-dataset** from Kaggle.

## Project Overview

- **Goal**: Predict house sale prices (in PKR) using regression techniques
- **Dataset**: ~2000 rows from Kaggle – includes numerical and categorical features
- **Model Used**: Gradient Boosting Regressor (chosen as the best single model after experimentation)
- **Key Metrics**:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- **Techniques Demonstrated**:
  - Data preprocessing (categorical encoding, feature scaling, log transformation of target)
  - Feature importance analysis
  - Predicted vs Actual price visualization
  - Handling real-world data characteristics (categorical variables, skewed target)

## Dataset

- Source: [Kaggle – House Price Prediction Dataset](https://www.kaggle.com/datasets/zafarali27/house-price-prediction-dataset)
- Main features:
  - Area (square feet)
  - Bedrooms
  - Bathrooms
  - Stories
  - Parking
  - Mainroad (yes/no)
  - Guestroom (yes/no)
  - Basement (yes/no)
  - Hotwaterheating (yes/no)
  - Airconditioning (yes/no)
  - Prefarea (preferred location – yes/no)
  - Furnishingstatus (furnished / semi-furnished / unfurnished)
  - Location (Urban / Rural / Suburban or similar)
  - **Target**: Price (in PKR)

## Project Structure

## Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/house-price-prediction.git
cd house-price-prediction
# Linux / macOS
python -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

pandas
numpy
matplotlib
seaborn
scikit-learn
kagglehub
