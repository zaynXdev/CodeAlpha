# 🌸 Iris Flower Classification with User Interaction

This project is a beginner-friendly machine learning application to classify iris flowers into one of three species — **Setosa**, **Versicolor**, or **Virginica** — based on their sepal and petal dimensions. It includes a user-friendly prediction system where you can choose between different models and input custom values!

---

## 📚 Project Description

The Iris dataset is a well-known dataset in the ML community, often used for classification problems.

In this project, we:

- Load and explore the Iris dataset
- Visualize feature distributions and relationships
- Train two models:
  - Random Forest Classifier
  - Linear Regression (used creatively for classification)
- Compare model performance
- Save the trained models and label encoder using `joblib`
- Allow user interaction via terminal input to predict flower species using either model

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📂 Project Structure

```
├── data/
│   └── Iris.csv
├── models/
│   ├── iris_random_forest_model.pkl
│   ├── iris_linear_regression_model.pkl
│   └── label_encoder.pkl
├── notebook/
│   └── Iris_Flower_Classification.ipynb
├── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   cd iris-flower-classification
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**:
   Use Jupyter Notebook or VS Code to open `Iris_Flower_Classification.ipynb`.

4. **Train the models**:
   Run the full notebook to train both models and save them using `joblib`.

5. **Predict with user input**:
   At the end of the notebook, enter flower features and choose a model:
   ```
   Choose the model for prediction:
   Enter 1 for Random Forest
   Enter 2 for Linear Regression
   ```

---

## 📊 Results

| Model               | Accuracy     |
|--------------------|--------------|
| Random Forest       | ~96-100%     |
| Linear Regression   | Lower (not ideal for classification) |

Random Forest is clearly the better fit for this classification task.

---

## 💾 Model Saving

The following models and tools are saved using `joblib` for later use:

- `iris_random_forest_model.pkl`
- `iris_linear_regression_model.pkl`
- `label_encoder.pkl`

---

## 💡 Future Improvements

- Add more models: KNN, SVM, Decision Tree
- Hyperparameter tuning with GridSearchCV
- Create a web app (e.g., with Streamlit or Flask)
- Export predictions as CSV


---

## 📌 Acknowledgements

- Dataset from [Scikit-learn](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Inspired by classic ML teaching examples

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).
