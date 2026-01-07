## Gradient Descent & Linear Regression (From Scratch + sklearn)

This notebook focuses on **understanding Linear Regression deeply** by combining:
- a standard sklearn implementation
- a **custom Gradient Descent implementation from scratch**
- and a comparison with `SGDRegressor`

The objective is to understand **how gradient descent actually works behind the scenes**.

---

## 📌 Dataset Used
- **Diabetes Dataset** from `sklearn.datasets`
- Features and target are loaded using:
  ```python
  load_diabetes(return_X_y=True)
