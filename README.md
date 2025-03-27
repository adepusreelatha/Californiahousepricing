# Californiahousepricing

A machine learning project to predict median house values in California using the California Housing Prices dataset from Kaggle.

##  Project Structure

- **EDA**: Data cleaning, distribution plots, correlations, feature engineering.
- **Modeling**: Linear Regression, Random Forest, Hyperparameter Tuning with GridSearchCV.
- **Evaluation**: RMSE and R² used to compare models on training and validation sets.

##  Key Results

| Model               | RMSE        | R² Score |
|---------------------|-------------|----------|
| Linear Regression   | 67,640.40   | 0.6544   |
| Random Forest (base)| 47,916.61   | 0.8237   |
| Random Forest (tuned)| **47,787.14** | **0.8246** |

 Random Forest (tuned) achieved the best performance.

##  Tech Stack

- Python
- JupyterLab
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

## 📁 Dataset

- [California Housing Prices - Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
