## Simple Linear Regression on Placement Data (CGPA vs Package)

This notebook demonstrates **Simple Linear Regression** using a real-world
placement dataset to understand the relationship between **CGPA and placement package**.

The main objective of this notebook is to build **strong intuition** about:
- how linear regression works
- how data is prepared
- how a model is trained and evaluated step by step

---

## 📌 Dataset Used
- **placement.csv**
- Contains:
  - `cgpa` → input feature
  - `package` → target variable (in LPA)

The dataset is loaded using:
```python
pd.read_csv('placement.csv')
