
# 📊 E-Commerce Sales Analysis

This project provides an in-depth analysis of an e-commerce store's sales and profit data using **Python** and **Plotly** for visualization. It focuses on identifying trends, patterns, and key insights related to **monthly sales**, **product categories**, **sub-categories**, **profitability**, and **customer segments**.

---

## ✅ **Project Objectives**

The analysis answers the following business questions:

1. **Monthly Sales** – Calculate total monthly sales and determine the months with the **highest** and **lowest sales**.
2. **Sales by Category** – Identify which product category has the **highest** and **lowest sales**.
3. **Sales by Sub-Category** – Perform a detailed sales analysis based on product sub-categories.
4. **Monthly Profit** – Determine the month with the **highest profit**.
5. **Profit by Category and Sub-Category** – Analyze profit distribution across product categories and sub-categories.
6. **Sales & Profit by Customer Segment** – Compare sales and profit across different customer segments.
7. **Sales-to-Profit Ratio** – Calculate and analyze the ratio for each customer segment.

---

## 🛠 **Technologies Used**

* **Python**

  * `pandas` – Data manipulation & analysis
  * `plotly.express` & `plotly.graph_objects` – Interactive visualizations
* **Dataset**: Sample Superstore dataset (`Sample - Superstore.csv`)

---

## 📂 **Key Steps in Analysis**

1. **Data Preprocessing**

   * Loaded dataset using `pandas`
   * Converted `Order Date` & `Ship Date` to datetime format
   * Created new columns: `Order Month`, `Order Year`, `Order Day of Week`

2. **Analysis & Visualization**

   * Monthly sales & profit trends (Line charts)
   * Sales & profit distribution by category and sub-category (Pie & Bar charts)
   * Customer segment analysis (Grouped bar charts)
   * Sales-to-Profit ratio computation

---

## 📈 **Insights & Findings**

### **1. Monthly Sales Trend**

* The highest sales were recorded in **November**.
* The lowest sales occurred in **February**.
* Sales show a peak towards the end of the year, likely due to **holiday season demand**.

### **2. Sales by Category**

* **Technology** category generated the highest sales (**36.4%** of total sales).
* **Office Supplies** had the lowest share among major categories (**31.3%**).

### **3. Sales by Sub-Category**

* **Phones** and **Chairs** are the top-performing sub-categories.
* **Fasteners** and **Labels** have the lowest sales contribution.

### **4. Monthly Profit Analysis**

* The month with the **highest profit** is **November**.
* The lowest profit months coincide with the low-sales months, such as **February**.

### **5. Profit by Category**

* **Technology** contributed the maximum profit (**50.8%** of total profit).
* **Furniture** had the lowest profit share (**6.44%**), possibly due to **higher discounts or costs**.

### **6. Profit by Sub-Category**

* **Copiers** and **Phones** sub-categories were highly profitable.
* Some sub-categories like **Tables** showed **negative profit**, indicating potential **loss-making products**.

### **7. Customer Segment Analysis**

* **Consumer segment** generated the highest sales and profit.
* **Corporate** and **Home Office** segments contribute less compared to Consumer.

### **8. Sales-to-Profit Ratio**

* **Consumer** segment: **8.66**
* **Corporate** segment: **7.68**
* **Home Office** segment: **7.13**

**Interpretation**: Consumer segment provides better profitability per sales dollar compared to others.

---

## 📊 **Visualizations**

* **Monthly Sales & Profit Trends**
* **Category & Sub-Category Analysis (Sales & Profit)**
* **Customer Segment Analysis**
* **Sales-to-Profit Ratio Table**

---

## 🚀 **How to Run**

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/ecommerce-sales-analysis.git
   ```
2. Navigate to the project folder:

   ```bash
   cd ecommerce-sales-analysis
   ```
3. Install dependencies:

   ```bash
   pip install pandas plotly
   ```
4. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

---

## 📌 **Future Enhancements**

* Add **forecasting models** for sales and profit (using ARIMA or Prophet).
* Build an **interactive dashboard** using **Dash or Streamlit**.
* Include **regional-level analysis** for better business strategy insights.


