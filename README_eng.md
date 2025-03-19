# Bitcoin Price Prediction with Machine Learning

## 📌 Project Description
This project aims to **predict Bitcoin prices** using **traditional Machine Learning algorithms**, based on historical data. A **reduced dataset** was used to improve performance and facilitate model training.

## 📌 Problem to Solve
Bitcoin prices are highly volatile and depend on multiple factors. The goal is to build a model that, based on features like **opening price, high/low price, and transaction volume**, can predict the **closing price** with reasonable accuracy.

## 📌 Dataset Used
- **Source:** The original dataset is from [Kaggle](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data).
- **Description:** It contains historical Bitcoin price data, including open, high, low, close prices, and transaction volume.
- **Reduced Version:** A random sample from the original dataset was selected to optimize training time.
- **Access:** You can download the original dataset from Kaggle.

## 📌 Solution Approach
1. **Exploratory Data Analysis (EDA):** Identifying correlations and cleaning data.
2. **Preprocessing:** Data normalization and train/test split.
3. **Models Used:**
   - **Linear Regression** as a baseline.
   - **Random Forest Regressor** for a more robust model.
4. **Model Evaluation:** Comparison of MAE, MSE, and R² metrics.
5. **Model Storage:** The best model is saved in `.joblib` format.

## 📌 Repository Structure
ML_Bitcoin/
│── src/
│   ├── data_sample/        # Sample dataset used in the project
│   ├── img/                # Images generated for analysis and presentation
│   ├── notebooks/          # Notebooks for experiments and analysis
│   ├── results_notebook/   # Final notebook with the complete model
│   ├── models/             # Saved models after training
│   ├── utils/              # Auxiliary functions used in the project
│── README.md               # Project description
│── requirements.txt        # Required libraries for running the project
│── presentation.pptx       # Presentation for the final submission
│── .gitignore              # Files and folders excluded from the repository

