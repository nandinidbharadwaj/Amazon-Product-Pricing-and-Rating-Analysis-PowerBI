# Amazon Product-Pricing and Rating Analysis-PowerBI
This project analyzes Amazon product pricing, discounts, and customer ratings using Power BI. The objective is to uncover insights related to revenue distribution, discount strategies, product performance, and rating trends across categories.

The dashboard provides an interactive view of product-level and category-level performance to support data-driven business decisions.

### **🎯 Business Objectives**

- Analyze total revenue across product categories

- Evaluate average discount trends

- Examine product rating distribution

- Understand the relationship between pricing and customer ratings

- Identify top-performing products

### **📂 Dataset Description**

The dataset contains Amazon product details including:

- Product ID

- Product Name

- Category

- Actual Price

- Discounted Price

- Discount Percentage

- Rating

- Rating Count

### **Data cleaning steps included:**

- Removing currency symbols (₹)

- Converting price columns to numeric format

- Removing unnecessary columns

- Creating calculated fields for analysis

### **🧮 Key Calculations (DAX)**

**- Total Revenue**

  SUM(discounted_price)

**- Average Rating**

  AVERAGE(rating)

**- Total Products**

  DISTINCTCOUNT(product_id)

**- Average Discount**

  AVERAGE(discount_percentage)

**- Price Difference (Calculated Column)**

  actual_price - discounted_price

### **📊 Dashboard Features**
**🔹 KPI Summary**

- Total Revenue: ₹4.58M

- Total Products: 1350

- Average Rating: 4.10

- Average Discount: 48%

**🔹 Category Analysis**

- Revenue by Category

- Average Discount by Category

**🔹 Product Insights**

- Top Rated Products

- Product Rating Distribution

- Price vs Discount Relationship (Scatter Analysis)

**🔹 Interactive Filters**

- Discount Percentage Range

- Category Selection

- Rating Filters

### **📈 Key Insights**

- Majority of products fall within the 4.0–4.5 rating range.

- Electronics category contributes the highest revenue.

- High discounts do not always guarantee higher ratings.

- Moderate pricing with balanced discounts tends to perform well.

### **🛠 Tools Used**

- Power BI

- Power Query (Data Cleaning)

- DAX (Data Analysis Expressions)

### **📸 Dashboard Preview**

<img width="1350" height="755" alt="image" src="https://github.com/user-attachments/assets/8b94bf72-c770-40e3-916d-078887274abb" />

### **🚀 How to Use**

- Download the .pbix file

- Open in Power BI Desktop

- Use slicers to explore category and discount trends

- Interact with visuals to analyze performance

### **👩‍💻 Author**

Nandini D Bharadwaj

Aspiring Data Analyst | Business Analyst

MBA in Business Analytics
