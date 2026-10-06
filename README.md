# Comparing rainfall in Seattle, WA and Charlotte, NC

> This project analyzes weather patters between Seattle, WA and Charlotte, NC.

---

## Project Overview

This project compares historical weather data from Seattle and Charlotte with a focus on precipitation. We will be comparing rainfall frequency, seasonal variations, as well as overall precipitation. We will be looking at the data set to find if Seattle or Charlotte gets more rain.

- **Objective:** We are analyzing precipitation data from Seattle, Washington and Charlotte, North Carolina. Does Seattle receive more precipitation or is it the other way around? We will try to answer how precipitation differ in terms of volume of precipitation, and frequency. Additionally, we can also review When it rains, how much rain tends to fall in both cities.   
- **Domain:** Climate Sceince, Precipitation
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

- **Source:** We will be using data from [NOAA website site](https://www.ncei.noaa.gov/cdo-web/datasets).
- **Description:** We downloaded precipitation data from Seattle's airport (SEA-TAC) as well as Charlotte's Airport (Charlotte Douglas) between 2018 and 2022. The dataset contains categorical data like Station, Name, and Date. Finally, the measures included were Precipitation, Snow fall and "SNWD". We recieved a total of 1826 rows for both locations. This means we received 5 years worth of data (365*5 + 1). Data types received are string and float. 
- **License:** (if applicable)

---

## Analysis

Describe the notebooks and/or scripts used to perform the analysis. Specify the order in which the code should be run to reproduce the results.
Run code/Weather_Project_SEA_CHA.ipynb file. 
---

## Results

Include a short discussion of the findings and what they imply.

---

## Authors

- Binay Raut - [@binay8](https://github.com/binay8)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Python libraries used include pandas, matplotlib.pyplot, numpy, seaborn, and scipy 

