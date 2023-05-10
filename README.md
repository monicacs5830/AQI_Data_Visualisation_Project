# AQI_Data_Visualisation_Project
Title: Air Quality Across Countries in COVID-19

##### INTRODUCTION:
Air pollution, a significant environmental concern, has notable effects on public health, a fact that became even more crucial during the COVID-19 pandemic. This project focuses on understanding the impact of air quality on health, specifically within the context of the pandemic. We analyzed the air quality index (AQI) - which encapsulates pollutants like particulate matter (PM2.5 and PM10), nitrogen dioxide (NO2), sulphur dioxide (SO2), carbon monoxide (CO), and ozone (O3) - across seven key countries (Brazil, India, Italy, France, the United States, Canada, and China) from 2019-Q4 to 2022-Q4. The study aims to identify a possible trend in AQI affecting the number of COVID-19 cases in each country, thereby enhancing our understanding of the relationship between human activities and air pollution.

##### METHODOLOGY:
Our research was conducted using a variety of Python libraries, including pandas and numpy for data manipulation, and matplotlib, choropleth graphs, and animated bubble plots for data visualization. These tools allowed us to analyze and represent our data effectively, making our findings more accessible.

##### Guiding questions for our research included:

How was AQI distributed across countries during COVID (2019-Q4 to 2022-Q4)?
Which countries experienced a rise in AQI during the sampled duration, and which country and city had the highest pollution level?
What factors influenced AQI, and what is the correlation between different pollutants and AQI?
Was there a relationship between AQI and COVID-19 cases in each country during the pandemic?
We sourced our data from the Air Quality Open Data Platform and the World Health Organization's COVID-19 data on Kaggle. After data collection, we preprocessed the data to ensure it was clean and ready for analysis. This involved merging data, dropping unnecessary columns, and checking for missing values. We then calculated the AQI for each pollutant following the US-EPA 2016 standard.

##### RESULTS AND CONCLUSIONS:
Our data visualization revealed that the levels of pollutants significantly impact AQI, with PM2.5 emerging as the most critical factor. We found a correlation between the COVID-19 pandemic and air quality, with improvements observed during periods of lockdowns and travel restrictions. The animated scatter plot of AQI vs. cumulative COVID cases over time visually represented this relationship.

Despite the evident impact of air pollution on global health, it receives minimal attention in terms of global development aid. We hope our analysis raises awareness about the urgency of reducing AQI levels. The insights gained can guide policymakers and environmental organizations in developing strategies to improve air quality and manage pollution levels effectively.

##### FUTURE SCOPE AND RECOMMENDATIONS:
While our study provides meaningful insights, there is a need for more comprehensive research to unravel the complex relationship between air quality and COVID-19 transmission. This could involve controlled experiments or multivariate analysis to establish causality. Future studies should also consider factors like population density, public health measures, and socioeconomic status. Our study serves as a starting point for this critical research, emphasizing the role of data visualization in understanding and communicating complex environmental health data.





