# COVID-19 Vaccination Data Analysis

## Project Overview

Our team conducted a comprehensive analysis investigating the relationship between COVID-19 mortality rates and vaccination implementation. We strategically selected four countries for our study: the United States, Germany, India, and Indonesia, allowing us to examine the impact across varying healthcare infrastructures and population densities.

In our analysis, we focused on comparing pre-vaccination data (through December 31, 2020) with post-vaccination periods (January 1, 2021 - June 1, 2021). Using statistical methods and data visualization, we discovered compelling correlations between vaccination rates and mortality rates.

Our key findings revealed strong negative correlations between vaccination implementation and death rates in most of our studied countries. We found correlation coefficients of -0.583 for the United States, -0.523 for Germany, and -0.594 for Indonesia. Notably, India showed a divergent pattern with a positive correlation of 0.432, which we attribute to its unique challenges with population density and healthcare infrastructure constraints.

Through our statistical analysis, we demonstrated that countries with robust healthcare systems (the United States and Germany) achieved more effective vaccination programs and faster reductions in mortality rates. Conversely, we observed that nations with higher population densities and limited healthcare infrastructure (India and Indonesia) faced more significant challenges in their vaccination implementation.  


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

## Project Files & Resources 

- [Google Slides Presentation](https://docs.google.com/presentation/d/1IpMftFHOCgYhkIwUz5A-0It0g4CQZYHFCIQwcNhRukQ/edit#slide=id.g315f01fec7a_0_427)
- https://github.com/lmc5440/tcm-project1/blob/3fa3f97102e816cf775aa793dc650569128ef428/Resources/country_vaccinations.csv
- https://github.com/lmc5440/tcm-project1/blob/3fa3f97102e816cf775aa793dc650569128ef428/Resources/owid-covid-data.csv
- https://github.com/lmc5440/tcm-project1/blob/3fa3f97102e816cf775aa793dc650569128ef428/analysis.ipynb

## Project Primary Resources 

1. COVID-19 World Vaccination Progress
   - Source: Kaggle
   - URL: https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress
   - File Used: country_vaccinations.csv
   - Access Date: 2021

2. Our World in Data COVID-19 Dataset
   - Source: Kaggle/OWID
   - URL: https://www.kaggle.com/datasets/owid/covid-19-data
   - File Used: owid-covid-data.csv
   - Access Date: 2021

All data processing steps and methodology can be found in our analysis.ipynb file. The complete analysis and visualization code is available in our GitHub repository.

For questions about our data sources or methodology, please open an issue in our GitHub repository.


## Future Development



## Acknowledgements

-- 

# draftreadme  

# COVID-19 Vaccination Impact Analysis
*A Data Analysis Project by Ser Yoon, Lauren Christiansen, CJ Fleming, Dhwani Patel*

## Project Overview
Our team investigated the relationship between COVID-19 mortality rates and vaccination implementation across four strategically selected countries. We analyzed pre-vaccination (through December 31, 2020) and post-vaccination periods (January 1, 2021 - June 1, 2021) to understand the impact of vaccination programs on mortality rates.

### Key Findings
- Strong negative correlations between vaccination rates and death rates in developed nations
- Significant variations in vaccination program effectiveness based on healthcare infrastructure
- Statistical evidence supporting vaccine efficacy in reducing mortality rates

## Installation & Usage

### Prerequisites
- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook

### Setup
1. Clone the repository:
```bash
git clone https://github.com/lmc5440/tcm-project1.git
cd tcm-project1
```

2. Install required packages:
```bash
pip install pandas matplotlib jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook analysis.ipynb
```

## Analysis Results

### Statistical Findings
We discovered significant correlations between vaccination rates and death rates:
- United States: -0.583
- Germany: -0.523
- Indonesia: -0.594
- India: +0.432

### Key Visualizations
Our analysis includes eight detailed visualizations:
1. Pre-vaccination death rates by country
2. Post-vaccination death rates by country
3. Daily vaccination rates comparison
4. Country-specific mortality trends
   - USA trends
   - Germany trends
   - India trends
   - Indonesia trends

## Data Sources
```
1. COVID-19 World Vaccination Progress
   Source: Kaggle
   File: country_vaccinations.csv

2. Our World in Data COVID-19 Dataset
   Source: Kaggle/OWID
   File: owid-covid-data.csv

3. World Population Data
   Source: Worldometer
```

## Methodology
1. Data Collection & Cleaning
   - Merged vaccination and mortality datasets
   - Removed null values
   - Standardized date formats
   - Created country-specific dataframes

2. Analysis Approach
   - Time series analysis
   - Correlation studies
   - Statistical summaries
   - Comparative analysis

## Summary of Findings
Our analysis revealed that countries with robust healthcare infrastructure demonstrated more effective vaccination programs and faster mortality rate reductions. The data shows a clear negative correlation between vaccination rates and death rates in most studied countries, with correlation coefficients averaging around -0.55 for developed nations.

### Impact
These findings provide valuable insights for:
- Healthcare policy development
- Pandemic preparedness planning
- Resource allocation strategies
- International cooperation frameworks

## Repository Structure
```
tcm-project1/
│
├── analysis.ipynb          # Main analysis notebook
├── Resources/
│   ├── country_vaccinations.csv
│   └── owid-covid-data.csv
├── Presentation/
│   └── COVID19_Analysis.pdf
└── README.md
```

## Contributors
- Ser Yoon
- Lauren Christiansen
- CJ Fleming
- Dhwani Patel

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
*For questions or feedback, please open an issue in our GitHub repository.*
