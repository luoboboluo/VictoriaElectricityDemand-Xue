# Project Name
**Victoria Electricity Demand Forecasting During Covid-19**

####  Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to explore the electricity demand change in Victoria after Covid-19 pandemic. Insights have been given to provide accountable future half-hourly electricity demand as below:

**Exploratory Data Analysis:**

* Hourly demand profile indicates that due to Covid-19,there is a late morning peak hour from 7 amm to 9 am. 
  Followed with an apparent demand drop down during peak hours 9 am to 18 pm. 
  At night, the peak demand is a little higher than previous years.
 
<p align="center"> 
<img width="436" alt="VIC2016-2020 Daily Profile" src="https://user-images.githubusercontent.com/48660936/98435747-a1fcb100-2129-11eb-95e1-02743a448041.png">
</p>


**Forecast Precision:**

**Hourly Demand Forecast by Tuned XGBoost**

<p align="center"> 
<img width="637" alt="Tuned XGBosst-half-hour" src="https://user-images.githubusercontent.com/48660936/98435817-5b5b8680-212a-11eb-9c1a-c0821f0ce6e0.png">
</p>

**Daily Demand Forecast by Tuned XGBoost**

<p align="center"> 
<img width="651" alt="Tuned XGBosst-DailyDemand" src="https://user-images.githubusercontent.com/48660936/98435834-7928eb80-212a-11eb-8f95-6dc0f7b352d4.png">
</p>

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

- Data exploration/descriptive statistics
- Data processing/cleaning
- Statistical modeling

## Getting Started

**1. Data Resources:**
   **Target Raw Data have been extracted from AEMO as below:**
       [AEMO: VIC-30-Min Demand Data](https://aemo.com.au/energy-systems/electricity/national-electricity-market-nem/data-nem/aggregated-data)
   
   **Features Raw Data have been extracted from public website and resources as below:**
    -  Daily Max/Min temperature data
       [Melbourne Maximum Daily Temperature Data](http://www.bom.gov.au/jsp/ncc/cdio/weatherData/avp_nccObsCode=122&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=086338)/
       [Melbourne Minimum Daily Temperature Data](http://www.bom.gov.au/jsp/ncc/cdio/weatherData/avp_nccObsCode=123&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=086338) /
     - Victoria Day Length Records
       [Sunrise and Sunset in Melbourne](https://www.timeanddate.com/sun/australia/melbourne)/
      - Victoria 2016-2020 Public Holidays
       [2016-2020-Australia Public Holidays](https://data.gov.au/dataset/ds-dga-b1bc6077-dadd-4f61-9f8c-002ab2cdff10/details)/
       
**3. Data processing/transformation scripts are being kept [1_Data Extraction and Preprocessing.ipynb] within this repo.**
**4. Feature Engineering and Modelling are being kept [2_Feature Engineering and Modelling.ipynb] within this repo.**



## Contact
* Linkedin: https://www.linkedin.com/in/yingxue-xue-shang-0828ab195/
* Tableau Public: https://public.tableau.com/profile/yingxue.shang#!/
* Medium: https://medium.com/@eirashang
* Wechat: giftdou
