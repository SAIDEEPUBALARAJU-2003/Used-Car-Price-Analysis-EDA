#  Exploratory Data Analysis on Used Car Prices

##  Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on **used car sales data** collected from the **Cars24 website**. The objective is to understand how different factors such as **brand, car age, mileage, fuel type, ownership, and manufacturing year** influence the resale price of used cars.

The analysis aims to generate insights that can help **buyers make informed purchasing decisions** and **sellers set competitive yet profitable prices**.

---

##  Project Objectives
- Analyze historical used car price data
- Identify key factors affecting car resale value
- Understand price variation across brands and fuel types
- Study the impact of mileage, ownership, and car age on price
- Perform data-driven insights using visual analysis

---

##  Dataset Information
- **Source:** Cars24 website  
- **Initial Dataset Size:**  
  - Rows: 874  
  - Columns: 7  
- **Final Cleaned Dataset:**  
  - Rows: 640  
  - Columns: 8  

###  Features Used
- Brand  
- Model  
- Price  
- Kms Driven  
- Fuel Type  
- Owner Type  
- Manufacturing Year  
- Car Age (engineered feature)

---

##  Tools & Technologies
- **Python**
- **Requests & BeautifulSoup** (Web Scraping)
- **Pandas & NumPy** (Data Cleaning & Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Regular Expressions (Regex)**

---

##  Data Cleaning & Feature Engineering
- Removed special characters from mileage and owner type
- Extracted numeric values from price using regex
- Converted mileage values from “k” to numeric format
- Handled missing values using:
  - Mode imputation (Owner Type)
  - Mean imputation (Mileage)
- Created a new feature **Car_Age**
- Split brand and model into separate columns
- Corrected data types and reset index

---

##  Exploratory Data Analysis
The analysis includes:
- Price distribution across brands
- Top brands by market share
- Maximum and minimum car prices by brand
- Impact of fuel type on price and mileage
- Effect of manufacturing year on car price
- Correlation analysis between price, mileage, and car age
- Ownership impact on resale value
- Identification of dominant price ranges in the market

---

##  Key Insights
- Car price decreases significantly as **car age increases**
- **1st owner cars** have higher resale value
- Premium brands like **BMW, Mercedes, and Audi** retain value better
- Diesel cars generally have **higher mileage and price** than petrol cars
- Most used cars fall in the **₹2.5–6.5 lakh** price range
- Mileage negatively correlates with price
- Newer manufacturing years lead to higher resale prices

---


##  Conclusion
This project demonstrates the complete **EDA workflow**, from data collection and cleaning to analysis and visualization. It reflects real-world analytical thinking and shows how data-driven insights can support decision-making in the used car market.


---

##  Author
**Saideepu Balaraju**  

