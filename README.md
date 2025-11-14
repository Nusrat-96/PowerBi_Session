# 📘 **10-Day Power BI Training Plan (with Assignments)**

### *Includes hands-on tasks + daily assignments to gradually build a full Sales Analytics Dashboard.*

---

# **📅 Day 1 — Introduction to Power BI**

### Topics:

* Power BI Desktop overview
* Importing data (Excel/CSV)
* Understanding Data / Model / Report views

### **Assignment:**

1. Download any dataset (Bangladesh or the one I created).
2. Import the dataset into Power BI.
3. Identify:

   * Number of columns
   * Number of rows
   * Data types (numeric, text, date)

---

# **📅 Day 2 — Power Query & Data Cleaning**

### Topics:

* Removing nulls
* Fixing data types
* Splitting/merging columns
* Creating new columns in Power Query

### **Assignment:**

1. Remove all rows with missing Region or Quantity.
2. Create a new column:
   **TotalSales = Quantity × UnitPrice**
3. Clean product/category naming (trim spaces).

---

# **📅 Day 3 — Data Modeling**

### Topics:

* Star Schema
* Relationships (1-to-many, many-to-one)
* Keys (CustomerID, ProductID)

### **Assignment:**

1. Create relationships between:

   * Sales ↔ Customer
   * Sales ↔ Product
   * Sales ↔ Calendar
2. Mark the **Calendar table as Date table**.
3. Explain (written in textbox):
   “Why do we use a Calendar Table?”

---

# **📅 Day 4 — Basic Visuals**

### Topics:

* Bar chart
* Table
* KPI cards
* Stacked bar

### **Assignment:**

Build a simple report with these visuals:

* **Card:** Total Sales
* **Bar Chart:** Sales by Category
* **Table:** ProductName, Quantity, SalesAmount

---

# **📅 Day 5 — Map Visuals (Bangladesh-based)**

### Topics:

* Filled Map
* Bubble Map
* Lat/Long mapping
* District/Division mapping

### **Assignment:**

1. Create a **map visual**:

   * SalesAmount by Region (Bangladesh Regions)
2. If your dataset has lat/long:

   * Plot shops or branches on a map
3. Add a slicer for **District** or **Division**

---

# **📅 Day 6 — DAX Basics**

### Topics:

* Calculated columns vs Measures
* SUM, AVERAGE, DISTINCTCOUNT
* CALCULATE basics

### **Assignment:**

Create the following measures:

* Total Sales
* Total Quantity
* Average Sale per Order
* Total Orders (DISTINCTCOUNT(OrderID))

Add these measures inside a **KPI section**.

---

# **📅 Day 7 — Time Intelligence (DAX)**

### Topics:

* YTD Sales
* MTD Sales
* Previous Month Sales
* YoY Growth

### **Assignment:**

Create:

1. **Sales LY**
2. **YoY Growth %**
3. A **line chart**:

   * X-axis = Month
   * Y-axis = SalesAmount & Sales LY

---

# **📅 Day 8 — Professional Dashboard Design**

### Topics:

* Theme colors
* Consistent layout
* Buttons & navigation
* Tooltip pages

### **Assignment:**

Create a **Homepage** containing:

* Title: *Bangladesh Sales Dashboard*
* 3 Navigation Buttons:

  1. Sales Overview
  2. Product Insights
  3. Region/Map View

---

# **📅 Day 9 — Power BI Service**

### Topics:

* Publishing
* Workspaces
* Scheduled refresh
* Sharing reports

### **Assignment:**

1. Publish your PBIX file to PowerBI Service
2. Create a Workspace
3. Share the report (if possible)

---

# **📅 Day 10 - Project**

### **Final Assignment (Full Dashboard):**

Build a **3-page Power BI Report**:

### **Page 1 — Sales Overview**

* KPIs: Total Sales, Profit, YoY Growth
* Line Chart: Sales trend
* Donut: Sales by Category

### **Page 2 — Product Insights**

* Top 10 Products
* Profit by Category
* Table: Product Performance

### **Page 3 — Bangladesh Map View**

* Map: Sales by Region/District
* Bar chart: Sales by Division
* Slicer: Product Category

---


