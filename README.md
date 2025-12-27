## AIR-QUALITY-ASSESSMENT-IN-THE-CITY-OF-NEW-YORK-A-SPATIAL-AND-SEASONAL-ANALYSIS

# PHASE I
# Aim of the Project
* Conduct a comprehensive spatial and temporal analysis of air quality measurements across New York City.

* Quantify long-term trends in pollution exposure over multiple years.

* Identify and assess spatial disparities in pollution exposure among different geographic regions.

* Generate actionable insights to guide environmental policy decisions and inform targeted public health interventions.
  
#Problem Definition
Air pollution levels vary significantly across regions and seasons, yet the lack of clear insights into when and where pollutant concentrations peak limits timely preventive actions. Although air quality data is available, it remains underutilized for detecting trends and identifying vulnerable locations. Without systematic analysis, policymakers and communities cannot effectively plan interventions. Therefore, it is essential to evaluate spatial and temporal patterns in pollutant levels to address rising public health risks.

#About the dataset
Domain: Air quality monitoring and pollutant trends

Source URL: https://catalog.data.gov/dataset/air-quality

Data Type: Comma Separated Values

Rows: 18863

Columns: 11

The dataset columns include the names of pollutants, types of measures used, and units of measurement, all studied across various locations in New York City, both spatially and temporally.

Data Collected From:
An official website of the United States government.

Major Geographical Types included:

    *42 United Hospital Fund neighborhoods

    *Community District

    *United Hospital Fund 34

    *Borough

    *Citywide
    
#Steps Required:
1.Data Loading and Initial Overview
2.Data Pre-processing
3.Exploratory Data Analysis (EDA)
4.Visualizations
5.Insight Generation and Report

#PHASE II
#Dataset Loading and  Overview:
*Total no. of rows:18,862
*Total no. of columns:11 columns

#Data Quality Assessment:
*Count of non-null values: 18,862
*No duplicate columns are found.
*The dataset is consistent throughout.
*Range index: 0 - 18,861
*Datatype issues are found: The datatype of Start_Date is wrongly given as 'object' instead of 'datetime'.
*Memory usage: 1.6+MB

#Pollution data overview of New York City:
*Average of pollution data: 21.05
*Median value: 26.26
*Standard deviation: 23.56
*Minimum value of pollution data: 0.00
*Maximum value of pollution data: 424.70

#Data Pre-processing part Overview:
*The dataset is devoid of missing values.

*No duplicate rows are also not detected.

*Data type of Start_Date and Data Value are changed to datatime and int respectively.

*Also the the Pollution Data Values are rounded to the nearby integers.

*Pollution data values of Nitrogen Dioxide(NO2) and Ozone(O3) are filtered out.

*Data values are aggregated based on the name of pollutants, place names, geographic areas and time period.

#PHASE III

#Insights from Exploratory Data Analysis part:
*Air quality data values are predominantly concentrated between 0 and 50, with a notable peak around 25, and gradually decrease as they approach 100.

*Nitrogen dioxide and fine particles (PM2.5) each account for 33.6% of total pollution, followed by ozone at 11.2%. These form the majority of the pollution caused.

*The 42 United Hospital Fund (UHF) districts cover the majority of the geographical area of New York City.

*The period from 2005 to 2017, with special attention is given to seasonal variations in analysing pollution trends.

*High Bridge–Morrisania records the highest pollution level in New York city.

*Nitrogen dioxide and fine particles (PM2.5) are the major pollutants in High Bridge–Morrisania.

*Highest variability in pollution levels is observed in the 42 United Hospital Fund (UHF) districts

*UHF34 records more consistent pollutant data values.

*Asthma emergency department visits due to PM2.5, exhibit the greatest spread and highest extreme values.

*Fine particles (PM2.5) display a very tight and compact distribution.

*Asthma emergency department visits due to PM2.5 represent the largest health-related impact of pollution, with the trend showing a decrease from 2006 to 2017. In contrast, the other leading indicators display either increasing or static trends from 2007 to 2022.

*UHF42 and CD generally exhibit higher mean values for primary pollutants such as nitrogen dioxide (NO2) and fine particles (PM2.5).

#PHASE IV
#Documentation 
#Project Summary:
Analyzed a consistent New York City environmental dataset of 18,862 records. After resolving data types and filtering pollutants, the study identified key contributors and significant health-related trends.

#Recommendations:
#1.Prioritize "Hotspot" Interventions:
*Target High Bridge–Morrisania: Since this district records the city's highest pollution levels, implement hyper-local mitigation strategies such as "Green Zones," increased urban canopy (trees), and stricter building emission standards.
*Focus on UHF42 and CD: Given the higher mean values for primary pollutants in these areas, prioritize these districts for the electrification of public transit and commercial delivery fleets.
#2.Tackle the "Big Two" Pollutants:
*Aggressive PM2.5 and NO2 Reduction: Nitrogen dioxide and fine particles account for over 67% of total pollution. Policy should focus on the primary sources of these pollutants, such as heavy-duty vehicle exhaust and aging residential heating systems.
#3.Enhance Public Health Protection:
Asthma-Focused Alerts: Since PM2.5-related asthma emergency visits show the highest extreme values, develop a more sensitive public notification system for "high-risk" days, specifically targeting vulnerable populations in UHF districts.
#4.Adaptive Monitoring and Seasonal Planning:
*Seasonal Mitigation Strategies: Since pollution trends fluctuate by season, the city should adjust its "Clean Air" initiatives.
*District-Specific Monitoring:In the 42 UHF districts where variability is high, deploy mobile monitoring units to catch transient spikes.In UHF34, where data is consistent, maintain long-term stationary sensors.




















