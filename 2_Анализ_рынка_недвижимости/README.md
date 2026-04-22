# **Project: Apartment Listings in Saint Petersburg — Real Estate Market Analysis**

## **Description**
**Data source:** Yandex.Real Estate dataset (archive of apartment listings in Saint Petersburg and nearby areas over several years)

**Objective:**  
Determine the market value of different types of properties and identify typical apartment characteristics depending on distance from the city center.

## **Work Performed**
- Conducted data preprocessing  
- Performed feature engineering (created additional variables)  
- Built visualizations: histograms, boxplots, and scatter plots  
- Carried out exploratory data analysis (EDA)  

The results were used to design an approach for estimating apartment prices based on key features and to help detect potential fraud in listings.

## **Tech Stack**
Matplotlib, Pandas, Python, Data Visualization, Exploratory Data Analysis, Data Preprocessing  

## **Key Findings**
The analysis covers apartment listings in Saint Petersburg and surrounding areas from November 2014 to March 2019. The dataset includes properties across different market segments, including premium real estate.

**Correlation with final price (1 = strong, 0 = none):**
- Total area: 0.65  
- Living area: 0.55  
- Kitchen area: 0.45  
- Number of rooms: 0.40  

- Floor level impacts pricing:
  - First-floor apartments are at least **7% cheaper**  
  - Top-floor apartments show a **8–9% price decrease**  

- No significant relationship was found between listing publication date and final price  

- Among the top 10 locations by number of listings:
  - **Most expensive:** Saint Petersburg — 15,352 listings, 104,656 RUB/m²  
  - **Least expensive:** Gatchina — 293 listings, 67,671 RUB/m²  

- A clear trend shows decreasing property prices with increasing distance from the city center  

## **Conclusion**
- Property size and number of rooms are the strongest predictors of price  
- Floor level is a significant pricing factor  
- Location (distance from city center) strongly influences property value  

Additional factors to consider:
- Property class (premium vs standard), as luxury housing skews distributions  
- Year of construction, which may explain anomalies (e.g., price drops ~3 km from city center in mid-rise buildings)  

Further analysis is recommended to validate these hypotheses.

## **Status**
Completed
