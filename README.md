# Customer-Behaviour-Analysis-Project
---
## NovaCart India is a fictional company created for this portfolio project. 😄
---
## Table of contents
- [Project Overview](#Project-Overview)
  
- [Data Cleaning Process](#Data-Cleaning-Process)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [EDA-Results and findings](#EDA-Results-and-findings)
- [Business Recommendations](#Business-Recommendations)
- [Tools & techniques](#Tools-&-techniques)


### Project Overview
This project analyses customer shopping behaviour for **NovaCart India**, a growing e-commerce company operating across multiple cities in India. The analysis is based on **customer survey responses** covering demographics, spending habits, shopping frequency, product preferences, and purchasing decisions.

The project aims to identify valuable customer segments and provide actionable insights to improve marketing, customer engagement, and business decision-making.

### Data Source
The Raw data Source used for this Analysis is  "Customer_Behaviour_Survey_responses.csv" file containing information about the customers [Download here](https://www.kaggle.com/datasets/mitultandon/ecommerce-customer-behaviour-dataset)



### Data Cleaning Process

**Issues Identified**
- Long and inconsistent column names.
- Missing and inconsistent values in the State and City fields.
- Inconsistent naming of categorical responses.
- Misplaced or irrelevant response values.
- Duplicate survey records.
- Incorrect data types in some columns.

**Steps Taken**
- Renamed all columns with clear, concise, and analysis-friendly names.
- Used Power Query to standardise text values and ensure consistent naming across categorical fields.
- Corrected and completed missing State and City information where appropriate.
- Removed duplicate survey records to maintain data accuracy.
- Verified and assigned the correct data type to each column (Date, Text, Whole Number where applicable).
- Reviewed all categorical columns to ensure consistent response values and eliminate formatting inconsistencies.
- Validated the final dataset to ensure there were no missing values in key analytical fields before loading it into Power BI.



### Exploratory Data Analysis

**1. Understand Customer Purchasing Behaviour**

- How does shopping frequency vary across city tiers?
- How does customer spending vary with purchase decision time?
- Are customers primarily price-oriented or brand-oriented?

**2. Identify High-Value Customer Segments**

- Which occupation represents the highest-spending customer segment?
- Which customer segments demonstrate the strongest potential for loyalty programmes?
- Which states demonstrate the strongest customer spending potential?

**3. Analyse Demographic Influences**

- Which age group represents NovaCart's largest customer segment?
- How is the customer base distributed by marital status?
- How do product preferences differ by gender?

**4. Support Marketing & Business Strategy**

- Which city tier represents NovaCart's strongest market presence?
- Which states should receive greater market investment?
- What product and customer segments offer the strongest opportunities for targeted marketing and cross-selli

---
<img width="1327" height="749" alt="Customer behaviour Dashboard" src="https://github.com/user-attachments/assets/abd8a6c9-2a1d-48db-b01e-c298dd83062e" />

---



### EDA Results and findings

- Customers aged 20–30 form NovaCart's largest segment (113) and have the highest shopping frequency.
- Tier 2 cities have the largest customer population, mainly students who are more price-oriented.
- Clothing is the top category for both genders; males favour Electronics, while females favour Beauty Products.
- Regular-job customers are the largest medium-spending segment, with stronger brand preference and consistent shopping behaviour.
- Price-oriented customers (101) slightly outnumber brand-oriented customers (91).
- Maharashtra, Delhi, and Uttar Pradesh have the highest customer concentration.
- Female customers have a higher average shopping frequency (2.76) than males.
- Customers aged 30–40 and above 51 are more brand-oriented, while younger customers and students are more price-oriented.
- Longer purchase decision times are associated with stronger brand preference but not higher spending.
- Customer behaviour varies across age, occupation, gender, and purchase preference, highlighting opportunities for targeted segmentation.

### Business Recommendations

**1. Implement Segment-Based Marketing**
- Target price-sensitive students and younger customers with value offers, while positioning premium products and trusted brands for working professionals and older customers.
**2. Prioritise Tier 2 City Growth**
- Introduce student discounts, bundles, and free-shipping offers in Tier 2 cities to convert NovaCart's largest customer base into stronger repeat customers.
**3. Use Clothing to Drive Cross-Selling**
- Maintain Clothing as a core category while recommending Electronics to male shoppers and Beauty Products to female shoppers to increase basket value.
**4. Strengthen Loyalty Among High-Value Customers**
- Launch a tiered loyalty programme for frequent shoppers and working professionals using rewards, personalised offers, and early product access to improve retention.
**5. Personalise the Purchase Journey**
- Use customer preferences and decision behaviour to deliver targeted discounts, product recommendations, reviews, and reminders that improve conversion and engagement.


###  Tools & techniques

**Excel**
- Data inspection and initial analysis
- Data validation and quality checks
- Exploratory Data Analysis (EDA)
  
**Power Query**
  - Data cleaning and transformation
  - Handling missing/inconsistent values
  - Preparing the dataset for analysis
  
  **Power BI**
- DAX measures and calculated KPIs
- Interactive dashboard development
- Business insights and storytelling


👍👍👍


















