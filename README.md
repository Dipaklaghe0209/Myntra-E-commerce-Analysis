# Myntra E-commerce Analysis

A comprehensive data analysis project of Myntra's e-commerce platform, providing actionable insights into products, customers, and order trends using Python, Pandas, and data visualization libraries.

---

## 📈 Project Overview

This project analyzes and visualizes Myntra's e-commerce data to uncover trends in product popularity, customer demographics, sales, and discount strategies. The goal is to help stakeholders understand business performance, customer behavior, and identify opportunities for growth.

---

## 📂 Dataset Structure

The analysis is based on three key tables extracted from `Myntra dataset.xlsx`:

- **dim_products**: Product catalog (Product ID, Category, Sub-category, Product Name, Brand Name, Size, Color, Ratings)
- **dim_customers**: Customer details (Customer ID, Age, City, State)
- **fact_orders**: Transactions (Order ID, Customer ID, Product ID, Date, Original Price, Discount%)

---

## 📊 Example Analyses

- **Product Trends**: Identify top-performing categories, brands, or products by sales and ratings.
- **Customer Segmentation**: Analyze customer distribution by age, location, and purchase volume.
- **Order & Pricing Insights**: Examine order volumes over time, average discount rates, and pricing patterns.
- **Data Quality Checks**: Validate data integrity by checking for duplicates, missing values, and dtype consistency.

---

## 🛠️ Technologies Used

- **Python** (Jupyter Notebook)
- **Pandas** for data manipulation
- **NumPy** for numerical analysis
- **Matplotlib** & **Seaborn** for visualization

---

## 🚀 How to Run the Analysis

1. **Clone the Repository**
   ```
   git clone https://github.com/Dipaklaghe0209/Myntra-E-commerce-Analysis.git
   cd Myntra-E-commerce-Analysis
   ```
2. **Install Dependencies**
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. **Open the Analysis Notebook**
   - Open `Myntra_Analysis (1).ipynb` in Jupyter Notebook or your preferred environment.
   - Ensure `Myntra dataset.xlsx` is in the working directory.

4. **Run the Notebook**
   - Execute cells sequentially to reproduce the analysis and visualizations.

---

## 📁 Files

```
├── Myntra dataset.xlsx              # Source data (products, customers, orders)
├── Myntra_Analysis (1).ipynb        # Main analysis notebook
└── README.md                        # Project documentation
```

---

## 📌 Key Columns Description

### dim_products

| Column         | Description              |
| -------------- | ----------------------- |
| Product ID     | Unique product code      |
| Category       | Major product category  |
| Sub-category   | Product sub-type        |
| Product Name   | Item name               |
| Brand Name     | Brand                   |
| Size           | Size (number or age)    |
| Color          | Product color           |
| Ratings        | Customer rating (1-5)   |

### dim_customers

| Column        | Description            |
| ------------- | --------------------- |
| Customer ID   | Unique customer code  |
| Customer Age  | Age of the customer   |
| City          | City                  |
| State         | State                 |

### fact_orders

| Column         | Description                       |
| -------------- | --------------------------------- |
| Order ID       | Unique order code                 |
| Customer ID    | Linked customer                   |
| Product ID     | Linked product                    |
| Date           | Order date                        |
| Original Price | Listed price before discount      |
| Discount%      | Fractional discount applied (e.g. 0.30 = 30%) |

---

## 🧑‍💻 Reproducibility & Data Quality

- Duplicates: Checked and confirmed (none found in any table).
- Data Types: Validated for all columns.
- Missing Values: Should be checked before further analysis.

---

## 📢 Insights & Outcomes

- **Business**: Spot high-growth categories, optimize discounting, and understand customer bases.
- **Product**: Prioritize inventory based on ratings and sales.
- **Marketing**: Tailor campaigns to top cities, states, or age groups.

---

## 🤝 Contributions

Contributions, suggestions, and pull requests are welcome!

---

## 📄 License

This project is released under the [MIT License](LICENSE).

---
