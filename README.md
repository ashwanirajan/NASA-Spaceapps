# Pollution, Mortality Rate, Unemployment and Mobility: Bringing them all together

### Task: An Integrated Assessment
Your challenge is to integrate various Earth Observation-derived features with available socio-economic data in order to discover or enhance our understanding of COVID-19 impacts.

### Team
Nagendra Sastry, VP-Decision Analytics, EXL
Shubham Thakur, Consultant-1, EXL
Anuja Saini, Consultant-1, EXL
Ashwani Rajan, Consultant-1, EXL

### Summary
Pollution has been seen as a cause of higher mortality rate and as the parameter most positively impacted by Covid. We have tried linking the unemployment and mobility numbers to the number of cases as well.

### How We Addressed This Challenge
Our project tries to discover the relationship between pollution and mortality from Covid-19. Higher the pollution, higher is the incidence rate of people with respiratory problems and since Coronavirus attacks the respiratory system, mortality rate is higher.
Ironically, it is the same virus that has reduced the pollution indirectly through lockdown policies. We try to provide that insight.
We also try to find out the relationship between number of Covid deaths, unemployment claims and reduction in mobility.

### How We Developed This Project

#### Inspiration: 
Our main inspiration was to perform a preliminary analysis on a balanced approach to return to normalcy where we can look for alternative ways to restore urban and industrial areas while at the same time having a reduced air pollution level compared to previous years. We were also motivated to study Covid-19 lockdown’s impact on the lives of white to blue-collar employees in urban industries and the overall role of air quality on Covid-19 and vice versa.

#### Basic Approach: 

Direct and indirect relationship of various social-economic factors affected due to covid19 cases for different states of the U.S.
Explored and processed Air Quality data and Aerosol Optical Thickness(AOT) along with mobility and unemployment rate to visualize and address the socio-economic impact of lockdown due to the Covid-19 pandemic.
Providing solutions to the policymakers using the satellite data for the verification of the relationship.

#### Impact of Covid-19 lockdown on air quality:
We explored open-data like NASA Worldview and NASA air quality analysis to compare the Particulate matter emission from their pre-crisis levels as well as their impact on the mortality rate. Earthdata Giovanni was used for the time series analysis of Aerosol Optical thickness.

#### Impact of Air Quality on Mortality Rate:
Recent studies have shown the impact of prolonged exposure to atmospheric pollutants on the Covid-19 mortality rate. From our analysis on the 2019 annual 90th Percentile AQI value and mortality rate on the county level supports the above study. For each county taken in our study, the 90th Percentile AQI value gives an estimate of an Air Quality Index(AQI) value, which is greater than the daily AQI value for 90% of the days in the year 2019. Hence, this parameter can be considered a good indicator of the inhabitants’ prolonged exposure to pollutants for a particular county. When a heat map was generated for the 90th percentile AQI and county-wise mortality rate, we see many regions with high 90th percentile AQI to have high mortality rates as well. This is because prolonged exposure to atmospheric pollutants leads to an increase in the percentage of people with respiratory issues and such a population is more prone to SARI(Severe Acute Respiratory Illness) on being exposed to coronavirus or other influenza-like viruses.

#### Impact of Covid-19 on Unemployment and Mobility Rate:
Unemployment has seen a sudden rise(highest in 53 years) because of the direct impact of covid19 on transportation, tourism, small businesses, Retail business, shut down of factories, industries, etc. From our analysis, it has been also observed the mobility rates has significantly reduced in the regions which has highest death records of covid19 and as a result of lockdown imposed to bring down the covid19 increment cases, industries, factories, transportation and tourism, small businesses, etc. have been significantly affected due to Covid-19, resulting in a surge in the unemployment rate.

### Tools Used:
We mainly used Python, Tableau, and MS Excel and google colaboratory for our analysis.

### Challenges:
Being very new to GIS datasets, we faced some initial issues in getting used to the process of GIS data extraction and we lacked the GPU resources required for analysis of large image datasets.

### Project Demo
Presentation Slides:
https://docs.google.com/presentation/d/1h4altxDp3kqC_40P0VyQthjMvaT7oJUylIbU9mEtXHc/edit?usp=sharing
https://drive.google.com/file/d/1czKbxtR7nzmiZYDi0UdxDvq9YOP4oWlr/view?usp=sharing

Other Dashboards:
Impact of lockdown on Air Quality Link: https://go.nasa.gov/2XE3VaG
Impact of lockdown on Unemployment and Mobility Rate Dashboard: https://tabsoft.co/2XEZMU3

### Data & Resources
We used the following data sources for our analysis.
Earthdata Giovanni.
NASA Air quality analysis of the Covid-19 pandemic.
Earthdata Worldview.
Google Mobility data.
US Bureau of labor statistics.
CDC’s county-wise number of Covid-19 cases and deaths.

### Tags
#Visualization #Data_Analysis #Air_quality #Unemployment #NASA #GIS #Covid19 #MortalityRate #AQI

