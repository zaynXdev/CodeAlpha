
# 🌸 Iris Flower Classification

This project is a simple Machine Learning solution to classify iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on their sepal and petal measurements.

---

## 📚 Project Description

The Iris dataset is a famous dataset often used in beginner machine learning projects.  
In this project, we:

- Load and explore the dataset
- Visualize relationships between features
- Train a classification model (Random Forest Classifier)
- Evaluate model performance
- Try another model (Linear Regression) for comparison
- Plot feature importances
- Save the trained model for future use

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
├── data/
│   └── Iris.csv
├── models/
│   ├── iris_random_forest_model.pkl
│   └── label_encoder.pkl
├── notebook/
│   └── iris_classification.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   cd iris-flower-classification
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   Open `iris_classification.ipynb` in Jupyter Notebook or VS Code and run all cells.

4. Predict on new data:

   After saving the model, you can load it and make new predictions easily.

---

## 📊 Results

- **Random Forest Classifier Accuracy**: ~96%-100% (depending on random split)
- **Linear Regression Accuracy**: Lower (since it's not ideal for classification)

Random Forest gave the best performance for this task.

---

## 📦 Model Saving

The trained model and label encoder are saved as `.pkl` files using `joblib`, so they can be easily loaded later for predictions without retraining.

---

## 🔥 Future Work

- Try more classification algorithms (SVM, KNN, Decision Tree)
- Hyperparameter tuning
- Build a simple web app to classify flowers

---

## ⭐ Acknowledgements

- Dataset from [Scikit-learn datasets](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Inspired by classical ML learning projects

---

# 📝 License

This project is open source and free to use under the [MIT License](LICENSE).
