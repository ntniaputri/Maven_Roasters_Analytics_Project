# Maven Roasters' Sales Trends

## Project Background

Maven Roasters, a coffee shop with three locations across New York City, collects a significant amount of data on its sales. This project undertakes a thorough analysis of Maven Roasters' sales records from the past few months to uncover key trends and performance indicators that can inform business decisions and drive revenue growth.

The company’s detailed dataset contains transaction dates, timestamps, product information (category, type, menu item), pricing, quantities, store locations, and overall transaction values. This analysis aims to synthesize this data to provide actionable insights in the following key areas:

* **Sales Trend:** Evaluation of the overarching sales performance of Maven Roasters over the past few months, identifying growth patterns, seasonality, and any significant fluctuations.
* **Product Performance:** An assessment of the sales contribution and trends for various product categories (e.g., Coffee, Tea, Bakery) and individual menu items, highlighting top and underperforming products.
* **Store Performance:** A comparative analysis of sales performance across Maven Roasters' three NYC locations, identifying top-performing stores and areas for potential improvement.

- Data was initially inspected and prepared using Microsoft Excel.
- Interactive dashboards and analyses, addressing sales trends, product, and store performance, are available in Tableau: 

## Data Structure & Initial Checks

The dataset for this Maven Roasters sales analysis consists of a single table containing transaction records. This table includes key information such as transaction date, timestamp, product details (category, type, menu item), unit price, transaction quantity, store ID, and transaction value, with a total row of 149117 records.

Before analysis, data accuracy and understanding were ensured by verifying data types, identifying missing values, examining unique entry ranges, and scanning for outliers.

## Executive Summary

### Overview and Findings

Overall, Maven Roasters has shown a strong positive sales trend from January to June 2023, with the total sales of $166,485.88 in the latest month. After an initial dip to $76,145.19 in February (a significant decrease compared to January's $81,677.74), sales experienced a robust recovery and subsequent growth. This growth has been significantly supported by the strong performance of the Coffee category, which commands the largest revenue share and exhibits a consistent upward trend. Additionally, the resilience of key individual products like "Morning Sunshine Chai Lg" from the “Tea” category has contributed to the overall positive trajectory.

Key performance indicators for the most recent month (June) compared to the previous month (May) indicate continued upward trend, with total sales increased by 6.23%, transaction quantity rose by 5.44%, and the average transaction value (ATV) experienced a slight increase of 0.74% to $4.71. The following sections will look into the contributing factors behind these trends, examining performance at the product category and store levels to identify key drivers and potential areas for further growth.

## Sales Trends

* June 2023 had peak revenue ($166,485.88) with 35,352 transactions and a $4.71 ATV. Weekly sales peaked around June 18th ($41,036.10). Mondays ($101,677.28) and Fridays ($101,373.00) had the highest daily sales, with an hourly peak around 10 AM ($88,673.39).
* February 2023 saw the lowest transactions (16,359), ATV ($4.65), and revenue ($76,145.19). Weekly sales bottomed around January 29th ($16,987.64). Saturdays had the lowest daily sales ($96,894.48), and hourly sales were lowest in early mornings (6 AM, $21,900.27) and late evenings (8 PM, $2,935.64).
* Sales recovered strongly after the February dip, driven by increased transactions while ATV remained stable ($4.65-$4.72). Weekly sales showed an upward trend with fluctuations. Daily sales were strongest on Mondays and Fridays, weakest on Saturdays. Hourly sales peaked in the morning (10 AM) and declined through the evening.

## Product Performance

* Maven Roasters' product performance is significantly driven by the Coffee category, which commands the largest share of revenue at 38.63% (representing $269,952 in total sales) and demonstrates a strong upward sales trend from January to June. Following Coffee, Tea contributes a substantial 28.11% ($196,406), with Bakery at 11.78% ($82,316) and Drinking Chocolate at 10.36% ($72,416) also representing significant portions of the overall revenue. Coffee Beans round out the top 5 categories by sales, contributing 5.74% ($40,085).
* The top 5 performing products across all stores are "Latte Rg (Coffee)", "Morning Sunshine Chai Lg" (Tea), "Cappuccino Lg" (Coffee), "Dark Chocolate Lg" (Drinking Chocolate), and "Sustainably Grown Organic Lg" (Drinking Chocolate).
* Interestingly, the top two individual sellers are Drinking Chocolate: Sustainably Grown Organic Lg ($21.2k) and Dark Chocolate Lg ($21k), outperforming even products from the leading Coffee category.
* Store-specific top performers are: Astoria and Lower Manhattan: Dark Chocolate Lg, and Hell's Kitchen: Sustainably Grown Organic Lg.
* Morning Sunshine Chai Lg showed strong resilience with consistent growth to $17.4k in June.
* The "Other" category (5.4% revenue, $37.6k), which includes Branded, Loose Tea, Flavours, and Packaged Chocolate, appears to be underperforming due to its significantly smaller revenue contribution compared to the top categories.

## Store Performance

* Hell's Kitchen led in total sales ($236.5k).
* Astoria typically ranked second ($232.2k) despite a sales low in February ($25.1k).
* Lower Manhattan had the lowest total sales ($230.1k) but outperformed Astoria in February.
* All stores experienced a sales decline in February, followed by recovery.
* Astoria (operating hours 7 AM - 8 PM) showed a more stable sales trend throughout its operating hours, typical of a residential area during this period.
* Astoria also saw its peak sales in the morning (8 AM - 10 AM) and had a strong daily peak on Wednesdays.
* Lower Manhattan (operating hours 6 AM - 9 PM) sales were likely driven by weekday business within this timeframe, with a noticeable drop-off outside of typical work hours.
* Lower Manhattan did exhibit a strong morning sales peak, likely between 9 AM and 11 AM, consistent with weekday business hours. Sales then gradually decreased throughout the afternoon, showing a noticeable drop-off after typical office hours (around 5 PM), and showed a notable daily peak on Mondays.
* Hell's Kitchen (operating hours 6 AM - 9 PM) displayed a dynamic pattern with strong performance during traditional rush hours and a significant surge in the late afternoon, reflecting its diverse customer base in a lively area during these months.
* Hell's Kitchen experienced its peak sales volume during the morning hours (8 AM - 10 AM) and showed strong daily peaks on Tuesdays and Fridays.

## Recommendations

### Immediate Impact:

* **February Sales Dip:** Conduct a thorough "February Dip Analysis" involving sales data review, staff interviews, and potentially customer surveys to identify the key reasons for the significant decline. Use these findings to inform a targeted strategy for future Februaries.
* **Increase ATV:** Implement "Pair & Size Up" prompts at checkout and offer "Value Combos”.

### Mid-Term Strategies:

* **Lower Manhattan Evenings:** Introduce an "After-Work Perk" (5-7 PM) and optimize evening staffing.
* **Afternoon Sales:** Launch an "Afternoon Boost" (2-4 PM) and offer loyalty points for afternoon purchases.

### Long-Term Review:

* **Underperforming "Other" Category:** Survey customers, discontinue bottom SKUs, and test remaining items with a "Small Batch Spotlight."
