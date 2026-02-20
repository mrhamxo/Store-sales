# Store Ecommerce Sales

## Problem Statement

This dashboard provides insights into the sales performance of an e-commerce store. It helps in understanding the distribution of profits, quantities sold, and customer purchasing behaviors across different categories, sub-categories, and payment modes. By analyzing these metrics, the store can identify trends, optimize inventory, and improve sales strategies.

### Steps followed 

- Step 1 : Load data into Power BI Desktop from the relevant data sources.
- Step 2 : Open Power Query Editor and in the View tab under the Data Preview section, check "Column distribution", "Column quality", and "Column profile" options.
- Step 3 : Ensure column profiling based on the entire dataset.
- Step 4 : Check for errors and empty values in all columns and handle them appropriately.
- Step 5 : Select a theme under the View tab in the Report view.
- Step 6 : Add various visuals to the report to represent key metrics.

### Key Metrics 

- **Sum of Amount**: 438K
- **Sum of Profit**: 37K
- **Sum of Quantity**: 5615
- **Sum of ADV (Average Daily Value)**: 121K

### Visualizations 

1. **Profit by Sub-Category**: 
   - Maharashtra
   - Madhya Pradesh
   - Uttar Pradesh
   - Delhi

2. **Quantity by Category**:
   - Furniture: 17%
   - Electronics: 21%
   - Clothing: 63%

3. **Amount by Customer**:
   - Hamid
   - Madhav
   - Mohan Mohini
   - Shiba

4. **Quantity by Payment Mode**:
   - EMI: 12%
   - Credit Card: 16%
   - Debit Card: 13%
   - UPI: 21%
   - COD: 44%

5. **Profit-Lost by Month**: 
   - Monthly profit and loss trend showcasing highest profit in December and other monthly fluctuations.

6. **Profit by Sub-Category**: 
   - Printers
   - Bookcases
   - Saree
   - Accessories
   - Tables

### Steps to Build the Dashboard

- Load the dataset into Power BI Desktop.
- Clean the data in Power Query Editor by checking column distribution, quality, and profile.
- Create necessary calculated columns and measures using DAX.
- Design the report view by adding visuals such as bar charts, pie charts, and card visuals.
- Add slicers for filtering data by quarter and sales regions.
- Publish the report to Power BI Service for sharing and collaboration.

# Insights

Following inferences can be drawn from the dashboard:

### 1. Profit Distribution
- Maharashtra and Madhya Pradesh contribute significantly to the overall profit.

### 2. Quantity Distribution
- Clothing is the dominant category with 63% of total quantity sold.

### 3. Customer Purchase Amount
- Customers named Hamid, Madhav, Mohan Mohini, and Shiba are the top purchasers.

### 4. Payment Mode Preference
- Cash on Delivery (COD) is the most preferred payment mode, accounting for 44% of transactions.

### 5. Monthly Profit and Loss
- December shows the highest profit, while other months exhibit varying levels of profit and loss.

### 6. Sub-Category Profit
- Printers generate the highest profit among sub-categories.

# Snapshot of Dashboard (Power BI Service)

![store sales dashboard](https://github.com/mrhamxo/Store-sales/assets/58738020/74953fe9-8c09-4f81-a9f8-69bc8b574fa9)

By analyzing this dashboard, the e-commerce store can make data-driven decisions to enhance profitability, optimize inventory, and improve overall sales performance.
