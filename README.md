# 📘 **10-Day Power BI Training Plan (with Assignments)**


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

# **📅 Day 2 — Data Cleaning and Transformation**

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

*  Bar / Column Chart
*  Pie / Donut
*  Line / Area
*  Table / Matrix
*  KPI cards
*  MAP visualizations - Map (Sales by Region)
  *  Filled map
  *  Bubble map
  *  Using lat/long
*  Tooltip visuals

### **Assignment:**

Build a simple report with these visuals:

* **Card:** Total Sales
* **Bar Chart:** Sales by Category
* **Table:** ProductName, Quantity, SalesAmount
*  Create a **map visual**:
   * SalesAmount by Region (Bangladesh Regions)

---

# **📅 Day 5 — ⭐ Slicers & Explicit Filters**

### Topics:

* Slicer types: dropdown, list, between, date
* Hierarchy slicer
* Visual-level filters
* Page-level filters
* Report-level filters
* Advanced filter options (contains, starts with, OR)

**Assignment:**

1. Add slicers: Region, Category, Year
2. Add visual-level filter: Category = Electronics
3. Add page-level filter: Region = Dhaka
4. Add report-level filter: Remove blank values

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

# **📅 Day 7 — Measures**

### Teach ONLY DAX Measures:

* SUM, SUMX
* AVERAGE
* DISTINCTCOUNT
* CALCULATE basics
* Filter context vs row context (simple example)

**Assignment:**
Create measures:

* Total Sales
* Total Orders
* Total Quantity
* Average Order Value
* Profit %

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

## **📅 DAY 9 – Publishing + Sharing + Row-Level Security**

**Topics:**

* Publish to Power BI Service
* Workspace creation
* Sharing & Permissions
* RLS (Row-Level Security)
* Export to PDF & PPT

**Assignment:**

* Publish your report
* Create a role "Sales Executive"
* Restrict data only to their region

---

## **📅 DAY 10 – Automation**

**Topics:**

* Scheduled Refresh
* Dataflows
* Power Automate Integration

  * Send email when sales drop
  * Auto-refresh dataset
* Parameters & Templates
* Creating reusable Power BI project structures


