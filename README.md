# 📊 Power BI Assignment 1 – Data Transformation & Data Modeling

## 📌 Project Overview

This project demonstrates the use of **Microsoft Power BI and Power Query Editor** for data preparation, transformation, aggregation, and data modeling using an **E-commerce Sales Dataset**.

The main objective of this project is to transform raw business data into a structured and analysis-ready data model that can be used for reporting and business insights.

This project focuses on practical **Data Analyst skills**, including:

- Data Import
- Data Cleaning
- Data Transformation
- Data Type Management
- Data Aggregation
- Data Modeling
- Table Relationships
- Summary Tables
- Business-oriented data preparation

---

## 🎯 Problem Statement

As a Data Analyst, the task is to prepare and model an E-commerce sales dataset containing multiple related datasets.

The raw data contains information related to:

- Orders
- Order details
- Products
- Sales targets

The objective is to clean and transform the raw datasets, create meaningful summary tables, establish relationships between related tables, and prepare the final Power BI model for business analysis and reporting.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI** | Data modeling and visualization |
| **Power Query Editor** | Data cleaning and transformation |
| **DAX** | Calculations and analytical logic |
| **Power BI Data Model** | Relationship management |
| **GitHub** | Project documentation and portfolio |

---

## 📂 Dataset / Data Model

The Power BI project contains the following major tables:

### 1. RAW_List of Orders

Contains the original order-level information.

**Purpose:**
- Store raw order information
- Provide the base data for transformation
- Support order-level analysis

---

### 2. RAW_Order Details

Contains detailed information associated with individual orders.

**Purpose:**
- Provide detailed order/product-level information
- Support product and category analysis
- Connect detailed transaction information with order data

---

### 3. RAW_Sales target

Contains sales target information.

**Purpose:**
- Store target/goal information
- Support comparison between actual sales and targets
- Enable performance analysis

---

### 4. Order_Data

This is the primary transformed/structured dataset created from the raw data.

**Purpose:**

- Cleaned and transformed order data
- Standardized fields
- Prepared data for analysis
- Used as a major analytical table in the Power BI model

---

### 5. Category_summary

An aggregated table created for category-level analysis.

**Purpose:**

- Summarize sales by category
- Compare category performance
- Support high-level business analysis

---

### 6. Monthly Summary

An aggregated table designed for monthly-level analysis.

**Purpose:**

- Analyze sales trends over time
- Compare monthly performance
- Identify high and low performing periods

---

### 7. SubCategory Summary

An aggregated table designed for sub-category analysis.

**Purpose:**

- Analyze product sub-category performance
- Compare sales across sub-categories
- Identify important product segments

---

## 🔄 Data Transformation Process

The project follows a typical Power BI data preparation workflow:

```text
Raw Data
   ↓
Data Import
   ↓
Power Query
   ↓
Data Cleaning
   ↓
Data Type Transformation
   ↓
Data Standardization
   ↓
Data Aggregation
   ↓
Summary Tables
   ↓
Data Modeling
   ↓
Power BI Analysis
```

---

## 🧹 Data Cleaning & Transformation

The Power Query transformation process focuses on preparing raw business data for analysis.

Key transformation activities include:

- Removing unnecessary data
- Checking duplicate records
- Handling missing values
- Correcting inconsistent values
- Standardizing data formats
- Changing columns to appropriate data types
- Preparing date-related fields
- Structuring order-level data
- Creating analysis-ready tables
- Aggregating data for summary analysis

The goal is to ensure that the final dataset is **consistent, accurate, and suitable for business reporting**.

---

## 🔗 Data Modeling

The project includes a Power BI data model containing raw, transformed, and aggregated tables.

### Model Structure

```text
RAW_List of Orders
        │
        ▼
    Order_Data
        │
   ┌────┼───────────────┐
   ▼    ▼               ▼
Category       Monthly Summary
Summary
   │
   ▼
SubCategory
Summary

RAW_Order Details
        │
        ▼
 Order-level / Product-level Analysis

RAW_Sales target
        │
        ▼
 Target Performance Analysis
```

The model is designed to organize the data into logical analytical structures and support efficient reporting.

---

## 📊 Summary Tables Created

### Category Analysis

The **Category_summary** table can be used to evaluate:

- Sales by category
- Category contribution
- Best-performing categories
- Low-performing categories

### Monthly Analysis

The **Monthly Summary** table can be used to identify:

- Monthly sales performance
- Sales trends
- High-performing months
- Low-performing months
- Changes in sales over time

### Sub-Category Analysis

