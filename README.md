#### Case-study-BlueSkyAnalytics
 
# **COVID-19 Impact on Enviroment**

Covid-19 has spread across the world and has affected 213 countries to more than 5 million people. As in 21st Century, Enormous efforts are in place to restore environmental standards. The study says Covid-19 led to a drop in pollution across the world. the Contingency measure has improved air and water quality, clean beaches, and environmental noise reduction.
so, we will study this factor in Detail.

The air around is made up of many gases and particles - Each so Small, for the most part, They're invisible to naked Eyes. 
    Yet they can Cause enormous health issues and Different countries across The World Where Facing health challenges due to the spread of COVID-19. Hence, in this notebook, we are going to explore the impact on air quality due to Covid-19.

**The Data used Contain following Feature**
- PM2.5/PM10 - It represents the value of particulate matter measured
- NO
- NO2
- NOx 
- NH3
- CO
- SO2
- O3
- Benzene
- Toluene
- Xylene
- AQI - Measure of Air quality index. 


    ### **Data**
- **Google Earth Engine-Sentinel-5P OFFL NO2: Offline Nitrogen Dioxide:** [GEE](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_OFFL_L3_NO2) This dataset provides offline high-resolution imagery of NO2 concentrations.
- **Google Earth Engine- Tropomi**
- **NOAA CDR AVHRR NDVI: Normalized Difference Vegetation Index, Version 5**
- **Air Quality Data :** [Kaggle](https://www.kaggle.com/rohanrao/air-quality-data-in-india ) or we can also get it from [CPCB](https://app.cpcbccr.com/ccr/#/caaqm-dashboard-all/caaqm-landing)

### **What is AQI ?**
Think of the AQI as a yardstick that runs from 0 to 500. The higher the AQI value, the greater the level of air pollution and the greater the health concern. For example, an AQI value of 50 or below represents good air quality, while an AQI value over 300 represents hazardous air quality.

The Official Scale Provided by the government is as Follows

![AQI](https://www.extremetech.com/wp-content/uploads/2018/11/Range-of-AQI-values-for-the-USA.jpg)

**What is the Impact of poor air Quality ?**
- The World's Greatest Environmental Threat to Health

Official statistics from the World Health Organisation state that 92% of us live in areas where air pollution exceeds the guidelines considered to be safe, 9/10 people breathe polluted air each day. The average number of deaths caused by air pollution in India was over 1.66 million in 2019.

- Huge Economic Cost 

The cost of air pollution to the global economy is huge. According to the World Bank, it costs us $5 trillion each year in welfare costs and $225 billion in lost income. Air pollution is so detrimental to national and global economic health that the UN created a new Wealth Index which factors the economic burden of air pollution on national economies. 

### **Region Focused** 
The Focus of this analysis will be on The National Capital Territory (NCT) of Delhi which is a massive metropolitan area in the country north.

