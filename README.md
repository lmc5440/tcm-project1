# COVID-19 Vaccination Data Analysis

## Project Overview

This project investigates the relationship between COVID-19 new deaths and vaccination rates across four countries: the United States, India, Germany, and Indonesia.  The primary goal is to determine if higher vaccination rates correlate with lower mortality rates, providing insights for future pandemic preparedness.  This analysis helps policymakers and medical professionals understand the impact of vaccination efforts and prepare for future public health emergencies.

## Key Questions

1. **Correlation:** Is there a statistically significant correlation between daily vaccination rates and new deaths in the selected countries?
2. **Regional Trends:** How do the trends of new deaths before and after vaccination efforts compare across the four countries? What factors (e.g., population density, healthcare infrastructure) might explain these differences?
3. **Impact of Vaccination:** To what extent did vaccinations reduce the daily number of new deaths in these countries? Are there discernible trends in vaccination and their effects on public health outcomes?

## Data Sources and Cleanup

* **COVID-19 Cases and Vaccinations:** Kaggle datasets ("COVID-19 in India," "COVID-19 World Vaccination Progress," and other global datasets).
* **Population Data:** Worldometer.

**Cleanup Process:**

1. **Data Integration:** COVID-19 case and vaccination data were merged using date fields and ISO country codes. A left join ensured all case data was retained.
2. **Data Cleaning:** Null values were handled through removal or imputation/interpolation. Inconsistent column names were standardized.
3. **Data Transformation:** Separate dataframes were created for each country using ISO country codes. Data was indexed by date for time-series analysis.
4. **Data Validation:** Key statistics (mean, standard deviation, record count) were calculated to ensure data integrity. Irrelevant columns were removed.


## Methodology

1. **Exploratory Data Analysis (EDA):** Visualizations were used to explore trends in vaccination and death rates.
2. **Time Period Division:** Data was split into pre-vaccination (before 2021-01-01) and post-vaccination (2021-01-01 to 2021-06-01) periods.
3. **Statistical Analysis:** Mean, standard deviation, correlation coefficients, and trend analyses were performed.
4. **Visualization:**  Daily vaccinations and new deaths per country were plotted to visualize patterns and correlations.

## Results

* **Vaccination Impact:** Vaccination significantly reduced COVID-19 transmissions and deaths, especially in countries with early and aggressive campaigns.
* **Regional Differences:** Vaccination program effectiveness varied due to population density, healthcare infrastructure, and vaccine access.  Wealthier nations (US, Germany) saw larger declines in death rates.
* **Correlation:** A positive correlation was observed between vaccination rates and a decrease in new deaths (e.g., -0.67 correlation in the US).  This suggests that higher vaccination rates are associated with fewer deaths.

**(Include visualizations here: Time-series plots of daily vaccinations and deaths pre- and post-vaccination, scatter plots showing correlation between new deaths and vaccination rates.  Label axes clearly and provide captions.)**




## Conclusions

* **Vaccination is Crucial:**  Rapid and widespread vaccination is essential for pandemic control and saving lives.
* **Policy Recommendations:**  Prioritize equitable vaccine distribution and strengthen global health systems.  Invest in healthcare infrastructure and foster international collaboration.
* **Further Research:** Analyze granular data (age, comorbidities, etc.) and long-term vaccine efficacy.  Examine policy challenges in low-vaccination countries.


## Installation and Usage

(Provide instructions on how to run your code, if applicable.  Specify any dependencies or required libraries.)

## Project Files

* `Project 1.pdf`: Project requirements document.
* `Presentation 1.pdf`: Project presentation slides.
* `Accounts.py`: Contains the `Account` class.
* `savings_account.py`:  Contains the `create_savings_account` function.
* `cd_account.py`: Contains the `create_cd_account` function.
* `customer_banking.py`: Main program file.


## Future Development



## Acknowledgements