The **SubCategory Summary** table supports:

- Sub-category sales comparison
- Product segment analysis
- Best-performing sub-categories
- Underperforming segments

---

## 📈 Business Questions This Model Can Answer

The prepared data model can be used to answer questions such as:

1. Which category generates the highest sales?
2. Which sub-category performs best?
3. Which month has the highest sales?
4. Which months show lower performance?
5. How are sales changing over time?
6. Which product segments contribute most to revenue?
7. How does actual sales performance compare with sales targets?
8. Which categories or sub-categories may require improvement?
9. What are the major sales trends in the business?
10. Where can management focus to improve sales performance?

---

## 💡 Data Analyst Skills Demonstrated

This project demonstrates practical skills in:

### Data Preparation
- Data import
- Data cleaning
- Data validation
- Data transformation
- Data type management

### Power Query
- Query transformation
- Column transformation
- Data standardization
- Aggregation

### Data Modeling
- Multiple-table modeling
- Relationship management
- Structured analytical tables
- Summary table creation

### Business Analysis
- Category analysis
- Sub-category analysis
- Monthly trend analysis
- Target vs actual analysis

### Power BI
- Power Query
- Data Model
- DAX
- Data visualization
- Business reporting

---

## 📁 Repository Structure

Recommended GitHub repository structure:

```text
PowerBI-Data-Transformation-Modeling/
│
├── README.md
│
├── Power BI/
│   └── Power BI Assignment 1.pbix
│
├── Dataset/
│   ├── List of Orders.xlsx
│   ├── Order Details.xlsx
│   └── Sales Target.xlsx
│
├── Screenshots/
│   ├── Data_Model.png
│   ├── Power_Query.png
│   └── Dashboard.png
│
└── Documentation/
    └── Project_Notes.pdf
```

> **Note:** Only upload the dataset files if you have permission to redistribute them.

---

## 🖼️ Recommended GitHub Screenshots

For a strong Data Analyst portfolio, add screenshots showing:

### 1. Power Query

Show:

- Raw data
- Applied transformations
- Cleaned columns
- Data types

### 2. Data Model

Show the relationships between:

- RAW_List of Orders
- RAW_Order Details
- RAW_Sales target
- Order_Data
- Category_summary
- Monthly Summary
- SubCategory Summary

### 3. Power BI Report

Show your final report/dashboard containing relevant:

- KPI cards
- Sales analysis
- Category comparison
- Sub-category analysis
- Monthly trend
- Target vs actual analysis

---

## 🚀 Project Workflow

### Step 1 – Import Data

Imported the available E-commerce datasets into Power BI.

### Step 2 – Explore Raw Data

Reviewed the structure, columns, data types, and quality of the imported datasets.

### Step 3 – Clean Data

Performed data cleaning and standardization using Power Query.

### Step 4 – Transform Data

Created structured and analysis-ready datasets from the raw data.

### Step 5 – Aggregate Data

Created summary tables for:

- Category
- Sub-category
- Month

### Step 6 – Build Data Model

Organized the transformed tables and established logical relationships between related datasets.

### Step 7 – Prepare for Analysis

Prepared the final model for Power BI reporting and business analysis.

---

## 📌 Key Learning Outcomes

Through this project, I developed practical knowledge of how a Data Analyst prepares raw business data before visualization.

The project helped me understand the importance of:

- Clean and consistent data
- Proper data types
- Data transformation
- Table relationships
- Aggregation
- Data modeling
- Business-focused analysis

A major learning from this project is that **good Power BI reports depend on a well-prepared data model**.

---

## 🔮 Future Improvements

The project can be further enhanced by adding:

- Interactive Power BI dashboard
- KPI cards
- Sales vs Target percentage
- Profit analysis
- Year-over-Year growth
- Monthly sales trend
- Category and sub-category slicers
- Drill-through pages
- Tooltips
- DAX measures
- Time-intelligence calculations
- Advanced business insights

---

## 👨‍💻 About Me

I am an **aspiring Data Analyst** developing practical skills in data cleaning, data transformation, data analysis, and business intelligence.

### Current Skills

- Microsoft Excel
- SQL
- Power BI
- Power Query
- DAX
- Python
- Data Cleaning
- Data Visualization
- Data Analysis

I am continuously building projects to strengthen my practical Data Analytics portfolio.

---

## ⭐ Project Objective

The ultimate goal of this project is to demonstrate the complete journey from:

**Raw Data → Clean Data → Transformed Data → Data Model → Business Analysis**

This project is part of my Data Analytics learning and portfolio development journey.
