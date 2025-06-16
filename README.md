# ☕ Maven Roasters Sales Analysis 📊

---

## ✨ Project Background ✨

Maven Roasters, a coffee shop with three locations across New York City, collects a significant amount of data on its sales. This project undertakes a thorough analysis of Maven Roasters' sales records from the past few months to uncover key trends and performance indicators that can inform business decisions and drive revenue growth.

The company’s detailed dataset contains transaction dates, timestamps, product information (category, type, menu item), pricing, quantities, store locations, and overall transaction values. This analysis aims to synthesize this data to provide actionable insights in the following key areas:
* **Sales Trend:** 📈 Evaluation of the overarching sales performance of Maven Roasters over the past few months, identifying growth patterns, seasonality, and any significant fluctuations.
* **Product Performance:** 🍩 An assessment of the sales contribution and trends for various product categories (e.g., Coffee, Tea, Bakery) and individual menu items, highlighting top and underperforming products.
* **Store Performance:** 📍 A comparative analysis of sales performance across Maven Roasters' three NYC locations, identifying top-performing stores and areas for potential improvement.

Data was initially inspected and prepared using Microsoft Excel.
Interactive dashboards and analyses, addressing sales trends, product, and store performance, are available in Tableau: 🔗 https://public.tableau.com/views/MavenRoastersSalesProductandStoreDashboard/MavenRoastersProductDashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🔍 Data Structure & Initial Checks 📋

The dataset for this Maven Roasters sales analysis consists of a single table containing transaction records. This table includes key information such as transaction date, timestamp, product details (category, type, menu item), unit price, transaction quantity, store ID, and transaction value, with a total row of 149117 records.

![image](https://github.com/user-attachments/assets/12af8cb1-03c9-4be6-ac03-0e2941e0bcd1)

Before analysis, initial quality checks confirmed a clean dataset with no significant missing values or outliers. Data types and unique entry ranges were verified for accuracy.

---

## 🌟 Executive Summary 🌟

### Overview and Findings

Overall, Maven Roasters has shown a strong positive sales trend from January to June 2023, with the total sales of $166,485.88 in the latest month. After an initial dip to $76,145.19 in February (a significant decrease compared to January's $81,677.74), sales experienced a robust recovery and subsequent growth. This growth has been significantly supported by the strong performance of the Coffee category, which commands the largest revenue share and exhibits a consistent upward trend. Additionally, the resilience of key individual products like "Morning Sunshine Chai Lg" from the “Tea” category has contributed to the overall positive trajectory.

Key performance indicators for the most recent month (June) compared to the previous month (May) indicate continued upward trend, with total sales increased by 6.23%, transaction quantity rose by 5.44%, and the average transaction value (ATV) experienced a slight increase of 0.74% to $4.71. The following sections will look into the contributing factors behind these trends, examining performance at the product category and store levels to identify key drivers and potential areas for further growth.

---

## 📈 Sales Trends 📈
![image](https://github.com/user-attachments/assets/1e11d171-7f6b-4375-89ba-d01b300d93ed)
* **Overall Peak:** June 2023 saw highest revenue ($166.5K), transactions (35.3K), and ATV ($4.71).
* **Overall Low:** February 2023 marked the lowest in revenue ($76.1K), transactions (16.4K), and ATV ($4.65).
* **Post-Feb Recovery:** Sales strongly recovered post-February, driven by transaction volume, while ATV remained stable ($4.65-$4.72).
* **Key Time Patterns:** Monthly sales peaked in June 2023, with weekly highs around June 18th ($41K). Daily sales were strongest on Mondays ($101.7K) and Fridays ($101.4K), but lowest on Saturdays ($96.9K).
* **Morning Peak:** Hourly sales consistently peaked around 10 AM ($88.7K).
* **Evening Drop:** Early mornings (6 AM, $21.9K) and late evenings (8 PM, $2.9K) had the lowest hourly sales.

---

## ☕ Product Performance 🍩
![image](https://github.com/user-attachments/assets/ddb0f20d-0610-42b1-94bc-65312a500516)
* **Dominant Categories:** Coffee leads (38.63%/$270K, strong growth), followed by Tea (28.11%/$196K), Bakery (11.78%/$82K), and Drinking Chocolate (10.36%/$72K).
* **Top Products (Non-Coffee Leads):** While Coffee is the top category, the two highest-selling individual products are "Sustainably Grown Organic Lg" ($21.2K) and "Dark Chocolate Lg" ($21K), both from Drinking Chocolate, outperforming top coffee items. Overall top 5 also include "Latte Rg", "Morning Sunshine Chai Lg", and "Cappuccino Lg".
* **Store-Specific & Growth:** "Dark Chocolate Lg" tops Astoria/Lower Manhattan; "Sustainably Grown Organic Lg" tops Hell's Kitchen. "Morning Sunshine Chai Lg" showed consistent growth to $17.4K in June.
* **Underperforming:** The "Other" category (5.4% revenue/$37.6K) significantly underperforms core categories.

---

## 📍 Store Performance 🏢
![image](https://github.com/user-attachments/assets/08c8bfbd-a2be-4dc1-855a-6a313ae5469c)
* **Overall & February Dip:** All stores experienced a sales decline in February, followed by a recovery.
* **Hell's Kitchen** led in total sales ($236.5k).
* **Astoria** was second ($232.2k), with its lowest sales in February ($25.1k).
* **Lower Manhattan** had the lowest total sales ($230.1k) but outperformed Astoria in February.
* **Astoria (7 AM - 8 PM):** Showed a stable sales trend, typical of a residential area. Peak sales were in the morning (8 AM - 10 AM) and on Wednesdays.
* **Lower Manhattan (6 AM - 9 PM):** Sales were driven by weekday business, with a strong morning peak (9 AM - 11 AM) and a gradual decline after office hours. Mondays were a strong daily peak.
* **Hell's Kitchen (6 AM - 9 PM):** Displayed a dynamic pattern with strong performance during morning rush hours (8 AM - 10 AM) and a significant surge in the late afternoon, reflecting its diverse customer base. Tuesdays and Fridays were strong daily peaks.

---

## 💡 Recommendations 💡

### 🟢 Immediate Impact:
- **February Sales Dip:** Conduct a thorough "February Dip Analysis" involving sales data review, staff interviews, and potentially customer surveys to identify the key reasons for the significant decline. Use these findings to inform a targeted strategy for future Februaries.  
- **Increase ATV:** Implement "Pair & Size Up" prompts at checkout and offer "Value Combos”.  
- **Leverage Monday Peaks (Lower Manhattan):** Launch a "Monday Kickstart" deal to capitalize on strong early-week traffic.  

### 🟡 Mid-Term Strategies:
- **Lower Manhattan Evenings:** Introduce an "After-Work Perk" (5–7 PM) and optimize evening staffing.  
- **Afternoon Sales:** Launch an "Afternoon Boost" (2–4 PM) and offer loyalty points for afternoon purchases.  
- **Product Focus Realignment:** Re-evaluate and enhance core coffee offerings while bundling them with high-performing non-coffee items to reinforce brand identity and boost individual coffee product sales.  
- **Astoria Midweek Offer:** Introduce a "Midweek Treat" on Wednesdays to build on Astoria's weekday strength.  
- **Hell’s Kitchen PM Surge:** Extend staffing and promote light snacks or drinks from 3–5 PM to ride the late-day momentum.  

### 🔵 Long-Term Review:
- **Underperforming "Other" Category:** Survey customers, discontinue bottom SKUs, and test remaining items with a "Small Batch Spotlight."

