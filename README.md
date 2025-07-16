# Brand & Customer Analytics Report 📊

This Power BI project delivers an interactive dashboard that analyzes **brand-based sales, customer behavior, and category performance**.  
Users can select any brand using the `Brand` slicer to dynamically filter all visuals.

---

## 🚀 Project Highlights

### 📌 General Features
- Power BI Desktop (.pbix) file
- Power Query transformations (data type casting, age calculation, age group segmentation, weekday vs weekend labeling, hour extraction)
- DAX measures for key metrics:
  - Total Sales Quantity
  - Total Revenue
  - Total Unique Customers
  - Revenue per Customer
  - Average Order Value
  - Male/Female Customer Count (fully responsive to slicers)
  - Category-based revenue for young customers in Istanbul (TreeMap)

---

### 📊 Dashboard Pages

#### 1️⃣ Summary Page
- **Sales by Weekday vs Weekend (Clustered Column Chart)**
- **Total Sales by Region (Bar Chart)**
- **Hourly Revenue (Column Chart)**
- Key metrics cards (total sales, revenue, customer count, orders, etc.)

#### 2️⃣ Customer Perspective
- Cards for unique customers, female customers, male customers
- Top 10 customers in Istanbul (TopN table)
- Sales by Age Group chart (Young, Adult, Middle Age, Senior)

#### 3️⃣ Category Perspective
- TreeMap showing total revenue by product category for young customers in Istanbul.

---

### 🔥 Technical Highlights
✅ Power Query M code for:
- Calculating age from `BirthDate`
- Creating age segments
- Extracting hour from datetime
- Weekday vs weekend labeling

✅ DAX for:
- Advanced measures using DISTINCTCOUNT, CALCULATE, TREATAS to ensure slicer sensitivity
- Dynamic filtering of all metrics based on selected `Brand`

✅ Page navigation with buttons:
- Seamless transitions from the entry page to Customer and Category perspectives.

---

## 🗂️ Tools & Technologies
- Power BI Desktop
- DAX
- Power Query (M language)

---

## 🚀 How to Use
1. Download the `.pbix` file from this repository.
2. Open it with Power BI Desktop.
3. Use the `Brand` slicer at the top right to select any brand and watch how all visuals update accordingly.

---

## 📝 Notes
This project was developed as part of a data visualization exercise.  
All data is sample data. 

---

