# 📘 Bitcoin Price Prediction Project

This project aims to predict the future closing price of Bitcoin using a Machine Learning model trained on historical OHLCV (Open, High, Low, Close, Volume) data.

## 📁 Project Structure

```
src/
├── data_sample/
│   └── btcusd_sample.csv          # Sample dataset used in the project
├── models/
│   └── bitcoin_price_model.pkl    # Trained model saved in pickle format
└── results_notebook/
    └── bitcoin_price_prediction.ipynb  # Main notebook with the full ML pipeline
```

## ▶️ How to Run the Notebook

1. Open the file `src/results_notebook/bitcoin_price_prediction.ipynb`.
2. Run all cells sequentially.
3. The notebook will:
   - Load and preprocess the sample dataset.
   - Train a Random Forest regression model.
   - Evaluate model performance on the test set.
   - Save the trained model to `src/models/bitcoin_price_model.pkl`.

## 💾 Model Output

The final model is saved as a `.pkl` file using `joblib` and can be loaded in any Python environment with:

```python
import joblib
model = joblib.load("src/models/bitcoin_price_model.pkl")
```

## 🧠 Requirements

- Python 3.8+
- pandas
- scikit-learn
- numpy
- joblib

You can install the dependencies with:

```bash
pip install -r requirements.txt
```
