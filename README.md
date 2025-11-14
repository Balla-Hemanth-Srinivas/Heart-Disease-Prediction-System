# 🫀 Heart Disease Prediction System
Logistic regression is a statistical and machine learning algorithm used for binary classification problems, where the output variable has two possible outcomes (e.g., presence or absence of disease). It models the probability of a specific class as a function of one or more input features. Logistic regression is widely used in healthcare, finance, and social sciences due to its simplicity, interpretability, and effectiveness.
This system uses data analysis, preprocessing, and classification algorithms inside a Jupyter Notebook.

---

## 📂 Project Structure


**Heart Disease Prediction.ipynb** - Main notebook containing the full workflow (EDA → preprocessing → model training → evaluation → prediction). 
**heart.csv** - Dataset used for training and testing. 

---

## 🚀 Features

- Load and explore the heart-disease dataset  
- Perform Exploratory Data Analysis (EDA)  
- Data preprocessing (scaling, cleaning, splitting)  
- Train machine learning model used:
  - Logistic Regression  
- Make predictions using trained Logistic Regression model  

---

## 🧠 Technologies Used

- Python 3.7+
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

Install required dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ How to Run

1. Clone the repository:
```
git clone https://github.com/Balla-Hemanth-Srinivas/Heart-Disease-Prediction-System.git
```

2. Navigate to the folder:
```
cd Heart-Disease-Prediction-System
```

3. Open the notebook:
```
jupyter notebook "Heart Disease Prediction.ipynb"
```

4. Run all cells sequentially to train models and view results.

---

## 📈 Example Outputs

Typical results you may see:
- Logistic Regression: **80%–85%**

Exact values depend on preprocessing, training.

---

## 🩺 Prediction Example

Example usage inside the notebook:

```python
model.predict([[63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]])
```

Output:
```
[1]  # Indicates heart disease likelihood
[0]  # Indicates no heart disease
```

---

## ⚠️ Notes

- Dataset must be present in the same directory.  
- Accuracy values depend on train/test split.  
- Notebook must be run in order to avoid errors.  

---

## 📄 License

This project is open-source and free to modify for educational use.
