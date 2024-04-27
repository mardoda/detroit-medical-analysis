# Detroit Medical Center Dataset Analysis

## Introduction
This project involves the analysis of health datasets centered around the Detroit Medical Center, focusing on correlations between medical conditions, healthcare coverage, and demographic factors such as obesity rates by county and city. 

## Data Sources
- **Medical School Data**: Dataframe named `med_school_df`
- **Weather Data**: Dataframe named `weather_df`
- **Health Insurance Coverage**: [Dataset URL](https://data.detroitmi.gov/datasets/health-insurance-coverage-by-zip-code-tabulation-area)
- **Adult Obesity Rates**: [Dataset URL](https://datausa.io/profile/geo/detroit-mi#conditions_diseases)
- **US Cities, States, and Counties**: [Dataset URL](https://raw.githubusercontent.com/grammakov/USA-cities-and-states/master/us_cities_states_counties.csv)

## Data Cleaning
- **Combined Datasets**: Joined medical data with obesity and insurance data, aligning by zip code and county where possible.
- **Removed Anomalies**: Filtered out non-relevant data such as incorrect gender values and duplicate entries.

## Analysis Techniques
- **Correlation Studies**: Examined relationships between obesity rates and medical specialties, insurance coverage by race and city, and appointment frequencies influenced by patient demographics.
- **Specialty Focus**: Analyzed the distribution of medical specialties in six selected cities.
- **Weather Impact Analysis**: Investigated how weather conditions affect medical appointment cancellations.

## Key Insights
- **Obesity Correlation**: Higher obesity rates correlate with specific medical specialties like Comprehensive and Pediatrics, particularly in Saginaw.
- **Insurance Coverage**: Significant disparities in health insurance coverage were observed, with notable findings in racial distribution and coverage in Detroit.
- **Appointment Trends**: Weather conditions have a measurable impact on appointment attendance, especially in colder months.

## Visualization
- **Graphs and Charts**: Various visual representations were used to illustrate the findings, including correlations between race and medical specialties, and the impact of weather on appointment frequencies.

## Conclusion
The project provides valuable insights into how demographic and environmental factors affect healthcare access and outcomes. It highlights the need for targeted healthcare services and the potential benefits of integrating weather data into patient management systems.

