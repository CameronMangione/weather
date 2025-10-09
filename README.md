# Seattle Weather Project (This is a template README.md file that you can adapt to your project)

> This project analyzes differences in precipitation data between one station Seattle and a singular station in Pittsburgh.

---

## Project Overview

Provide a short and concise overview of the project. We are looking to solve the problem of knowing if it rains more in Seattle over a four year time period compared to another US city. We used precipitation data from NCEI in the timeframe of 01/01/2018-12/31/2022. **To be determined** the key outcomes or findings.

- **Objective:** Compare precipitation differences between two US cities between the time frame of 01/01/2018-12/31/2022.
- **Domain:** conservation/weather
- **Key Techniques:** Exploratory Data Analysis, Modelling, t-tests, z-tests data visualization (lineplots, barplots, histograms, boxplots))

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebook and Python script
├── reports/              # Generated two page with visualization signifance levels with mean monthly precipitation
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Link to the data source(s). [Seattle](data/seattle_rain.csv).  [Pittsburgh](data/pittsburgh_rain.csv).
- **Description:** Each dataset consists of precipitation data from the First Hill station in Seattle, and Pittsburhg International Airport in Pittsburgh.
- **License:** See Requirements file.

---

## Analysis

THe weather data was collected from the CCOA website, and was then imported into the JupyterLab workbook. From there, we analyzed the data and differences between the two datasets. 
We discovered that Seattle had 190 missing datapoints, and we needed to find a way to replace and update them.
To solve this issue, we imputated the missing datapoints by calculating the mean for each day of the year for Seattle, and applied the day of year mean to the Nan points in the dataset to clean the data.
We analyzed the data based on mean precipitation levels, the proportion of prercipitation per day in each city, and also calculated the five quartiles for median analysis in our boxplots.
---

## Results

Based on the results, Seattle experiences significantly more rainfall in November, December, and January, while Pittsburgh experiences significantly more rainfall from May through September. 

---

## Authors

- Cameron Mangione - [@CameronMangione](https://github.com/CameronMangione)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: See Requirements file.
- Tutorials or papers referenced
- Inspiration or collaborators
