# 📈 Linear Regression From Scratch (NumPy Only)

A complete implementation of **Linear Regression from scratch using only NumPy**, without using any machine learning libraries such as Scikit-learn.

This project was built to deeply understand how machine learning models actually work internally, including:
- feature scaling
- gradient descent
- cost minimization
- parameter optimization
- model evaluation

---

# 🚀 Project Goal

Predict student performance scores using:
- weekly self-study hours
- attendance percentage
- class participation

The model predicts:
- `total_score`

using a fully manual implementation of Linear Regression.

---

# 🔥 What Makes This Project Different

Everything in this project was implemented manually from scratch:

✅ No Scikit-learn regression model  
✅ No prebuilt training functions  
✅ No automatic optimizers  
✅ No prebuilt evaluation pipeline  

Only:
- NumPy
- mathematical equations
- manual gradient descent

---

# 🧠 Implemented From Scratch

## ✔ Feature Scaling
Implemented standardization manually using:

\[
X_{scaled} = \frac{X - \mu}{\sigma}
\]

---

## ✔ Prediction Function
Implemented the hypothesis function manually:

\[
\hat{y} = Xw + b
\]

---

## ✔ Cost Function (MSE)
Implemented Mean Squared Error manually:

\[
MSE = \frac{1}{m} \sum (\hat{y} - y)^2
\]

---

## ✔ Gradient Computation
Manually derived and implemented:
- weight gradients
- bias gradient

using vectorized NumPy operations.

---

## ✔ Gradient Descent
Implemented parameter optimization manually:

\[
w := w - \alpha dw
\]

\[
b := b - \alpha db
\]

---

## ✔ Model Evaluation
Implemented evaluation metrics manually:
- Mean Squared Error (MSE)
- R² Score

---

# 📊 Dataset

Student Performance Dataset containing features such as:
- study hours
- attendance
- participation
- total score

Dataset used for educational machine learning purposes.

---

# 📈 Final Results

| Metric | Result |
|---|---|
| R² Score | 0.92+ |
| RMSE | ~5 |
| MSE | ~27 |

The model successfully learned the relationship between student behavior and performance using only manually implemented linear regression.

---

# 🛠 Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab

---

# 📚 Concepts Learned

This project demonstrates understanding of:
- Linear Regression
- Gradient Descent
- Feature Scaling
- Optimization
- Underfitting vs Overfitting
- Train/Test Splitting
- Validation Concepts
- Model Evaluation

---

# 📷 Example Visualization

- Prediction vs Actual plots
- Loss curve visualization
- Residual analysis

---

# 🎯 Future Improvements

Planned upgrades:
- Mini-batch Gradient Descent
- Cross Validation
- Polynomial Regression
- Regularization
- Full vectorized optimization
- Better evaluation dashboard

---

# 💡 Key Takeaway

The purpose of this project was not just to use machine learning, but to understand:
> how machine learning models actually learn internally.

This project focuses on fundamentals, mathematics, and implementation details rather than relying on high-level ML libraries.
