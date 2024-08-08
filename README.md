Overview
This project involves cleaning, analyzing, and visualizing data from the Global Terrorism Database and the World Happiness Report. The goal is to understand patterns in global terrorism incidents and their relationship with happiness scores across different countries.

Files
globalterrorismdb_0718dist.csv: Dataset containing global terrorism data.
2015.csv: Dataset containing world happiness scores for the year 2015.
Libraries Used
pandas: For data manipulation and analysis.
numpy: For numerical operations.
seaborn: For statistical data visualization.
matplotlib.pyplot: For creating static, animated, and interactive visualizations.
Steps and Analysis
Data Import
The datasets are imported from CSV files for subsequent analysis.

Data Cleaning
Selected relevant columns from the terrorism dataset.
Removed duplicates and addressed missing values to ensure data integrity.
Data Exploration
Terrorism Incidents by Year: Analyzed the distribution of incidents over different years.
Terrorism Incidents by Country: Identified and sorted countries by the number of terrorism incidents.
Happiness Report Exploration: Examined the relationship between GDP per capita and happiness scores.
Attack Type Analysis
Distribution of Attack Types: Explored the frequency and types of attacks.
Number of Incidents by Attack Type: Created a bar plot showing the number of incidents for each attack type.
Heatmap of Region vs. Attack Type: Visualized the relationship between regions and attack types using a heatmap.
Merging and Analysis
Merge Terrorism and Happiness Data: Combined the terrorism and happiness datasets on the country column to enable joint analysis.
Correlation Analysis: Examined correlations between happiness scores and the number of terrorist incidents.
Pivot Table Creation: Generated a pivot table to summarize average happiness scores and incident counts by country.
Results
Visualized terrorism incidents over time and across countries.
Analyzed attack types and their distribution.
Explored the relationship between economic factors and happiness scores.
Merged datasets to analyze the interaction between terrorism and happiness scores.
Conclusion
The analysis provides insights into global terrorism trends and their potential relationship with happiness scores. The visualizations and statistical analyses help in understanding regional patterns and temporal trends, offering valuable information for stakeholders.
