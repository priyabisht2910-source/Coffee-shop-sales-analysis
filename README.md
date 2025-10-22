# ☕ Coffee Sales Analysis — Data Cleaning & EDA with Python

This project explores and analyzes a **coffee shop sales dataset** to uncover patterns in revenue, product performance, and customer behavior.  
The analysis demonstrates a complete data analytics workflow — from cleaning raw data to generating insights through visualization.

---

## 📊 Project Overview

This notebook performs an end-to-end analysis of a **Coffee Sales Dataset** from Kaggle.  
It includes:
- Data cleaning and preprocessing  
- Handling of missing values and outliers  
- Exploratory Data Analysis (EDA)  
- Visualizations of key business metrics  

---

## 📁 Dataset Information

**Source:** [Kaggle — Coffee Sales Dataset](https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset)  
The dataset contains detailed records of coffee shop transactions including:
- Product names and categories  
- Quantities sold  
- Sales revenue (`money`)  
- Date and time of each transaction  

> ⚠️ Please download the dataset manually from Kaggle and place `coffee_sales.csv` in the same folder as the notebook.

---

## 🧹 Data Cleaning Steps

- Removed duplicate entries  
- Converted `Date` and `Time` columns to proper datetime formats  
- Detected and capped outliers in the `money` column using the **IQR method**  
- Encoded categorical features for numeric analysis  

---

## 📈 Exploratory Data Analysis (EDA)

The notebook explores:
- Sales distribution and revenue trends  
- Product-wise and category-wise performance  
- Time-based sales patterns (daily, monthly trends)  
- Revenue contribution by different items  

Interactive visualizations are created using **Plotly** alongside static charts with **Matplotlib** and **Seaborn**.

---

## 🧰 Technologies Used

| Library | Purpose |
|----------|----------|
| `pandas` | Data manipulation and cleaning |
| `numpy` | Numerical operations |
| `matplotlib` | Basic visualizations |
| `seaborn` | Statistical plots and styling |
| `plotly` | Interactive charts |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/priyabisht2910-source/coffee_sales_analysis.git
   cd coffee_sales_analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

3. Download the dataset from Kaggle and place it in this folder:
   ```
   coffee_sales.csv
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook coffee_sales.ipynb
   ```

5. Run all cells to reproduce the analysis.

---

## 📌 Future Improvements

- Perform predictive modeling (e.g., forecast sales using time-series models)  
- Add advanced dashboards with Plotly Dash or Streamlit  
- Integrate profitability and customer segmentation analysis  

---

## 👩‍💻 Author

**Priya Bisht**  
📍 Data Analyst | Python Enthusiast  
🔗 [GitHub Profile](https://github.com/priyabisht2910-source)  
💼 [LinkedIn](https://www.linkedin.com/in/priya-bisht-6a11aa328)

---

*Happy Analyzing!* ☕📈
