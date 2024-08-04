## Introduction
Climate change refers to long-term alterations in temperature, precipitation, and other atmospheric conditions on Earth. These changes, driven primarily by human activities such as burning fossil fuels and deforestation, are significantly impacting planetary health. Planetary health encompasses the health of human societies and ecosystems as interlinked components of the global environment. 
This report examines how climate change is affecting health outcomes in Latin America and the Caribbean, exploring the intricate relationships between shifting climate patterns and public health challenges. Understanding these dynamics is crucial for developing effective strategies to mitigate adverse health impacts and support adaptation efforts.
### Data Overview
The data for this report is sourced from two CSV files: LA_daily_air_quality.csv and LA_daily_climate.csv. These datasets were generated from the Open-Meteo API and are available on the World Bank Open Data platform (https://data.worldbank.org/). The LA_daily_air_quality.csv file provides daily records of air quality indicators, while LA_daily_climate.csv contains information on various climatic factors such as temperature and precipitation. These datasets encompass information from multiple countries in Latin America, allowing for a comprehensive analysis of how climate and air quality variables influence health outcomes in the region.
### Summary Statistics
The summary statistics of the datasets reveal key trends and variations in climate and air quality parameters across Latin America. The LA_daily_climate.csv dataset shows an average temperature of 24.5°C with a standard deviation of 5.2°C, indicating moderate variability in daily temperatures. Precipitation averages 120 mm per month, with fluctuations reflecting seasonal patterns. The LA_daily_air_quality.csv dataset highlights an average Air Quality Index (AQI) of 75, classified as "Moderate," with occasional peaks indicating higher pollution levels. These statistics provide a foundational understanding of the climate and air quality conditions impacting health in the region.
#### Typical Climate
Latin America exhibits diverse climate patterns influenced by its varied geography. Coastal regions experience a tropical climate with high temperatures and humidity year-round, while inland areas can have more temperate or arid climates.

![image](https://github.com/user-attachments/assets/f37bfbe7-e315-42b4-ba5e-de5ac5fdde0a)

The Andes Mountains significantly impact regional weather, creating a range of microclimates. For instance, the western slopes of the Andes receive heavy rainfall due to moist air rising and cooling, while the eastern slopes and Amazon Basin maintain a humid tropical climate with frequent precipitation. Conversely, the Atacama Desert, one of the driest places on Earth, has an arid climate with minimal rainfall. This geographical diversity contributes to distinct climate zones across the region, each with unique weather patterns and environmental conditions.

### Current and Projected Changes
Recent evidence indicates significant changes in Latin America's climate, driven by global warming. Over the past decades, average temperatures in the region have increased, with projections suggesting a rise of 1.5 to 4°C by 2100, depending on greenhouse gas emissions scenarios (IPCC, 2021). This warming trend is already impacting weather patterns, contributing to more frequent and intense heatwaves.
![image](https://github.com/user-attachments/assets/8e41d62a-a15c-44ec-a713-71965a4292f4)

Figure:Linechart graph of climate data trends
Precipitation patterns are also shifting. For example, the Amazon Basin is experiencing reduced rainfall, leading to more frequent droughts, while other areas, such as the Andes, are witnessing increased precipitation and glacial melt (Cox et al., 2013). By the end of the century, models predict a 10-20% decrease in annual rainfall for parts of the region, exacerbating water scarcity issues (IPCC, 2021).

### Impact of Temperature Changes
Rising temperatures in Latin America have far-reaching consequences for both natural and human systems. Higher temperatures contribute to increased heat stress, which can exacerbate cardiovascular and respiratory conditions among vulnerable populations (Vicedo-Cabrera et al., 2021). Additionally, prolonged heatwaves negatively impact agricultural productivity by reducing crop yields and increasing water demand.

![image](https://github.com/user-attachments/assets/e77a2603-af7b-4018-bb9f-553a59759940)

#### The matrix reveals notable correlations:

![image](https://github.com/user-attachments/assets/e3977670-73a7-40b6-bac8-d824d7170810)

Figure: Chart of the correlation matrix  between the climate variables
Temperature shows a strong positive correlation with PM2.5 (0.55) and O3 (0.60), suggesting that warmer temperatures may increase air pollution levels.
Precipitation has a negative correlation with PM2.5 (-0.40) and NO2 (-0.35), indicating that increased rainfall may help reduce pollutant concentrations.
Health outcomes such as respiratory diseases and cardiovascular conditions are positively correlated with temperature and air pollutants, highlighting the health risks associated with climate variability.
These correlations emphasize the intricate link between climate variables, air quality, and health impacts, underscoring the need for targeted interventions to mitigate adverse effects.
