# Dedrone_intern

# Project Title: Analysis of Protest Activity in the United States
## Introduction
This project analyzes a dataset containing details about protest activities across the United States, focusing on aspects like geographical distribution, types and sub-types of protests, and the scale of events. The analysis provides insights into the patterns and characteristics of protests, including the influence of factors like location, population, and transportation accessibility.

## Data Preparation
- The dataset was loaded into a Pandas DataFrame for manipulation and analysis.
- Missing data in certain columns (actor2, assoc_actor_2, admin3) were addressed by deletion as they were inconsistently reported or irrelevant.
- The event_date column was converted to datetime format to facilitate time-series analysis.
## Analysis Overview
- Time Series Analysis: Examined the frequency of protests over time to identify trends and periodic patterns.
- Geographical Distribution: Utilized folium maps to visualize the distribution of protests across states, highlighting concentration near major cities and in states with larger populations.
  ![image](https://github.com/pomelogod/Dedrone_intern/assets/46542469/bf659e1c-e1e6-44f0-8b2c-e797ac9b4228)
  ![image](https://github.com/pomelogod/Dedrone_intern/assets/46542469/7b697799-d97a-4991-a628-3b044a052c21)
- Categorization of Protests: Analyzed the types, sub-types, and sources of protests, revealing a predominance of peaceful demonstrations primarily reported by local media.
- Comparative Analysis: Studied the ratio of rioters in major states, the reasons for protests, and the size of protests, particularly focusing on peaceful versus rioter protests and the impact on safety.
## Key Insights
- No significant time-based pattern in the frequency of protests was found, possibly due to data volume limitations.
- Protests are more likely to occur in populous and developed states like California, New York, and Florida, often near major transportation routes.
- Black Lives Matter activists, students, labor representatives, and women are the main participants in these protests.
- Protests with large numbers of participants, particularly those involving rioters or resulting in casualties, tend to be more dangerous.
## Usage
- This analysis can help in understanding the dynamics of protest activities and in planning and managing public safety measures.
- The datasets and scripts used in this analysis are provided in this repository. To replicate the analysis, follow the steps described in the accompanying Jupyter notebooks.
## Dependencies
- Python
- Pandas
- Folium
- Matplotlib
## Contributors
- Longsheng Xie
## Acknowledgements
- The dataset used in this analysis was sourced from public records of protest activities in the United States.
- Special thanks to Kaggle user Chandan Charchit Sahoo for the guide on using folium for map visualizations.
- Special thanks to https://realpython.com/python-nltk-sentiment-analysis/ for basic NLP.
