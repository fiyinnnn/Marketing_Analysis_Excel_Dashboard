# 📈 **Marketing Analysis Dashboard in Excel**

## **Final Dashboard**
<img width="1341" height="662" alt="Dashboard" src="https://github.com/user-attachments/assets/da384165-e07c-4ce2-9653-3e57e8a58e84" />
<img width="1345" height="661" alt="MORE" src="https://github.com/user-attachments/assets/24dc421c-ee77-4d21-afad-7a6c7d2801c9" />

## **Raw Dataset Structure**

-<img width="1314" height="636" alt="RAW_DATASET" src="https://github.com/user-attachments/assets/dcf48476-1df4-4a4f-9c1b-9a51574852b9" />

## **Pivot Table Example**
<img width="198" height="188" alt="Raw_Pivot_Table" src="https://github.com/user-attachments/assets/f696a39e-649c-4d10-b47a-6c32f5abf864" />

# 📁 **1. PROJECT SETUP**

## **Step 1: Prepare Your Workbook**

1. Open **Excel → Blank Workbook**
2. Rename your sheets as follows:

```
Marketing_Raw_Data  
Age_Distribution  
Gender_Breakdown  
Income_vs_Spending  
Spending_Segments  
Category_Popularity  
Income_vs_Last_Purchase  
Purchase_Frequency  
Top_Customers  
KPIs  
DASHBOARD
```

## **Step 2: Import the Dataset**

1. Go to **Data → Get Data**
2. Load your dataset into **Marketing_Raw_Data**
3. Confirm the following column headers exist:

* Customer ID
* Age
* Gender
* Income
* Spending Score
* Purchase Frequency
* Category
* Last Purchase Amount


## **Step 3: Convert Data to an Excel Table**

1. Select the dataset
2. Press **CTRL + T**
3. Name the table: **Marketing_Data**

# 📊 **2. ANALYSIS & PIVOT TABLE CREATION**

Each sheet contains one pivot table and chart answering a specific business question.

## **A. Age Distribution**

**Goal:** Identify which age groups dominate the customer base
**Sheet:** `Age_Distribution`

### Steps

1. Select the Age column directly from the Excel table
2. Insert → Statistic Chart → Histogram
3. Adjust bin ranges to reflect age groups (e.g. 18–28, 28–38, 38–48, etc.)
4. Format the chart to display count of customers per age group

<img width="1261" height="587" alt="Age_Distribution" src="https://github.com/user-attachments/assets/8df26d98-40f0-411a-a6c6-5f48182b2a95" />

## **B. Gender Breakdown**

**Goal:** Understand customer gender distribution
**Sheet:** `Gender_Breakdown`

### Steps

1. Insert Pivot Table
2. Rows: **Gender**
3. Values: **Count of Customer ID**
4. Insert **Doughnut Chart**

<img width="1198" height="638" alt="Gender_Breakdown" src="https://github.com/user-attachments/assets/39948bb8-51f1-4949-8b43-39d168f7f8a5" />


## **C. Income vs Spending Score**

**Goal:** Analyze relationship between income and spending behavior
**Sheet:** `Income_vs_Spending`

### Steps

1. Select Income & Spending Score columns
2. Insert → **Scatter Plot**
3. Add a **Trendline**

<img width="1293" height="615" alt="Income_vs_Spending Score" src="https://github.com/user-attachments/assets/34724d17-af77-4c15-b4f4-c4959bea9544" />


## **D. Spending Score Segmentation**

**Goal:** Classify customers into spending groups
**Sheet:** `Spending_Segments`

### Segments

* Low (<34)
* Medium (34–66)
* High (>66)

### Steps

1. Create a helper column for segments
2. Insert Pivot Table
3. Rows: **Spending Segment**
4. Values: **Count of Customer ID**
5. Insert **Bar Chart**

<img width="1306" height="644" alt="Spending_Score_Segments" src="https://github.com/user-attachments/assets/478c475f-d681-4197-961e-1aa8f4fdf3ff" />

## **E. Category Popularity**

**Goal:** Identify most popular product categories
**Sheet:** `Category_Popularity`

### Steps

1. Insert Pivot Table
2. Rows: **Category**
3. Values: **Count of Customer ID**
4. Sort descending
5. Insert **Horizontal Bar Chart**

<img width="1272" height="600" alt="Categories" src="https://github.com/user-attachments/assets/32a2a7dd-b243-4af4-a774-53fc5ef87512" />

## **F. Income vs Last Purchase Amount**

**Goal:** Compare income with last purchase value
**Sheet:** `Income_vs_Last_Purchase`

### Steps

1. Select Income & Last Purchase Amount
2. Insert **Scatter Plot**
3. Add Trendline

<img width="1184" height="599" alt="Income_vs_Last Purchase Amount" src="https://github.com/user-attachments/assets/031599aa-8253-49cf-888c-bcd7eaa6e618" />

## **G. Purchase Frequency Distribution**

**Goal:** Analyze customer purchase frequency
**Sheet:** `Purchase_Frequency`

### Steps

1. Group Purchase Frequency into ranges
2. Insert Pivot Table
3. Values: **Count of Customer ID**
4. Insert **Column Chart**

<img width="1252" height="616" alt="Purchase Frequency Distribution" src="https://github.com/user-attachments/assets/97324800-8c08-4753-bba4-434e6ce438f6" />

## **H. Top Customers by Purchase Amount**

**Goal:** Identify customers with the highest purchases
**Sheet:** `Top_Customers`

### Steps

1. Insert Pivot Table
2. Rows: **Customer ID**
3. Values: **Max of Last Purchase Amount**
4. Sort descending
5. Insert **Horizontal Bar Chart**

<img width="1250" height="610" alt="Top_10_Customers" src="https://github.com/user-attachments/assets/e10b6d78-d285-44e4-9734-8fc21322c45d" />

## **I. KPI Metrics**

**Sheet:** `KPIs`

### Metrics Created

* Total Customers
* Average Income
* Average Spending Score
* Average Purchase Frequency
* Most Popular Category

### How to Build KPI Cards

1. Insert → Shape → Rectangle
2. Link values using formulas (COUNT, AVERAGE, MAX)
3. Apply consistent formatting

<img width="497" height="298" alt="KPI&#39;s" src="https://github.com/user-attachments/assets/4cec0ea3-e511-4149-9d85-7e6451e930cf" />


# 📌 **3. BUILDING THE FINAL DASHBOARD**

All visuals are assembled in the `DASHBOARD` sheet.


## **Step 1: Layout Design**

* Insert background shapes
* Use neutral business colors (cream, black, gold accents)
* Add dashboard title:

```
MARKETING ANALYSIS DASHBOARD
```

## **Step 2: Add Charts**

Copy charts from analysis sheets and arrange logically:

* KPIs at the top
* Demographics (Age, Gender)
* Behavior (Spending, Frequency)
* Revenue insights (Categories, Top Customers)


## **Step 3: Final Polish**

* Remove gridlines
* Align all visuals
* Maintain consistent fonts and sizes
* Add guiding arrows or labels where necessary

<img width="1341" height="662" alt="Dashboard" src="https://github.com/user-attachments/assets/d74802dd-1bc4-43c3-b769-8531b59a3087" />

# 🎉 **DONE!**

You have successfully built a complete **Marketing Analysis Dashboard in Excel** from scratch.


## 📬 **Author**

**Abolarin Isaac**
Aspiring Data & Financial Analyst

---

⭐ Feel free to explore, fork, or build upon this project.
