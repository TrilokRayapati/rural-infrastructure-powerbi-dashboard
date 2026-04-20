# Rural Infrastructure Analysis Dashboard (Power BI)

## Overview
This project focuses on analyzing village-level data across India to understand how rural infrastructure is distributed across different states and districts.

The dataset contains over 6.1 lakh records, which were initially spread across multiple Excel files. These files were combined, cleaned, and transformed using Power Query, and then analyzed in Power BI using DAX.

## Dataset
- ~613,000+ rows  
- 8 columns  
- Combined from 32 Excel files  
- Includes State, District, Sub-district, and Village-level data  

## What I Built
- A fully interactive Power BI dashboard  
- Drill-down functionality from State → District → Sub-district  
- Filters to explore specific regions  
- Top-N analysis to highlight key areas  

## DAX Measures Used
- **Total Villages** – Counts total number of villages  
- **% Contribution** – Shows each state's share in the overall dataset  
- **District Rank** – Ranks districts based on village count 

## Tools Used
- Power BI  
- Power Query  
- DAX  
- Excel  

## Key Insights
- Some states contribute a significantly higher number of villages  
- A small number of districts account for a large portion of the data  
- Ranking and percentage analysis help identify high-impact regions  

## Dashboard Preview

![Overview](overview.png)
![Filtered View](Filtered_view.png)
![Drill-down](drilldown.png)

## How to Use
1. Download the `.pbix` file  
2. Open it in Power BI Desktop  
3. Use filters and drill-down to explore the data  

## Future Improvements
- Add more real-world indicators (population, literacy, etc.)  
- Connect to live data sources  
- Extend analysis using Python or advanced models  


## Author
Rayapati Trilok
