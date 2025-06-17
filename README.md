# 🏡 Boston Housing Price Prediction

This project compares **Linear Regression** and **Polynomial Regression (degree=2)** to predict housing prices based on selected features from the Boston Housing dataset.

---

## 📁 Project Structure

```
housing_regression/
├── HousingData.csv
├── housing_regression.ipynb
├── Linear_model.pkl
├── polynomial.pkl
├── README.md
└── images/
```

---

## 📊 Visualizations

### 🔹 Pairplot

![Pairplot](images/pairplot.png)

### 🔹 Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

### 🔹 RM vs MEDV

![RM vs MEDV](images/rm_vs_medv.png)

### 🔹 LSTAT vs MEDV

![LSTAT vs MEDV](images/lstat_vs_medv.png)

---

## 📈 Model Comparison

### 🔸 Linear Regression

- **MSE**: ...
- **MAE**: ...
- **R² Score**: ...

![Linear](images/actual_vs_predicted_linear.png)
![Residuals Linear](images/residuals_linear.png)

### 🔸 Polynomial Regression (degree=2)

- **MSE**: ...
- **MAE**: ...
- **R² Score**: ...

![Poly](images/actual_vs_predicted_poly.png)
![Residuals Poly](images/residuals_poly.png)

---

## 🧠 Insights

- Polynomial regression captured some non-linear relationships better than linear.
- Overfitting is possible if degree is too high.
- Visualizations and metrics helped compare both models effectively.

---

## 💾 Models Saved

- `Linear_model.pkl`
- `polynomial.pkl`

You can load them using `joblib` to make predictions on new data.

---

## 🏁 Example Prediction

```python
new_house = [[6.5, 12.0, 18.0, 3.5, 300]]
model.predict(new_house)
```

---

## 👩‍💻 Created by

**Rowayda Alaa**
