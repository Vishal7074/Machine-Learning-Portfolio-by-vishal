## Mini-Batch Gradient Descent for Linear Regression

This notebook demonstrates **Mini-Batch Gradient Descent** by implementing
a custom regressor from scratch and applying it to a real-world dataset.

The main focus of this notebook is to understand:
- how mini-batch gradient descent works internally
- how it differs from batch and stochastic gradient descent
- how model parameters are updated using batches

---

## 📌 Dataset Used
- **Diabetes Dataset** from `sklearn.datasets`
- Loaded using:
  ```python
  load_diabetes(return_X_y=True)
