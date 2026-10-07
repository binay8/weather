# Comparing rainfall in Seattle, WA and Charlotte, NC

> This project analyzes precipitation patterns in Seattle, WA and Charlotte, NC.

---

## Project Overview

This project compares historical weather data from Seattle and Charlotte with a focus on precipitation. We will be comparing rainfall frequency, seasonal variations, as well as overall precipitation. 

- **Objective:** We are analyzing precipitation data from Seattle, Washington and Charlotte, North Carolina. Does Seattle receive more precipitation or is it the other way around? We will try to answer how precipitation differ in terms of volume of precipitation, and frequency. Additionally, we can also review When it rains, how much rain tends to fall in both cities.   
- **Domain:** Climate Science, Precipitation
- **Key Techniques:** Exploratory Data Analysis, Statistical Testing.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** We will be using data from [NOAA](https://www.ncei.noaa.gov/cdo-web/datasets).
- **Description:** We downloaded precipitation data from Seattle-Tacoma International Airport (SEA-TAC) as well as Charlotte  Douglas International Airport between 2018 and 2022. The dataset contains categorical data like Station, Name, and Date. Finally, the measures included were Precipitation, Snowfall and Snowdepth "SNWD". We recieved a total of 1826 rows for both locations. This means we received five-years worth of data (365 days * 5 years + 1 leap-day). Data types received are string (text) and float (numerical). 
- **License:** (if applicable)

---

## Analysis

This analysis was completed using the data science methodology to compare precipitation patterns between Seattle, WA, and Charlotte, NC.

General steps taken:
1. Download data from NOAA database
2. Investigate source data set to understand data structure, categories, data types, missing values.
3. Performed data cleansing by: removing unnecessary columns, updating data types, imputing missing values.
4. Converted data to tidy format
5. Calculated columns were added as needed. Specifically for month, day from datetime column.
6. Performed exploratory data analysis: bar charts to visualize mean, boxplots to view summary.
7. Deeper analysis to compare monthly mean precipitation as well as proportions days with precipitation between two cities. 
8. Statistical tests to assess observed differences in mean and proportions of days with rain between two cities were statistically significant

## Resources

- Name of file that performs the analysis: [Weather_Project_SEA_CHA.ipynb](https://github.com/binay8/weather/blob/master/code/Weather_Project_SEA_CHA.ipynb)

- Final clean dataset: [clean_seattle_charlotte_weather.csv](https://github.com/binay8/weather/blob/master/data/clean_seattle_charlotte_weather.csv)

- Report: [Report.docx](https://github.com/binay8/weather/blob/master/reports/Report.docx)

---

## Results

As far as amount of precipitation, based on the the dataset, Charlotte receives more average daily precipitation than Seattle. However, if we look at the proportions of days with precipitation, Seattle receives more precipiation days than Charlotte. A simple explaination is that Charlotte receives a greater amount of precipitation when it does rain as opposed to lower amount/consistent days of precipitation in Seattle. Finally, Seattle's precipitation is influenced by seasonal differences where they experience wet/dry patterns. Charlotte however, has a more consistent seasonal pattern. 

---

## Authors

- Binay Raut - [@binay8](https://github.com/binay8)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Python libraries used include pandas, matplotlib.pyplot, numpy, seaborn, and scipy 

