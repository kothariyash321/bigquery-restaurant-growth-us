# Smart Restaurant Expansion Using BigQuery

A data-driven project that identifies high-potential U.S. counties for launching smart restaurants. Using Google BigQuery and SafeGraph mobility data, this project combines geospatial analysis, demographics, and market viability signals to provide actionable insights for strategic restaurant site selection.

## 🚀 Project Overview

This project explores where to open **next-generation smart restaurants**—featuring chef-bots, automated queue management, and demand prediction systems. By analyzing foot traffic patterns, median income, education, housing value, rent affordability, and business-friendliness across U.S. counties, we provide a shortlist of **investment-ready locations**.

Developed with a **digital product design mindset**, the analysis empowers data-backed business expansion decisions using real-world consumer and location data.

## 🧠 Key Questions Addressed

- Which states and counties offer the best conditions for new restaurant investments?
- Where is foot traffic rising despite low restaurant density?
- Which locations have high purchasing power and favorable business environments?
- What demographic and business metrics most strongly correlate with under-served demand?


## 🛠️ Tools & Technologies

- **Google BigQuery** – Core analytics engine
- **SafeGraph** – Foot traffic and POI data
- **US Census Demographics** – Income, housing, education, age
- **SQL** – Data transformation and aggregation
- **MS PowerPoint / PDF** – Final deliverables

## 📊 Methodology

1. **Data Extraction**: Pulled foot traffic and demographic data from SafeGraph tables.
2. **County-Level Aggregation**: Summarized metrics like dwell time, visit counts, income brackets, and house values.
3. **Ranking & Filtering**: Applied weighted percentile and threshold logic to identify top counties.
4. **Cross-Dataset Join**: Merged restaurant brand data, FIPS mappings, and state-level business rankings.
5. **Insight Generation**: Generated investment recommendations based on data-driven thresholds.

## 🌎 Key Metrics Considered

- Foot traffic volume & trends
- Median dwell time
- Household income > $75k
- Rent and housing value brackets
- Population age distribution (15–39)
- Education level (college or higher)
- Business costs, accessibility, and climate

## 💡 Insights & Outcomes

- Identified 10+ high-potential counties across multiple states.
- Revealed underserved regions with strong consumer and business signals.
- Informed launch planning for a smart restaurant chain.
- Provided framework that can be extended to other industries (e.g., grocery).

## 📌 Project Status

✅ Completed SQL-based analysis  
✅ Final presentation and report delivered  
🔄 Optional: Streamlit dashboard or interactive visualizations (future work)

## 👥 Contributors

- Dhairya Dedhia  
- Yash Kothari  


