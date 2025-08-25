# Pivitt Keyword Analysis Dashboard

This project analyses keyword search data to identify the best budget allocation opportunities for Pivitt’s services:

- Branding/Rebranding  
- Brand Consulting  
- Brand Management  
- Digital Experiences  

---

## Data Preparation (Excel)

Before building the dashboard, I used Excel to clean and structure the raw keyword dataset:  
- Removed irrelevant or inaccurate columns (e.g., CR and Leads).  
- Categorised each keyword into one of the 4 service categories (or "Other/Generic" if no clear fit).  
- Created calculated columns to highlight search demand, competition, and CPC.  
- Added an **Opportunity Score (Z-score)** to compare keywords fairly across services.  
- Simplified the dataset into a clean, analysis-ready `.csv` for Power BI import.  

This ensured the data was accurate, structured, and directly linked to Pivitt’s business goals.  

---

## Dashboard Overview (Power BI)

The Power BI dashboard includes:  
- **Search Demand by Service Category** (bar chart)  
- **Cost vs Competition** (scatter plot, bubble size = demand)  
- **Top Keywords by Opportunity Score** (ranked table)  
- **Interactive slicer** (filter by service category)  

---

## Key Insights

- A large portion of demand sits in **Other/Generic** terms, but these are broad and less targeted.  
- **Brand Management** has the highest targeted demand (10k+ monthly searches).  
- **Brand Consulting** terms are lower in volume but highly strategic (niche, high-value keywords).  
- **Digital Experiences** show lower demand but carry higher CPC (expensive space).  

---

## Files
- `.pbix` → Interactive Power BI dashboard  
- `.csv` → Cleaned keyword dataset (Excel output)  
- `.png` → Screenshot preview of dashboard  

---

## How to Use
- Open `.pbix` file with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)  
- Or view static screenshot/PDF in this repo  
