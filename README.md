# US-Wildfires-Project
Wildfire Analysis and Insights in the US (1992-2015)
Overview
Wildfires are among the most destructive natural disasters in the United States, burning millions of acres, destroying thousands of properties, and even claiming lives annually. This project analyzes US wildfires from 1992 to 2015, aiming to provide insights on their causes, geographical patterns, and trends. These findings can help define recommendations to improve public safety and reduce future wildfire damage.

Objectives
Trend Analysis:

Has the number of wildfires increased over time?
What is the average destruction caused each year, and how has it changed?
Fire Size Analysis:

Breakdown of wildfire occurrences by size class (A to G).
Number of fires per size class annually.
Geographical Impact:

Which states are most and least prone to wildfires?
Cause Identification:

Analyze the various causes of wildfires over time.
Dataset
The data is sourced from Kaggle, containing records of wildfires in the US from 1992 to 2015.

Data Dictionary:
FOD_ID: Global unique identifier for the fire.
FIRE_YEAR: Year the fire was discovered.
FIRE_SIZE: Acres affected by the fire.
STATE: US state where the fire occurred.
STAT_CAUSE_DESCR: Description of the fire’s cause.
FIRE_SIZE_CLASS: Size classification (A-G) based on the area burned.
And many more fields related to fire incident reporting.
Project Structure
1. Data Preparation
Basic error-checking, removal of redundant records, and filtering out data for size classes A and B to optimize dataset size.
2. Exploratory Data Analysis (EDA)
Statistical analysis of historical wildfire data to answer the targeted questions.
Key Findings
The number of wildfires and the extent of destruction tend to increase every 4-5 years.
Human activities are a significant contributor to the majority of wildfires, highlighting the need for stricter guidelines in fire-prone areas.
Useful Links
Final Report Notebook
EDA Notebook
Pandas DataFrame isin
Pandas DataFrame replace
Pandas Pivot Table
Pie Plot
Conclusion
Wildfires are becoming more frequent and destructive over time. The majority of fires are caused by human activities, calling for stricter enforcement of guidelines in forest zones to prevent future disasters.

Acknowledgements
This dataset was collected using funding from the U.S. Government. If you use this data in any publication or research product, please cite:
Short, Karen C. 2017. Spatial wildfire occurrence data for the United States, 1992-2015 [FPAFOD20170508]. 4th Edition. Fort Collins, CO: Forest Service Research Data Archive. DOI:10.2737/RDS-2013-0009.4.
