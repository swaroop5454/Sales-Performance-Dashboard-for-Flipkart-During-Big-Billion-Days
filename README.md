# Sales-Performance-Dashboard-for-Flipkart-During-Big-Billion-Days

![bandicam2024-11-2323-25-38-757-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/245364c3-a07e-4806-b5ad-092c3bee49d4)

![bandicam2024-11-2323-22-50-408-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/747c9a3c-2d3a-4771-a292-4c6bfb62edd3)


# Let’s Go To Build A Flipkart Dashboard

### Presented by:
**Swaroop H**  
Innovative | Enthusiast Educator | Data Scientist  
Bengaluru | +91-8951444547 | [swaroop5454@gmail.com](mailto:swaroop5454@gmail.com)  
[LinkedIn](https://linkedin.com/in/swaroop5454/) | [GitHub](https://github.com/swaroop5454)

---

## Dataset Overview

The dataset contains three tables: `Sales_Data`, `Product_Data`, and `Customer_Data`. These tables are merged using a left join to create the final dataset with **100,000 rows and 17 columns**.

### Column Details:
- **Order Details**: Order Id, Order Date, Customer Id, Product Id.
- **Transaction Metrics**: Qty, Unit Price, Total Sales.
- **Customer Details**: Customer Name, Email, Phone, Join Date, Age, Gender.
- **Product Details**: Product Name, Category, Stock Qty.
- **Region**: Indicates the geographical region of sales.

---

### Key Observations:
- **Data Completeness**: No missing values were detected.
- **Data Types**: Most fields are correctly typed (e.g., numeric for sales metrics, categorical for region and gender).

---

## Initial Insights from the Data

### Key Metrics:
- **Total Sales Revenue**: ₹261,163,351.53
- **Average Order Value**: ₹2,611.63
- **Top-Selling Products**:
  1. Product x1: ₹2,127,781.39
  2. Carry: ₹1,988,400.11
  3. Room: ₹1,918,601.46
  4. Citizen: ₹1,820,793.20
  5. May: ₹1,759,954.24

---

### Regional Sales Performance:
- East: ₹52,753,536.56
- Central: ₹52,179,864.12
- South: ₹52,211,376.66
- North: ₹52,168,524.47
- West: ₹51,850,049.72

---

### Customer Demographics:
- **Gender Split**:
  - Male: 51.14%
  - Female: 48.86%

---

### Data Quality:
- No duplicates were found in the dataset.
- Dates have been converted for analysis, and the data appears clean and ready for dashboarding.

---

# Dashboard Overview

The dashboard is interactive and segmented into multiple sections to analyze sales trends, customer behavior, and product performance.

### Components:

1. **Header Section**:
   - **Title**: "Flipkart Sales During Big Billion Days" emphasizes the focus of the analysis.
   - **Region Filters**: Allows users to view data filtered by regions: Central, East, North, South, and West.

2. **KPIs**:
   - **Top-Selling Product**: Displays "Ability" as the most popular product.
   - **Sum of Orders**: 225K orders during the Big Billion Days.
   - **Total Sales**: ₹56.01M total revenue.

3. **Total Sales by Region**:
   - A bar chart compares sales across regions (West, East, North, Central, and South) overlaid with stock quantities.

4. **Sales Trend Over Time**:
   - A line graph visualizes daily sales during the campaign, highlighting fluctuations and peak sales days.

5. **Category Stock Quantity**:
   - A pie chart showing the proportion of stock by category:
     - Categories include Books, Clothing, Electronics, Home, and Sports.
     - Distribution is fairly balanced (~18-22%).

6. **Sales Growth Percentage**:
   - A bar chart tracks daily sales growth percentage, showcasing a consistent upward trend with occasional dips.

7. **Sum of Sales by Category and Gender**:
   - A stacked bar chart showing sales split by categories (Books, Clothing, Electronics, etc.) and segmented by gender (Male and Female).

8. **Sales Based on Products**:
   - A bar chart lists top-performing products based on sales revenue (e.g., "So," "Room," "Carry," "Billion").

9. **Interactive Filters**:
   - **Order Date**: Select specific date ranges for focused analysis.
   - **Customer Age**: A slider to filter data based on customer age groups.

---

### Key Observations:

1. **Regional Sales Performance**:
   - All regions exhibit similar sales, with no significant outliers.
   - Stocks were well-distributed across regions.

2. **Category-wise Stock Distribution**:
   - Electronics and Clothing had slightly higher stocks compared to other categories.

3. **Customer Demographics**:
   - Both genders contributed nearly equally to total sales.
   - Significant sales were driven by customers within the filtered age range.

4. **Sales Trends**:
   - Peak sales observed on certain days, likely coinciding with promotional offers.
   - Consistent growth across the campaign period.

---

## Report Deliverables:

### A. Dashboard Features:
- Interactive slicers for time, region, and demographic analysis.
- Easy-to-read charts and visualizations for stakeholders.

### B. Insights:
- **Total Orders and Revenue**: ₹56.01M revenue from 225K orders.
- **Top-Selling Product**: "Ability."
- **Key Growth Drivers**: Sales growth was steady with peak days driving higher revenue.

### C. Business Recommendations:
1. **Expand Inventory**:
   - Focus on top-performing categories like Electronics and Clothing.

2. **Promotional Strategies**:
   - Schedule targeted promotions during peak days to maximize revenue.

3. **Customer Segmentation**:
   - Leverage insights from the age and gender distribution to personalize campaigns.

