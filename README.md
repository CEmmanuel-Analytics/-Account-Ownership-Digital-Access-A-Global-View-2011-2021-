## Account Ownership Digital Access A Global_View 2011-2021

📊 Chibueze Emmanuel – Global Financial Inclusion Dashboard (2011–2021)

📖 Project Overview

This project analyzes data from the World Bank Global Findex database to track global trends in financial inclusion between 2011 and 2021. Using interactive visuals in Power BI, the dashboard examines how account ownership, digital payment access, and gender-based disparities vary across countries and regions.

  **The Goal is to:**
- Explore inclusion rates by gender, country, and year
- Understand gender gaps in account ownership
- Identify regional leaders and laggards in digital access
-Track how financial access has evolved globally

🛠️ Tools & Technologies

Power BI: Dashboard creation, DAX measures, visual interactivity

DAX: For custom measures like gender gap

Data source: Simplified World Bank Global Findex CSV (2011–2021)

CSV Data Format: For data cleaning and preparation

🔄Data Overview
**The dataset includes:**

-Countries: 10 (e.g., Nigeria, Kenya, Germany, Brazil, France, etc.)
-Regions: Sub-Saharan Africa, South Asia, Europe, etc.
-Years: 2011, 2014, 2017, 2021
-Indicators: Account Ownership, Digital Payments
-Gender: Male, Female
-Key calculated metric:
-Gender Gap = Male Inclusion − Female Inclusion (per country)

📊 Dashboard Visuals:<img width="931" height="623" alt="Inclusion Rate by Country" src="https://github.com/user-attachments/assets/b3a47695-5fc8-4326-ab2d-1c45c13c99eb" />
1. Tree Map – Inclusion by Country
A tree map displaying average inclusion rates by country.
France, Kenya, and Nigeria had the highest overall inclusion.
Easy comparison of country performance based on block size.

2. Clustered Bar Chart – Inclusion by Gender
<img width="718" height="454" alt="Inclusion Rate by Country Stacked with Gender" src="https://github.com/user-attachments/assets/44488099-f60c-45bb-89d1-74a064174522" />

Side-by-side comparison of Male vs Female inclusion rates for each country.
-Nigeria: Female 74.9% vs Male 48.5%

-Kenya: Female 71.6% vs Male 54.9%

-Countries like France showed traditional male-led inclusion

3. Gender Gap Chart – Custom Measure
<img width="924" height="446" alt="Gender Dax Calculated Inclined Gap by Country " src="https://github.com/user-attachments/assets/d58f4c96-5d09-474e-a03e-ea89a92ec0a6" />

A clustered column chart showing the gender gap per country.
France: +15 (men lead)
Nigeria: -32 (women lead)
Pakistan: -41 (strong gender gap)
-This visual uses positive/negative bars to highlight where gender disparities are widest.

4. Line Chart – Yearly Trends by Gender
<img width="830" height="387" alt="Yearly Change Rate" src="https://github.com/user-attachments/assets/89bbd2f2-194b-4d48-9a38-b8a7c498bb23" />

-Tracks inclusion rates from 2011 to 2021 by gender.
-Women maintained higher inclusion rates across most years.
-Males saw a decline from 2017 to 2021.

5. Matrix Table – Region vs Year
<img width="353" height="231" alt="Regional Performance" src="https://github.com/user-attachments/assets/0277a286-89b4-4f20-88af-f1fa1bdc3f37" />

A heatmap-style matrix showing regional inclusion rates over time.
Sub-Saharan Africa consistently led in average inclusion.
South Asia ranked lowest across years.

6. Stacked Bar Chart – Inclusion by Country
<img width="926" height="491" alt="Countries Perfomance " src="https://github.com/user-attachments/assets/256f60fc-c5b3-4ce0-8271-5e41e4f764c6" />

-Ranks countries based on overall average inclusion rates.
-France, Kenya, Nigeria: Highest
-Germany, India, Brazil: Lowest

 Interactive Features

Slicers for:

Year (2011–2021)

Indicator (Account Ownership / Digital Payments)

Gender (Male / Female)

-These allows more efficient explorative view of the data dynamically.

🔍 Key Insights

-Women lead account ownership in countries like Nigeria and Kenya
-Pakistan shows one of the worst gender gaps at −41%
-France and Brazil show traditional male-favored patterns

-Sub-Saharan Africa emerges as a surprising leader in inclusion

-Digital access has grown steadily across most countries

**Discoveries**
-Financial Inclusion = Having access to financial services (bank accounts, mobile money, etc.)

-Gender Gap = Difference between male and female inclusion rates (positive = men lead, negative = women lead)

-Digital Access = Use of digital payments instead of cash

**This project helped me analyze real-world inclusion data across countries. I created an interactive Power BI dashboard with DAX measures, year slicing, and gender comparisons. I discovered that inclusion doesn’t always follow expectations – in some regions, women lead. This kind of insight helps policymakers and financial institutions make data-informed decisions.**

