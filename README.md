# Startup Success Prediction

This project aims to predict the success of startups using machine learning techniques. The dataset contains information about startups, including their name, location, funding amount, and status (acquired or closed). The workflow includes data preprocessing, feature selection, model training, and evaluation.

## Project Structure

- **Data Preprocessing:**  
  - Import and inspect the dataset (`startup_data.csv`)
  - Handle missing values and data types
  - Encode categorical variables using one-hot encoding
  - Transform the target variable (`status`) into a binary column

- **Feature Selection:**  
  - Analyze feature correlations with the target variable
  - Use Random Forest Classifier to determine feature importance

- **Model Training & Evaluation:**  
  - Train and evaluate a Decision Tree Classifier with class weighting
  - Train and evaluate a K-Nearest Neighbors (KNN) Classifier with feature scaling
  - Visualize results using confusion matrices and feature importance plots

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn