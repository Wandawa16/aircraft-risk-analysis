# Aircraft Risk Analysis

## Overview
This project analyzes aviation accident data from 1962-2023 to identify low-risk aircraft for commercial and private operations. The goal is to provide insights that will help stakeholders make informed decisions when purchasing aircraft.

## Business Understanding
### Stakeholder
A company looking to expand into aviation operations needs to understand which aircraft have the lowest risk before making purchase decisions.

### Key Business Questions
1. What factors contribute to aircraft accidents?
2. Which aircraft models have the lowest accident and fatality rates?
3. How do different factors (weather, phase of flight, manufacturer) impact risk levels?

## Data Understanding and Analysis
### Data Source
- **Dataset:** National Transportation Safety Board (NTSB)
- **Records:** 88,889 aviation accident reports
- **Key Features:**
  - Aircraft Make & Model
  - Injury Severity & Fatalities
  - Accident Location & Date
  - Weather Conditions
  - Phase of Flight at Accident

### Data Cleaning Steps
- Handled missing values in key fields (latitude, longitude, injury severity)
- Standardized categorical data (e.g., manufacturer names)
- Converted date formats for analysis
- Removed duplicate records

### Visualizations
1. **Accident Trends Over Time** - Shows the number of accidents per year.
   ![image](https://github.com/user-attachments/assets/3cbded56-e20d-4e14-b8bf-07b389f92b3e)


   
3. **Top 10 Manufacturers with Most Accidents** - Highlights which aircraft makers have the highest accident occurrences.
![image](https://github.com/user-attachments/assets/626b3b7c-7941-4bc6-ba45-190e2f14fa4e)

5. **Fatality Rates by Aircraft Model** - Displays models with the highest and lowest fatality rates.
   

## Conclusion
### Findings
1. Some aircraft models have significantly higher accident rates than others.
2. Weather conditions and flight phase at the time of accident impact risk levels.
3. Specific manufacturers have consistently lower accident occurrences.

### Business Recommendations
- Prioritize purchasing aircraft models with historically lower accident rates.
- Consider accident trends when selecting aircraft for different flight conditions.
- Monitor and implement stricter maintenance and operational safety protocols.

## Project Files
- **project.ipynb** - Jupyter Notebook containing data analysis and visualizations.
- **presentation.pdf** - A non-technical presentation summarizing key findings.
- **dashboard_link.txt** - Link to the interactive Tableau dashboard.
- **data/** - Contains raw and cleaned datasets.
- **notebooks/** - Exploratory analysis notebooks.
- **images/** - Saved visualizations used in reports.

## Next Steps
- Improve the dataset by integrating more recent accident reports.
- Expand analysis to include additional risk factors (e.g., airline safety records).
- Implement a machine learning model to predict accident probabilities.

## Contact
- **Author:** Gerald
  


