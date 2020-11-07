# Project Name
Victoria Electricity Demand Forecast After Pandemic

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to explore the chane of elctricity demand in Victoria after Covid-19 pandemic. Insights have been given to provide accountable future half-hourly electricity demand. 

### Methods Used
* Data Visualization
* Feature Engineering (Outlier Detection/Scaling/Feature Selection)
* Predictive Timeseries Modeling
* Machine Learning(Hyperparameter Tuning/Decision Tree/KNN/XGBoost)

### Technologies 
* Python
* Jupyter Notebook

## Project Description
The time range has been selected from 2016-01-01 to 2020-10-29. 
Used Jan 2016-Dec 2019 to predict the 2020 demand.
Inspired by 2020 AEMO Electricity Demand Forecasting Methodology Information Paper.



## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here] within this repo. 
   Features Raw Data have been extracted from public website and resources as below:
    -  Daily Max/Min temperature data
        max_temp:  [BOM:Daily Maximum Temperature of Station:Melbourne(Olympic Park)](http://www.bom.gov.au/jsp/ncc/cdio/weatherData/av?    
        p_nccObsCode=122&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=086338)\
        min_temp:   [BOM:Daily Minimum Temperature of Station:Melbourne(Olympic Park)](http://www.bom.gov.au/jsp/ncc/cdio/weatherData/av?
        p_nccObsCode=123&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=086338)\
    -  Victoria Day Length Records
       [Sunrise and Sunset in Melbourne](https://www.timeanddate.com/sun/australia/melbourne)
    -  Victoria Public Holidays in 2016-2020
       [2016-2020-Australia Public Holidays](https://data.gov.au/dataset/ds-dga-b1bc6077-dadd-4f61-9f8c-002ab2cdff10/details)
       
  Target Raw Data have been extracted from AEMO as below:
       [AEMO: VIC-30-Min Aggregated Price & Demand Data)](https://aemo.com.au/energy-systems/electricity/national-electricity-market-nem/data-nem/aggregated-
       data)

3. Data processing/transformation scripts are being kept [1_Data Extraction and Preprocessing.ipynb] within this repo.
4. Feature Engineering and Modelling are being kept [2_Feature Engineering and Modelling.ipynb] within this repo.



## Contact
* Linkedin: https://www.linkedin.com/in/yingxue-xue-shang-0828ab195/
* Tableau Public: https://public.tableau.com/profile/yingxue.shang#!/
* Medium: https://medium.com/@eirashang
* Wechat: giftdou
