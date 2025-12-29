# Michelin Restaurants Analysis

This project performs **exploratory data analysis (EDA)** on Michelin-starred restaurants worldwide, providing insights into locations, awards, cuisines, pricing, and sustainability.

---

## Dataset

- **File:** `michelin_my_maps.csv`
- **Key Columns:**  
  `Name`, `Address`, `City`, `Country`, `Price`, `Cuisine`, `Award`, `GreenStar`
- **Preprocessing:**  
  - Removed irrelevant columns: `PhoneNumber`, `Url`, `WebsiteUrl`, `FacilitiesAndServices`, `Description`  
  - Extracted `City` and `Country` from the `Location` column

---

## Libraries

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

---

## Key Analyses

1. **General Overview**  
   - Dataset shape, info, and missing values  
   - Unique values per column

2. **Awards & Sustainability**  
   - Count of 1, 2, 3-star restaurants  
   - Green Star certification percentage  

   ![Award Distribution](images/award_distribution.png)  
   ![Green Star Pie](images/green_star_pie.png)  

3. **Geographical Analysis**  
   - Top cities and countries with Michelin restaurants  
   - Award distribution by city/country  

   ![Top Cities](images/top_cities.png)  
   ![Top Countries](images/top_countries.png)  

4. **Cuisine Analysis**  
   - Top 10 cuisine types  

   ![Cuisine Pie](images/top_cuisines.png)  

---

## How to Run

```bash
pip install numpy pandas matplotlib seaborn
