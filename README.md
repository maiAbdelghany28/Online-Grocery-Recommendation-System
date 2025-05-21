################################################################
##           🛒 Online Grocery Recommendation System          ##
################################################################

## Author
Mai Waheed AbbdelGhany

---

## Project Overview

This project aims to build a **machine learning-based system** that predicts whether a grocery product will be reordered by a customer. The prediction can be used to enhance recommendation systems in online grocery platforms.

---

## 📊 Dataset Used

The dataset is based on an online grocery ordering platform and includes:

- `aisles.csv`
- `departments.csv`
- `products.csv`
- `orders.csv`
- `order_products__prior.csv`
- `order_products__train.csv`

---

## Exploratory Data Analysis (EDA)

- Analyzed missing values and duplicates
- Checked categorical vs. non-categorical columns
- Merged data from multiple sources
- Visualized:
  - Most ordered products
  - Reorders by department and aisle
  - Daily and hourly order patterns
  - Most popular products per day of week

---

## Features Engineered

- `user_total_orders`
- `user_total_products`
- `user_reorder_ratio`
- `product_total_orders`
- `product_reorder_ratio`
- `add_to_cart_order`
- `order_dow`
- `order_hour_of_day`
- `days_since_prior_order`

---

## Technologies & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Models Used

| Model                  | Accuracy | Precision | Recall | AUC-ROC |
|------------------------|----------|-----------|--------|---------|
| Logistic Regression    | ✓        | ✓         | ✓      | ✓       |
| Decision Tree (Best)   | ✓        | ✓         | ✓      | ✓       |
| K-Nearest Neighbors    | ✓        | ✓         | ✓      | ✓       |

Decision Tree performed the best in terms of overall accuracy and ROC-AUC.

---

## 📈 Visualizations

- Bar plots of top departments and aisles
- Reorder ratios by department
- Popular products and time-based order distribution
- ROC Curves for model comparison
- Accuracy comparison across models
- Actual vs. Predicted Reorder Counts

---

## How to Run

1. Ensure all CSV files are in the same directory as the notebook.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
