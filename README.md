---

# 📊 Supervisor Sales Dashboard (2020–2022)

An interactive **Power BI Sales Dashboard** designed to analyze and monitor sales performance across supervisors, brands, categories, and states from **2020 to 2022**.

This dashboard provides a clear overview of key business metrics including **Total Sales, Total Cost, Profit Trends, Quantity Sold, and Brand Performance**, enabling better decision-making and performance tracking.

---

## 🚀 Project Overview

The **Supervisor Sales Dashboard** helps:

* Track overall sales performance
* Compare sales by product category
* Analyze brand contribution
* Monitor supervisor-wise performance
* Visualize state-wise sales distribution
* Evaluate cost vs revenue insights

It is designed for business managers, sales supervisors, and analysts to quickly identify trends and performance gaps.

---

## 📌 Key KPIs Displayed

The dashboard highlights major performance indicators:

* 💰 **Total Sales:** 99M
* 💸 **Total Cost:** 76M
* 📦 **Total Quantity Sold:** 13K
* 🔄 **Total Transactions:** 723M

These KPIs give a quick snapshot of business health.

---

## 📊 Dashboard Features & Visualizations

### 1️⃣ Quantity by Category

* Bar chart displaying product-wise quantity sold
* Categories include Monitor, Mouse, CPU, Graphic Card, Keyboard, SSD, HDD, RAM, etc.
* Helps identify high-demand products

---

### 2️⃣ Sales by States (Map Visualization)

* Interactive geographical map
* Displays sales distribution across different states
* Allows quick identification of top-performing regions

---

### 3️⃣ Total Sales by Brand (Pie Chart)

* Shows brand contribution to overall sales
* Includes brands like:

  * Intel
  * Samsung
  * Dell
  * Nvidia
  * Acer
  * Seagate
  * Western Digital
  * Gigabyte
  * Hynix

Useful for understanding brand dominance and market share.

---

### 4️⃣ Supervisor Filter Panel

* Dynamic supervisor selection
* Filter dashboard based on individual supervisor performance
* Enables performance comparison

Supervisors included:

* Aadil Khan
* Aarvi Gupta
* Advika Joshi
* Ajay Sharma
* Roshan Kumar
* Vijay Singh

---

## 🗂️ Data Model Structure

The report is built using a structured data model with proper relationships:

### 🔹 Tables Used:

1. **Sales_Data**

   * Order Date
   * Order Number
   * Customer Name
   * Brand
   * Category
   * Product
   * Quantity
   * Cost
   * Assigned Supervisor

2. **State_list**

   * State
   * State Code

3. **Supervisor**

   * Supervisor Name
   * Image URL

### 🔗 Relationships:

* `Sales_Data` connected with `State_list`
* `Sales_Data` connected with `Supervisor`
* One-to-many relationships used for proper filtering

This optimized model ensures accurate aggregation and smooth performance.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop**
* Data Modeling (Relationships)
* DAX Measures
* Interactive Visualizations
* Map Visualization
* KPI Cards
* Slicers & Filters

---

## 📈 Business Insights Generated

✔ Identify top-selling categories
✔ Monitor supervisor performance
✔ Compare brand contribution
✔ Analyze geographical sales trends
✔ Evaluate cost vs sales distribution

---

## 🎯 Purpose of This Project

This dashboard was built to demonstrate:

* Data modeling skills
* Business intelligence reporting
* Visual storytelling
* KPI tracking
* Real-world sales analytics

It can be used as a **portfolio project** for Data Analyst / Business Intelligence roles.

---

## 📷 Dashboard Preview

(<img width="1920" height="1020" alt="Screenshot 2026-03-04 134400" src="https://github.com/user-attachments/assets/617ec6d0-af2b-449e-89b2-5b4aea16bc9c" />
)

---

## 📥 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use supervisor filter to explore performance
4. Hover over charts for detailed insights
5. Interact with map for state-level sales analysis

---

## 🌟 Future Improvements

* Add Profit & Profit Margin analysis
* Include Time Intelligence (YoY Growth, MoM Growth)
* Add Drill-through pages
* Add Forecasting
* Implement Role-Level Security (RLS)

---

