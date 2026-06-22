# Assignment-Python-For-Analyst
This assignment assesses my technical ability to work with real world data using Python. I will select a dataset, clean and prepare it, perform exploratory and analytical work, and present my findings in a clear, well structured notebook. The focus is on demonstrating my command of the Python skills covered in sessions

## Data Overview

### Source

The dataset is *Electric Vehicle Market and Pricing Dataset 2026*, published on Kaggle by Patel Ris:
[https://www.kaggle.com/datasets/patelris/electric-vehicle-market-and-pricing-dataset-2026](https://www.kaggle.com/datasets/patelris/electric-vehicle-market-and-pricing-dataset-2026)

### Contents

A single CSV file with 2,000 rows and 24 columns. The columns cover three broad domains:

- **Identification** — brand, model, year, variant, country of origin, market segment
- **Technical specifications** — price, battery capacity, range, charging speed, horsepower, torque, acceleration, top speed, weight, drive type, autopilot level, safety rating, seating, cargo, warranty
- **Commercial outcomes** — annual sales units, customer rating

### Research questions

This notebook will analyse four questions:

1. **What drives price?** Is it range, battery, brand, or something else?
2. **What drives customer satisfaction?** And is it the same thing as what drives price?
3. **What drives sales volume?** Which spec actually moves units?
4. **Are there geographic patterns** in cost-efficiency and value-for-money?

## Result

## Key Findings

### 1. What Drives Vehicle Price?

Analysis showed that **horsepower is the strongest predictor of price** (r = 0.76), while driving range has only a weak relationship with price (r = 0.16). This suggests that manufacturers primarily position and price electric vehicles based on performance rather than range capability.

### 2. What Drives Customer Satisfaction?

Customer ratings were most strongly associated with **driving range** (r = 0.67) and **battery capacity** (r = 0.66). These results indicate that consumers place greater value on practical usability and vehicle capability than on raw performance or purchase price.

### 3. What Drives Sales Volume?

Among all variables analysed, **charging speed** showed the strongest relationship with sales volume (r = 0.40). Vehicle price demonstrated almost no correlation with sales (r = -0.03), suggesting that charging convenience is a more important commercial factor than cost alone.

### 4. Geographic Value Comparison

A comparison of price per mile of driving range revealed notable regional differences:

| Country       | Cost per Mile of Range |
| ------------- | ---------------------- |
| Japan         | $248                   |
| China         | $253                   |
| South Korea   | $254                   |
| United States | $338                   |
| Sweden        | $343                   |
| Germany       | $376                   |

The findings indicate that Asian manufacturers generally provide better value for money, offering more driving range per dollar spent than their European counterparts.

### 5. Central Insight

The analysis revealed a strategic disconnect within the electric vehicle market:

* Manufacturers optimise for **power and performance**
* Customers value **range and battery capability**
* Market success is most strongly linked to **charging speed**

This suggests that the factors influencing pricing, customer satisfaction, and sales volume are not aligned. Among the brands analysed, Tesla was the only manufacturer positioned in both the high-price and high-volume segment of the market.

