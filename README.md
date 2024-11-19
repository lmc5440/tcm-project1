# COVID-19 Vaccination Data Analysis

## Project Overview

This project investigates the relationship between COVID-19 new deaths and vaccination rates across four countries: the United States, India, Germany, and Indonesia.  The primary goal is to determine if higher vaccination rates correlate with lower mortality rates, providing insights for future pandemic preparedness.  

--- 
## PRESENTATION DESCRIPT
"The purpose is to investigate the relationship between COVID-19 new deaths and vaccination rates in four countries: the United States, India, Germany, and Indonesia. The study collects useful data and employs statistical analysis to determine whether lower mortality rates are connected with higher vaccination rates."

## Goals [from presentation] 

Investigating Data

Databases with COVID-19 cases, fatalities, and vaccinations should be cleaned and integrated. Concentrate on four nations: Indonesia, Germany, India, and the United States.

Testing Hypotheses

- Analyze whether fewer new deaths are associated with increasing vaccination rates.
- Look for notable variations in mortality between the pre- and post-vaccination periods.

Analysis of COVID Vaccination Over Time

- Examine patterns in vaccinations and death during the course of the outbreak.
- Utilize descriptive statistics to compile results by nation.

Making Insights Visible

- Make concise, comparative charts showing the number of new deaths and vaccinations by nation.
- Emphasize the importance of vaccinations in preventing pandemics.

## Questions [from presentation]

Questions

The Relationship
- Is there a significant correlation between daily vaccination rates and new deaths across various nations?

Regional Trends
- Which countries show differing trends in new deaths before and after vaccination efforts?
- What factors, such as population density and healthcare infrastructure, may account for these differences?

The Impact of Immunization
- How significantly did vaccinations decrease daily new deaths in the four focal countries?

## Sources of Data:
- The COVID-19 case and immunization data came from Kaggle datasets such as "COVID-19 Daily Updates" and "COVID-19 World Vaccination Progress," along with other related global datasets. These databases contain detailed records of COVID-19 immunization status and statistics by date and country.
- **Worldometer** provides World Population Data to normalize analysis by accounting for population discrepancies between countries.


## Actions Taken:

- **Integration of Datasets:**  
  To synchronize case and vaccination numbers, the COVID-19 case and vaccination data were combined using date fields and ISO country identifiers (for example, IND for India). Even if some dates' vaccination data was lacking, a left join was used to guarantee that all case data that was accessible was kept.

- **Data Purification:**  
  To guarantee the reliability of the analysis, null values were found and removed when needed. Appropriate imputations or interpolations were taken into consideration for missing data that could not be eliminated. To make merging and querying easier, inconsistent column names were standardized.

- **Data Conversion:**  
  By filtering rows according to ISO country codes, distinct data frames for Germany, Indonesia, India, and the USA were produced. Comparative study between the chosen nations was made possible by this methodology. To facilitate time-series analysis, data from every nation was indexed by date.

- **Verification and Preparation:**  
  To guarantee data integrity after cleaning, key statistics like mean, standard deviation, and record count were computed. Columns that had no bearing on the analysis were eliminated to make viewing and computation easier.

## Approach Taken 

### Push toward Exploratory Data Assessment (EDA):
- Envisioned designs in vaccination and destruction rates.

### Time Span Division:
- Disconnected data into:
  - Pre-vaccination: 2020-12-31 and earlier
  - Post-immunization: 2021-01-01 to 2021-06-01

### Genuine Examination:
- Decided mean, standard deviation, association coefficients, and blueprint experiences for key variables.

### Portrayal:
- Plotted examples and associations for daily vaccinations and new passings per country.

### Problems Encountered:
- Changing project focus midway due to lack of data (see addendum).

### Future Focus:
- Are there any discernible trends in immunization efforts and the effects they have on public health outcomes?


## Results and Conclusions

### Effects of Immunization
- Immunization efforts were largely responsible for the decrease in coronavirus transmissions from one side of the planet to the other. In nations with aggressive and early vaccination programs, passing rates decreased more quickly.

### Reasonability-related Elements
The effectiveness of immunization campaigns depends on:
- People's population: There were clear worries when people were thicker, like in Indonesia and India.

### Clinical Theory Foundation
Helped nations like Germany and the United States launch effective vaccination efforts, which led to additional results.

### Future Results
The information makes it very evident how important it is to distribute vaccines fairly and to have a proactive, prosperous structure in case of future pandemics. Continued interest in clinical concept frameworks and vaccination care initiatives is necessary for long-term success security.



## Results:
- Huge decrease in new deaths post-immunization across our examined nations.
- Positive relationship between normal vaccinations and the decrease of new deaths (e.g., USA: -0.67 relationship).


Depictions:
- plots in pre and post vaccination periods normal immunizations and deaths
- Disperse plots for relationship between new death and vaccination rates.

## Summmary 

Role of Vaccination: According to the statistics, vaccination rates significantly reduce the COVID-19 death rate. The strong correlation between increased vaccination efforts and fewer new deaths found in every country under study demonstrated the life-saving potential of vaccinations.

Global Variances: Because of variables including population density, healthcare systems, and vaccine distribution plans, immunization programs' effectiveness differed significantly amongst nations. Death rates declined more in wealthier countries—like the US and Germany—than in poorer ones, indicating shortages in healthcare resources.


--- 
  
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

# tcm-project1

[Google Slides Presentation](https://docs.google.com/presentation/d/1IpMftFHOCgYhkIwUz5A-0It0g4CQZYHFCIQwcNhRukQ/edit#slide=id.g315f01fec7a_0_427)


## Future Development



## Acknowledgements


