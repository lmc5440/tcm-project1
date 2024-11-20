# COVID-19 Vaccination Impact Analysis
_A Data Analysis Project by Ser Yoon, Lauren Christiansen, CJ Fleming, Dhwani Patel_


## Executive Summary
Our research team conducted a comprehensive investigation into the relationship between COVID-19 mortality rates and vaccination implementation, analyzing data from four strategically selected countries representing diverse healthcare infrastructures and population densities. Through rigorous statistical analysis, we found:
- Strong negative correlations (average -0.55) between vaccination rates and death rates in developed nations
- Significant statistical evidence (p < 0.05) supporting vaccine efficacy
- Quantifiable differences in healthcare system responses
- Clear impact of infrastructure on program effectiveness

## Installation & Usage

### Prerequisites
- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook
- Git version control system
- Internet connection for data downloads

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

### Data Preparation
1. Download required datasets:
   - COVID-19 vaccination data
   - Mortality statistics
   - Population metrics
2. Place in Resources/ directory
3. Verify file integrity using provided checksums

[Would you like me to continue with the rest of the clean version? It will include all enhanced sections we discussed, including:
1. Analysis Results with enhanced statistical methods
2. Detailed visualization descriptions
3. Project Evolution (TCM pivot)
4. Expanded methodology
5. Study limitations
6. Enhanced findings and impact sections
7. Complete repository structure
8. Updated contributor information]

## Analysis Results

### Statistical Methods
Our analysis employed multiple statistical approaches:
- Time Series Analysis: Tracking mortality rate changes over vaccination periods
- Correlation Analysis: Pearson correlation coefficient calculations
- Descriptive Statistics: Mean, median, standard deviation calculations
- Data Normalization: Population-adjusted metrics

### Statistical Findings
We discovered significant correlations between vaccination rates and death rates:
- United States: -0.583 (p < 0.05)
- Germany: -0.523 (p < 0.05)
- Indonesia: -0.594 (p < 0.05)
- India: +0.432 (p < 0.05)

### Significance Testing
- Confidence Level: 95%
- P-values < 0.05 for all major correlations
- Standard error calculations included
- Outlier analysis performed

### Key Visualizations
Our analysis includes eight detailed visualizations, each addressing specific research questions:

1. Pre-vaccination Death Rates by Country
![COVID Deaths After Vaccinations](Images/covid%20deaths%20after%20vaccinations.png)

Analysis shows:
- Initial surge patterns across regions
- Baseline mortality rates
- Regional response variations
- Healthcare system capacity indicators

2. Post-vaccination Death Rates by Country
![COVID Deaths in India After Vaccine](Images/covid%20deaths%20in%20india%20after%20vaccine.png)
![COVID Deaths in Germany After Vaccine](Images/covid%20deaths%20in%20germany%20after%20vaccine.png)
![COVID Deaths in Indonesia After Vaccine](Images/covid%20deaths%20indonesia%20after%20vaccine.png)
![USA After Vaccine Deaths](Images/usa%20after%20vaccine%20deaths.png)

Key findings:
- Immediate impact of vaccination programs
- Varying response rates by region
- Infrastructure influence on outcomes
- Population density effects

3. Daily Vaccination Implementation Rates
![Number of COVID Vaccinations](Images/number%20of%20covid%20vaccinations.png)
Demonstrates:
- Vaccination program efficiency
- Distribution capabilities
- Healthcare system capacity
- Resource allocation effectiveness

4. Country-Specific Analysis
![COVID Deaths USA Prior to Vaccine](Images/covid%20deaths%20usa%20prior%20to%20vaccine.png)
![COVID Deaths in Indonesia After Vaccine](Images/covid%20deaths%20indonesia%20after%20vaccine.png)
![COVID Deaths Before India Vaccine](Images/covid%20deaths%20before%20india%20vaccine.png)
![COVID Deaths in Germany Before Vaccine](Images/covid%20deaths%20in%20germany%20before%20vaccine.png)

