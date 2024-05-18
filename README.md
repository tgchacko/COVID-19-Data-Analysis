# COVID-19-Data-Analysis with Python

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Description](#data-description)
- [Tools](#tools)
- [EDA Steps](#eda-steps)
- [Forecasting for Confirmed Cases](#forecasting-for-confirmed-cases)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)


### Project Overview

The objective of this project is to analyze the COVID-19 dataset to extract meaningful insight. This analysis aims to help understand the spread of the virus and provide actionable insights for decision-makers.

### Data Sources

COVID-19 Data: The primary dataset used for this analysis is the covid_19.csv file, containing detailed information about COVID-19 cases globally.

[Covid 19 Dataset](https://github.com/tgchacko/COVID-19-Data-Analysis/blob/main/covid_19.csv)

### Data Description
The dataset `covid_19.csv` contains various columns including:
- **Date**: The date of the observation.
- **Country/Region**: The country or region of the observation.
- **Confirmed**: The number of confirmed cases.
- **Deaths**: The number of deaths.
- **Recovered**: The number of recoveries.

### Tools

- Python: Data Cleaning and Analysis

    [Download Python](https://www.python.org/downloads/)

- Jupyter Notebook: For interactive data analysis and visualization

    [Install Jupyter](https://jupyter.org/install)

#### Libraries
    
Below are the links for details and commands (if required) to install the necessary Python packages:
- **pandas**: Go to [Pandas Installation](https://pypi.org/project/pandas/) or use command: `pip install pandas`
- **numpy**: Go to [NumPy Installation](https://pypi.org/project/numpy/) or use command: `pip install numpy`
- **matplotlib**: Go to [Matplotlib Installation](https://pypi.org/project/matplotlib/) or use command: `pip install matplotlib`
- **seaborn**: Go to [Seaborn Installation](https://pypi.org/project/seaborn/) or use command: `pip install seaborn`
- **scikit-learn**: Go to [Scikit-Learn Installation](https://pypi.org/project/scikit-learn/) or use command: `pip install scikit-learn`
- **statsmodels**: Go to [Statsmodels Installation](https://pypi.org/project/statsmodels/) or use command: `pip install statsmodels`
- **pmdarima**: Go to [Pmdarima Installation](https://pypi.org/project/pmdarima/) or use command: `pip install pmdarima`
- **fbprophet**: Go to [Prophet Installation](https://pypi.org/project/fbprophet/) or use command: `pip install fbprophet`
- **tbats**: Go to [TBATS Installation](https://pypi.org/project/tbats/) or use command: `pip install tbats`

### EDA Steps:

EDA involved exploring the COVID-19 data to answer key questions, such as:

1) What is the overall trend of confirmed cases, deaths, and recoveries?
2) How do these trends vary by country/region?

### Forecasting for Confirmed Cases

Forecasting: Using the Prophet-Model to forecast future confirmed cases.

### Findings:

The analysis results are summarized as follows:

1) The number of confirmed cases has shown a significant upward trend, with noticeable peaks during certain periods.
2) The spread of the virus varies significantly by region, influenced by factors such as population density and government interventions.

![Confirmed_Cases1](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/0b6d8c03-5717-479c-8ec6-336bdb2ca6b2)

![Confirmed_Cases2](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/9bedea02-f877-49ca-b489-d7d0a02978c5)

![Confirmed_Cases3](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/357d2206-c196-4db2-9571-4155303a5a44)

![Confirmed_Cases4](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/b06822a2-f7f0-4ec7-a4ba-ea7eb2673b94)

![Confirmed_Cases5](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/0ce5ebae-b618-4b68-8db7-f11f7b1e20d9)

![Confirmed_Cases6](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/7bf5f4f3-44da-45b9-b403-4b30eb776ba3)

![Confirmed_Cases7](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/afb8ff89-0ebe-4f3d-a307-24e2badfead9)

![Confirmed_Cases8](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/c63b91ac-c20b-4f6d-883d-6ed73060b01b)

![Confirmed_Cases9](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/c3f094a7-7613-4b97-b053-e4db952f7410)

![Mortality](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/467e2ecd-c7dd-4126-a042-fabc08a558ed)

![Recovery](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/d276c3c2-3031-4de7-b114-a056e5fd46bf)

![Forecast](https://github.com/tgchacko/COVID-19-Data-Analysis/assets/169921893/e7fd386b-5679-4b02-88f5-07515c7e4e37)

### Recommendations

Based on the analysis, we recommend the following actions:

1) Implement targeted interventions in regions with rapidly increasing case numbers to contain the spread.
2) Continue monitoring environmental factors to understand their potential impact on the virus spread.
3) Utilize the forecasting model to plan resource allocation and healthcare responses more effectively.

### Limitations

1) Data Quality: Some data points may be inaccurate due to underreporting or delays in reporting.
2) Model Limitations: The models used may not capture all the complexities of the virus spread and may need continuous updating with new data.
3) External Factors: Other factors not included in the analysis, such as social behavior and political decisions, can significantly impact the results.

### Conclusion:

The COVID-19 Data Analysis and Forecasting project provides a comprehensive approach to understanding and predicting the spread of the COVID-19 virus. Through exploratory data analysis (EDA), and the application of Prophet time series forecasting model, we have gained valuable insights into the trends and factors influencing the pandemic. Key findings highlight significant upward trends in confirmed cases and regional variations in virus spread.

The forecasting models developed in this project offer actionable predictions for future confirmed cases, enabling more informed decision-making for resource allocation and intervention planning. Despite some limitations in data quality and model complexity, the analysis underscores the importance of continuous monitoring and model updating to capture the evolving dynamics of the pandemic.

In conclusion, this project not only enhances our understanding of COVID-19 but also equips decision-makers with the tools and insights needed to effectively combat the virus and mitigate its impact on society.

### References

1) COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University
2) Python for Data Analysis by Wes McKinney
3) Prophet: Forecasting at Scale by Facebook
