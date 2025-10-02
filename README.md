# Seattle Weather Project (This is a template README.md file that you can adapt to your project)

> This project analyzes differences in precipitation data between one station Seattle and a singular station in Pittsburgh.

---

## Project Overview

Provide a short and concise overview of the project. We are looking to solve the problem of knowing if it rains more in Seattle over a four year time period compared to another US city. We used precipitation data from NCEI in the timeframe of 01/01/2018-12/31/2022. **To be determined** the key outcomes or findings.

- **Objective:** Compare precipitation differences between two US cities between the time frame of 01/01/2018-12/31/2022.
- **Domain:** conservation/weather
- **Key Techniques:** (e.g., Regression, Classification, Clustering, NLP, Time Series)

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

- **Source:** Link to the data source(s). [Seattle](data/seattle_rain.csv).  [Pittsburgh](data/pittsburgh_rain.csv).
- **Description:** Brief overview of the dataset features, size, and format
- **License:** (if applicable)

---

## Analysis

THe weather data was collected from the CCOA website, and was then imported into the JupyterLab workbook. From there, we analyzed the data and differences between the two datasets. 
We discovered that Seattle had 190 missing datapoints, and we needed to find a way to replace and update them.
To solve this issue, we imputated the missing datapoints by calculating the mean for each day of the year for Seattle, and applied the day of year mean to the Nan points in the dataset to clean the data.

---

## Results

Include a short discussion of the findings and what they imply.

---

## Authors

- Your Name - [@yourhandle](https://github.com/yourhandle)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