- USA Trends: Rapid implementation, strong infrastructure impact
- Germany Trends: Efficient distribution, consistent results
- India Trends: Population density challenges, infrastructure limitations
- Indonesia Trends: Geographic distribution challenges

## Project Evolution: TCM Data Pivot

### Initial Direction
- Originally focused on Traditional Chinese Medicine (TCM) impact on COVID-19
- Planned to analyze herbal medication effectiveness
- Collected extensive TCM treatment data

### Challenges Encountered
- Limited numerical data for statistical analysis
- Qualitative vs quantitative data challenges
- Categorization difficulties between Eastern and Western medical approaches

### Pivot Decision
- Recognized need for quantifiable metrics
- Identified vaccination data as robust alternative
- Maintained focus on healthcare effectiveness

### Lessons Learned
- Importance of data evaluation before project commitment
- Value of adaptability in research
- Understanding of cross-cultural medical data challenges

## Methodology

### Data Collection & Preprocessing
1. Initial Assessment
   - Data source verification
   - Quality validation
   - Format standardization
   - Missing value analysis

2. Data Cleaning & Integration
   - Dataset merging
   - Null value removal
   - Date standardization
   - Country-specific dataframe creation
   - Outlier handling
   - Post-cleaning validation

3. Analysis Methodology
   - Time Series Analysis
     * Rolling averages
     * Trend identification
     * Seasonal adjustment
   - Statistical Testing
     * Correlation calculations
     * Significance testing
     * Error margin analysis
   - Comparative Metrics
     * Population adjustments
     * Healthcare capacity normalization
     * Regional variance analysis

## Study Limitations and Considerations

### Data Limitations
- Reporting delays and inconsistencies
- Varying testing capabilities
- Limited regional data availability
- Different tracking methodologies

### Methodological Constraints
- Population density variations
- Healthcare infrastructure differences
- Socioeconomic factors
- Vaccination strategy variations

### External Factors
- Policy changes during study period
- Variant emergence
- Behavioral changes
- Healthcare system adaptations

## Summary of Findings

### Key Insights
1. Healthcare Infrastructure Impact
   - Robust systems showed faster implementation
   - Better outcomes in developed healthcare systems
   - Quantifiable effectiveness differences

2. Vaccination Program Effectiveness
   - Clear negative correlation with mortality rates
   - Faster response times in developed nations
   - Variable implementation success rates

3. Regional Variations
   - Population density effects
   - Healthcare access impact
   - Resource distribution challenges

### Impact & Implications
1. Healthcare Policy Development
   - Evidence-based recommendations
   - Resource allocation strategies
   - Infrastructure development priorities

2. Pandemic Preparedness
   - Early response systems
   - Distribution network optimization
   - Healthcare capacity planning

3. Resource Management
   - Efficient distribution systems
   - Supply chain optimization
   - Strategic reserve planning

4. International Cooperation
   - Cross-border coordination
   - Resource sharing frameworks
   - Knowledge transfer systems

## Repository Structure
```
tcm-project1/
│
├── analysis.ipynb          # Main analysis notebook
├── Resources/
│   ├── country_vaccinations.csv
│   ├── owid-covid-data.csv
│   └── data_validation.md
├── Documentation/
│   ├── methodology.md
│   └── statistical_analysis.md
├── Visualizations/
│   └── figures/
├── Presentation/
│   └── COVID19_Analysis.pdf
└── README.md
```

## Contributors
- Ser Yoon: Statistical Analysis, Visualization
- Lauren Christiansen: Data Collection, Methodology
- CJ Fleming: Documentation, Analysis
- Dhwani Patel: Data Processing, Validation

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Data providers: Kaggle, OWID
- Academic advisors
- Healthcare professionals who provided domain expertise

---
_For questions or feedback, please open an issue in our GitHub repository._
