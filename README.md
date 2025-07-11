# Starbucks Geospatial Store Location Analysis

## Project Overview

In this project, I conducted a **geospatial analysis of Starbucks US store locations** combined with county-level demographic data to identify **optimal expansion opportunities**.

---

## Objective

**Problem:**  
Starbucks aims to expand its store network strategically to maximise revenue and market penetration while avoiding cannibalisation of existing stores.

**Goals:**

- Map existing Starbucks US locations
- Integrate county-level population and median income data
- Identify counties with high market potential and low store density
- Recommend optimal locations for strategic expansion

---

## Dataset

1. **Starbucks Store Locations Dataset** (Kaggle)  
   - Store name, city, state, latitude, longitude

2. **US County Demographics Dataset (ACS 2017)** (Kaggle)  
   - County, state, total population, median household income

3. **US Counties Latitude-Longitude Dataset** (Simplemaps)  
   - County, state, latitude, longitude, county population

---

## Analysis Steps

1. Imported and explored all datasets  
2. Filtered Starbucks data for US stores only  
3. Cleaned county naming conventions for dataset merging  
4. Merged demographic and location data to integrate population, income, and geolocation  
5. Created interactive Folium maps:
   - **Counties sized by population, coloured by income**
   - **Starbucks stores overlaid as red markers**

---

## Key Results

- **High opportunity counties identified:**  
  Counties with large populations and high median incomes but low Starbucks density present ideal expansion targets.

- **Strategic insights:**  
  Recommended prioritising counties with populations over 200,000 and median household incomes above $60,000 lacking sufficient Starbucks presence.

---

## Business Recommendations

1. **Expand in High-Potential Counties**  
   Target counties with strong purchasing power and minimal internal competition to maximise profitability.

2. **Conduct Competitive and Feasibility Analysis**  
   Complement demographic insights with on-ground feasibility and competitive assessments before rollout.

3. **Incorporate Customer Behaviour Data (Future Work)**  
   Integrate mobility data, consumer preferences, and loyalty metrics to refine site selection further.

---

## Conclusion

This geospatial project demonstrates how integrating **store location data with demographic intelligence** enables data-driven market expansion strategies, supporting revenue growth and operational efficiency for retail businesses.

---

## Tools Used

- Python (pandas, numpy)
- geopandas
- folium
- matplotlib, seaborn

---

## Repository Structure

- `starbucks_geospatial_analysis.ipynb` – Main analysis notebook
- `images/` – Visualisations and map screenshots

---

## Author

[Aditya Prabhu](https://github.com/AdityaPbhu)

---

**Feel free to connect if you have questions about this project or geospatial business analytics.**
