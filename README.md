# 📊 Customer Lifetime Value (CLV) Prediction

This project predicts the **Customer Lifetime Value (CLV)** using transaction data from an online retail dataset. The goal is to identify high-value customers based on **purchase behavior**, **frequency**, and **monetary contribution**.

---

## 📁 Project Structure

celebal_project_lipsa/
├── Celebal_project_code.ipynb      # Jupyter Notebook with full code
├── dataset.csv             # Cleaned dataset (50,000 rows)
├── README.md                          # Project documentation


---

## 📌 Objectives

- Preprocess and clean transactional data  
- Generate **RFM features** (Recency, Frequency, Monetary)  
- Apply **BG/NBD** and **Gamma-Gamma** models to predict:
  - Future purchases  
  - Expected monetary value  
  - 6-month CLV  
- Segment customers using **K-Means clustering**  
- Visualize customer distribution and gain insights for targeting

---

## 🛠️ Tools & Libraries Used

- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- `lifetimes` (for probabilistic CLV modeling)
- `scikit-learn` (for clustering algorithms)
- `XGBoost` *(optional for classification tasks)*

---

## 📈 Results

- Customers are segmented by predicted CLV
- Visualizations reveal differences in value-based customer groups
- Business can focus on top segments for **retention** and **upselling**

---

## 🔍 Dataset Information

- Original Dataset: [Online Retail II – Kaggle](https://www.kaggle.com/datasets)
- This repository uses a compressed subset: `Dataset.csv`

---

## 🚀 How to Run

1. **Clone** this repository or download it as a ZIP
2. Navigate to `notebooks/customer_lifetime_value.ipynb`
3. **Run all cells** sequentially in Jupyter Notebook to reproduce analysis
4. Explore clustering outputs and CLV predictions

---

## 👩‍💻 Author
## LIPSA PATTANAIK*  
## Final-year B.Tech, ITER SOA University  
## Project created during **Celebal Technologies Summer Internship 2025**

---
