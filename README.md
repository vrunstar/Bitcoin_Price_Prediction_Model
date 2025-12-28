# Bitcoin Price Prediction Model

## Project Introduction

The Bitcoin Price Prediction project is designed to predict the future movement of Bitcoin prices using machine learning. By leveraging Python libraries such as NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, and XGBoost, this project builds a complete pipeline to analyze historical Bitcoin data and make predictions.

___

## Overview

This project focuses on predicting whether the Bitcoin price will increase or decrease on the next day based on historical price patterns. Such predictions are useful in financial analysis and trading strategies. The project applies machine learning classification techniques on time-series price data to model market behavior.

___

## Dataset Used

The project uses a historical Bitcoin price dataset containing features such as:
- Open price
- High price
- Low price
- Close price
- Date

Additional features are engineered from the raw data, such as price differences and time-based features, to improve model performance. The dataset is preprocessed using Pandas to prepare it for modeling.

___

## Tech Stack

- Python
- NumPy – numerical computations
- Pandas – data processing and manipulation
- Scikit-learn – machine learning algorithms and evaluation
- XGBoost – gradient boosting classification
- Matplotlib & Seaborn – data visualization

___

## Workflow

1.  Data Collection & Preprocessing: Load and clean historical Bitcoin price data.
2.  Feature Engineering: Extract date-based features and price difference features.
3.  Data Visualization: Analyze price trends and distributions using plots.
4.  Train-Validation Split: Split the dataset into training and validation sets.
5.  Model Building: Train multiple machine learning models including Logistic Regression, SVM, and XGBoost.
6.  Model Evaluation: Evaluate model performance using ROC-AUC score and compare results across models.

___

## How to Run the Project

1.  Clone the repository: `gh repo clone vrunstar/Bitcoin_Price_Prediction_Model`
2.  Install required libraries using `pip` (skip if using Google Colab).
3.  Open the notebook: `bitcoin.ipynb` using Jupyter Notebook or Google Colab.
4.  Run the notebook cells in order.

___

## Conclusion

This project demonstrates how machine learning can be applied to financial time-series data to predict Bitcoin price movement. By combining data preprocessing, feature engineering, visualization, and multiple classification models, the project provides a practical approach to market trend prediction.

___

## Acknowledgement

Thanks to the developers and maintainers of open-source Python libraries such as NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, and XGBoost, as well as the resources that inspired this project.

___

## License

This project is licensed under the MIT License.
