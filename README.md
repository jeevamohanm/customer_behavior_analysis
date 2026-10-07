# Customer Shopping Behavior Analysis

## Overview

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across different product categories.

The objective is to identify customer spending patterns, product preferences, customer segments, subscription behavior, and other business insights that can support data-driven decision-making.

The project follows an end-to-end data analytics workflow:

**Python → EDA & Data Cleaning → MySQL & SQL Analysis → Power BI Dashboard → Business Report → Presentation**

---

## Dataset

The dataset contains **3,900 rows and 18 columns**.

### Key Features

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Size, Color, Purchase Amount, Season
* **Shopping Behavior:** Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shopping Type

The dataset initially contained **37 missing values in the Review Rating column**.

---

## Tools & Technologies

| Tool                | Purpose                                             |
| ------------------- | --------------------------------------------------- |
| **Python**          | Data loading, EDA, cleaning and feature engineering |
| **Pandas**          | Data manipulation and analysis                      |
| **MySQL**           | Database storage and SQL analysis                   |
| **SQL**             | Business queries and customer analysis              |
| **Power BI**        | Interactive dashboard and visualization             |
| **Gamma**           | Project presentation                                |
| **Microsoft Excel** | Supporting data/reporting tasks                     |

---

## Project Workflow

### 1. Data Loading

The dataset was imported into Python using **Pandas**.

Initial inspection was performed using:

* `df.shape`
* `df.info()`
* `df.describe()`
* Missing-value checks
* Data type checks

This helped understand the structure, quality, and characteristics of the dataset.

### 2. Exploratory Data Analysis

EDA was performed to identify:

* Customer demographics
* Purchase patterns
* Product performance
* Spending behavior
* Subscription patterns
* Customer segments
* Missing and inconsistent data

### 3. Data Cleaning

The following cleaning steps were performed:

* Checked and handled missing values
* Imputed missing **Review Rating** values using the median rating for each product category
* Standardized column names using `snake_case`
* Created **Age Groups** through age binning
* Removed the `promo_code_used` column after verifying its relationship with `discount_applied`

### 4. MySQL Integration

The cleaned Pandas DataFrame was connected to **MySQL** and loaded into a database for SQL-based analysis.

### 5. SQL Analysis

Business questions were answered using SQL queries, including:

* Revenue by gender
* High-spending customers who used discounts
* Top 5 products by average rating
* Standard vs. Express shipping comparison
* Subscribers vs. non-subscribers
* Customer segmentation
* Top 3 products within each category
* Repeat buyers and subscription behavior
* Revenue contribution by age group

### 6. Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize important customer and business metrics.

The dashboard helps users understand:

* Sales and revenue trends
* Customer segments
* Product performance
* Subscription behavior
* Customer demographics
* Purchase patterns

### 7. Business Report

The analysis was documented in a business report containing the methodology, analysis, findings, and recommendations.

### 8. Presentation

A project presentation was created using **Gamma** to communicate the major findings and business recommendations in a concise format.

---

## Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior.

**Key areas covered:**

* Customer demographics
* Revenue and purchase analysis
* Product performance
* Subscription status
* Customer segmentation
* Age-group revenue
* Shopping behavior

> Add your Power BI dashboard
<img width="924" height="534" alt="dashboard" src="https://github.com/user-attachments/assets/a45f720f-ed4e-4533-8056-a18471fd0039" />


## Key Results & Insights

The analysis produced several business insights:

* Customers were segmented into **New, Returning, and Loyal** groups based on purchase history.
* Repeat buyers with **more than 5 previous purchases** showed a higher likelihood of subscribing.
* Product ratings and purchase frequency were analyzed to identify high-performing products.
* Revenue contribution was compared across different age groups.
* Spending behavior was compared between subscribers and non-subscribers.
* Standard and Express shipping purchase amounts were compared.
* High-spending customers using discounts were identified.

---

## Business Recommendations

Based on the analysis:

1. **Boost Subscriptions**
   Promote exclusive benefits and offers to increase subscription adoption.

2. **Customer Loyalty Programs**
   Reward repeat customers and encourage them to move into the Loyal segment.

3. **Product Positioning**
   Highlight top-rated and best-selling products in marketing campaigns.

4. **Targeted Marketing**
   Focus marketing efforts on high-revenue age groups and relevant customer segments.


## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* SQL
* MySQL
* Data Visualization
* Power BI
* Dashboard Development
* Customer Segmentation
* Business Analysis
* Business Reporting
* Data Storytelling
* Presentation Development

---

## Conclusion

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw customer transaction data and progressing through data cleaning, exploratory analysis, SQL-based business analysis, visualization, reporting, and presentation.

The project focuses not only on analyzing data but also on converting analytical findings into **actionable business recommendations**.

