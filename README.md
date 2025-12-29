# Michelin Restaurants Analysis

This project performs **exploratory data analysis (EDA)** on Michelin-starred restaurants worldwide. The analysis provides insights into restaurant locations, awards, cuisines, pricing, and sustainability.

---

## Dataset

- **File:** `michelin_my_maps.csv`
- **Key Columns:**  
  `Name`, `Address`, `City`, `Country`, `Price`, `Cuisine`, `Award`, `GreenStar`
- **Preprocessing:**  
  - Removed irrelevant columns: `PhoneNumber`, `Url`, `WebsiteUrl`, `FacilitiesAndServices`, `Description`  
  - Extracted `City` and `Country` from the `Location` column  
  - Converted `GreenStar` from 0/1 to "Yes"/"No"  
  - Converted `Price` into a visual `$` format based on length  

---

## Libraries

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

---

## Data Exploration

1. **General Overview**  
   - Checked dataset shape, data types, missing values, and duplicates  
   - Counted unique values for categorical and numeric columns  

2. **Awards & Sustainability**  
   - Count of 1, 2, and 3-star restaurants  
   - Percentage of restaurants with Green Star certification  

3. **Geographical Analysis**  
   - Top cities and countries with Michelin-starred restaurants  
   - Distribution of awards (1, 2, 3 stars) by city and country  

4. **Cuisine Analysis**  
   - Top 10 cuisine types served in Michelin-starred restaurants  

---

## Insights

- **Geographical Concentration:**  
  Michelin-starred restaurants are concentrated in a few countries and cities, especially in Europe and East Asia.  

- **Award Distribution:**  
  - 1-star restaurants are the most common  
  - 3-star restaurants are rare and geographically concentrated  

- **Sustainability:**  
  Only a small fraction of restaurants have a Green Star certification, indicating sustainability practices are still limited.  

- **Cuisine Trends:**  
  French and European cuisines dominate, followed by Japanese and modern fusion cuisines.  

- **Pricing Insight:**  
  Higher Michelin stars often correlate with higher price levels, but there is variation across countries and cities.  

- **Overall:**  
  The Michelin Guide highlights culinary excellence concentrated in major cities and certain countries, with limited but growing emphasis on sustainability.
