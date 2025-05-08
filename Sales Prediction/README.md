
# 🛍️ Sales Prediction Using Machine Learning

This project is a simple machine learning pipeline that predicts product sales based on advertising budget across different channels (TV, Radio, Newspaper). It uses **Linear Regression** and **Random Forest Regressor** to train models and allows user interaction for predictions.

---

## 📁 Dataset

- **File:** `Advertising.csv`
- **Columns:**
  - `TV`: Advertising budget spent on TV
  - `Radio`: Advertising budget spent on Radio
  - `Newspaper`: Advertising budget spent on Newspaper
  - `Sales`: Resulting product sales

---

## ⚙️ How It Works

1. The dataset is split into training and testing sets.
2. Two models are trained:
   - Linear Regression
   - Random Forest Regressor
3. Both models are evaluated using Mean Squared Error (MSE).
4. Models are saved for later use.
5. A user interface (CLI-based) allows users to input advertising budgets and select a model for predicting sales.

---

## 🧪 Requirements

```bash
pip install pandas scikit-learn joblib
```

---

## 🚀 Run the Project

### 1. Train Models

```bash
python train_models.py
```

### 2. Predict Sales with User Input

```bash
python predict_sales.py
```

---

## 📊 Example Output

```
Linear Regression MSE: 2.10
Random Forest MSE: 1.45

Choose a model to use:
1. Linear Regression
2. Random Forest Regressor
Enter 1 or 2: 2

Using Random Forest Model
Enter TV advertising budget ($): 150
Enter Radio advertising budget ($): 25
Enter Newspaper advertising budget ($): 20

Predicted Sales: 14.65 units
```

---

## 📌 Notes

- The model assumes a linear or ensemble relationship between ad spend and sales.
- This is a simplified project for educational purposes.

---

## 📁 File Structure

```
├── Advertising.csv
├── train_models.py         # Trains both ML models
├── predict_sales.py        # User input & prediction interface
├── linear_model.pkl        # Saved linear regression model
├── rf_model.pkl            # Saved random forest model
└── README.md               # Project documentation
```

