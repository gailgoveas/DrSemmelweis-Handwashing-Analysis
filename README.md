# Handwashing and Mortality Rates Analysis

## Introduction

This project investigates the historical data from the Vienna General Hospital to highlight the impact of handwashing on mortality rates. The analysis focuses on the data collected by Dr Ignaz Semmelweis, which demonstrates a significant reduction in mortality rates after the introduction of hand hygiene practices in the mid-19th century.

## Methodology

### Data Acquisition
The datasets utilized in this project were obtained from historical records of the Vienna General Hospital, which cover the period between 1841 and 1849. These records were sourced from publicly available sources and reflect the impact of handwashing on mortality rates in obstetrical clinics.

### Data Preprocessing
Upon acquisition, the datasets underwent a preprocessing stage where the data were cleansed, normalized, and structured for analysis. The handling of missing values, parsing of dates, and calculating the monthly and annual proportions of deaths out of the number of births were carried out.

### Statistical Analysis
The following analyses were conducted using Python's data analysis libraries, namely Pandas for data manipulation and Matplotlib for visualization:
- **Time Series Analysis**: Monthly trends of mortality rates were plotted to assess the impact of handwashing over time visually.
- **Difference in Proportions**: The average difference in mortality rates before and after the handwashing policy was enacted was calculated to quantify the impact.
- **Bootstrap Analysis**: A bootstrap analysis was implemented to estimate the confidence in the results. This involved resampling the data to create numerous simulated samples, allowing the calculation of a 95% confidence interval for the mean difference in mortality rates due to the introduction of handwashing.

### Results
The visualizations clearly showed a drastic reduction in the proportion of deaths after the implementation of handwashing practices. The bootstrap analysis further supported this finding, providing statistical evidence of a significant decrease in mortality rates with high confidence.

### Conclusion
The historical data analysis conclusively demonstrates that handwashing was associated with substantially decreasing mortality rates due to puerperal fever. This strongly supports Dr. Semmelweis's hypothesis that hand hygiene is crucial in preventing disease spread in medical facilities.

### Contributing
Contributions to the analysis are welcome. Please fork the repository and submit a pull request with your changes.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.


