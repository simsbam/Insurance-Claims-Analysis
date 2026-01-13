# Insurance-Claims-Analysis
This project analyzes insurance policyholder data to understand how **demographics, vehicle characteristics, income levels, and coverage zones** affect **claim frequency and claim amounts**.

The analysis was completed **entirely in Microsoft Excel** using **Power Query**, **Power Pivot (DAX measures)**, **PivotTables**, and **charts**.

---

## Dataset Columns
- Client ID  
- Birthdate  
- age  
- marital_status  
- gender  
- parent  
- kids_driving (numeric)  
- education  
- house_hold income (numeric)  
- car_use  
- car_make  
- car_model  
- car_color  
- car_year  
- coverage_zone  
- claim_frequency (numeric)  
- claim_amount (numeric)  

---

## Tools Used
- Microsoft Excel  
- Power Query  
- Power Pivot (DAX)  
- PivotTables & PivotCharts  

---

## Data Preparation
- Cleaned and standardized all columns using **Power Query**
- Fixed data types and removed inconsistencies
- Created derived fields:
  - **Age Group** (18–24, 25–34, 35–44, 45–54, 55–64, 65+)
  - **Car Age Band** (0–2, 3–5, 6–10, 10+)
  - **Income Band** (Low → High)
  
---

## Analysis Performed
- Analyzed claim frequency across **age groups, gender, and marital status**
- Evaluated the impact of **education level** on average claim amount
- Compared claim behavior across **coverage zones** (Rural, Urban, Highly Urban)
- Examined the relationship between **household income** and claim frequency and severity
- Compared **private vs commercial** vehicle use
- Assessed the effect of **kids driving** on claim patterns
- Identified car brands with the **highest and lowest average claim amounts**
- Analyzed claim patterns based on **car age** and **car color**
- Explored how **income level interacts with coverage zone** to influence claims

---

## Key Insights
- Commercial vehicles record higher claim frequency and higher average claim amounts
- Urban and highly urban coverage zones experience more frequent claims than rural areas
- Lower-income households tend to file claims more frequently
- Higher-income households generally have higher average claim amounts
- Older vehicles show higher claim frequency, while newer vehicles show higher claim severity
- Households with kids who drive present increased insurance risk
- Differences in claims by car color are minimal and largely driven by sample size

---

## Output
- Cleaned and transformed dataset using Power Query
- Data model with DAX measures for claim frequency and severity
- PivotTables answering all research questions
- Interactive Excel dashboard with slicers and KPI cards
- Business-focused insights suitable for underwriting and pricing decisions

---

## Author
**Simisola**  
Actuarial Science Graduate | Insurance & Data Analytics  
Excel • SQL • Power BI • Python

