# Car45 Used Car Market Analysis
 
An Excel analysis of **2,894 vehicle listings** from the Nigerian used-car market, covering pricing, brand popularity, location, vehicle condition, and specifications. The workbook ends in an interactive dashboard.
 
---
 
## 📌 Project Overview
 
This project analyzes listings scraped from Car45, a Nigerian car marketplace. Each listing includes the car's make, model, year, condition, mileage, engine size, transmission, color, body type, and location, plus its asking price. The goal is to understand what the market looks like and what drives price.
 
| Metric | Value |
|---|---|
| Total Listings | 2,894 |
| Average Price | ₦4,986,147 |
| Median Price | ₦3,203,125 |
| Average Mileage | 28,362 |
| Average Horsepower | 216.8 |
| Manufacture Years | 1988 to 2018+ |
| Makes / Models / States | 47 / 338 / 13 |
 
## 🎯 Business Problem
 
Buyers, sellers, and dealers in the used-car market need to know which cars are most available, where the market is concentrated, and what actually drives price. Without this, pricing is guesswork and inventory decisions are made blind.
 
## 📊 Project Objectives
 
- Identify the most listed makes, colors, and locations
- Understand how condition, age, and mileage affect price
- Compare the market across states and cities
- Profile typical vehicle specifications (engine size, horsepower, transmission)
- Present the findings in a clear, interactive dashboard

## 🛠️ Tools & Technologies
 
- **Microsoft Excel**
  - Data cleaning and preparation
  - PivotTables and Pivot Charts
  - KPI summaries (average price, mileage, engine size, horsepower)
  - Dashboard design
## 📈 Analysis & Key Findings
 
### Market Snapshot
- The average listing price is **₦4.99M**, but the **median is ₦3.2M**, so a few premium cars pull the average up.
- The average car has about **28,400 miles** and **217 horsepower**.
### Brands & Colors
- **Toyota** dominates with **1,126** listings, followed by **Honda** (310), **Lexus** (289), and **Mercedes-Benz** (261).
- **Black** is the most common color (741), followed by **Gray** (498) and **Silver** (484).
### Location
- **Lagos** has **1,452** listings and the **Federal Capital Territory** has **654**, far ahead of **Oyo** (270) and **Rivers** (84).
- **Ibadan** is the single most listed city (270).
### Transmission
- **Automatic** cars account for **2,702** listings against **171 manual**.
## 💡 Business Insights
 
1. **The market is dominated by a handful of brands.**
   Toyota alone makes up about **39%** of all listings, and Toyota, Honda, Lexus, and Mercedes-Benz together account for about **69%**. Sellers of other brands face a thin market, and dealers can safely stock up on Toyota models like the Camry, Corolla, and Sienna.
2. **Lagos and Abuja are the market.**
   Lagos (50%) and the FCT (23%) account for about **73%** of listings, so these two locations set the pricing benchmarks. Prices are similar in both (median about ₦3.4M in Lagos and ₦3.15M in the FCT), which suggests a national price level rather than a strong location premium.
3. **Condition is the biggest price divider.**
   Foreign Used cars have a median price of **₦6.3M**, about **2.2x** the **₦2.84M** for Nigerian Used cars, yet they are only about 17% of listings. Brand New cars (23 listings) sit far above at a median of ₦17.5M. Importing quality foreign-used cars is a clear premium niche.
4. **Age matters much more than mileage.**
   Year of manufacture has a strong correlation with price (**0.58**), while mileage has almost none (**0.07**). The median price rises from **₦1.5M** for cars made in 2000 or earlier to **₦6.3M** for 2011 to 2015 models and **₦16.8M** for 2016 and newer. Buyers appear to price on model year, not odometer readings, so newer cars hold their value well.
5. **Luxury brands and SUVs command a premium.**
   Land Rover (median ₦7.3M), Mercedes-Benz (₦5.3M), and Lexus (₦4.3M) sit well above Toyota (₦3.3M), while Peugeot and Honda are the cheapest at about ₦1.7M and ₦2.1M. SUVs are the most common body type among listings that have one (925 listings, average ₦7.1M), well above sedans (₦4.2M). Automatic cars are also the norm (about 94%) and are worth about 1.7x manual cars at the median.
### Recommendations
- Dealers should focus stock on Toyota and Lexus models, the highest-volume and most liquid segment.
- Price newer, foreign-used, and SUV listings at a clear premium.
- Use the **median** rather than the average when quoting typical prices.
- Consider expanding beyond Lagos and Abuja, where competition is heaviest.
## ⚠️ Data Notes & Limitations
 
- **Missing values:** body type is missing for 57% of listings and trim for 86%, so those breakdowns cover only a portion of the data.
- **Outliers:** 17 listings show engine sizes above 10,000 (up to 158,713), which likely reflect entry errors, and 16 used cars show zero mileage.
- **Skewed prices:** the average price is about 1.6x the median, so the median is a better measure of a typical car.
## 📸 Dashboard / Visualizations
 
![Dashboard Overview](images/dashboard_overview.png)
![Top Brands](images/top_brands.png)
![Listings by State](images/listings_by_state.png)
 
## 📚 Skills Demonstrated
 
- Data cleaning and handling of missing values
- PivotTables, Pivot Charts, and KPI summaries
- Market segmentation by brand, condition, location, and body type
- Price-driver analysis (age, mileage, condition, brand)
- Dashboard design and business storytelling
## 👤 Author
 Shodunke Feranmi
