# Insurance Charges Python Analysis

## Project Overview

This Python project analyses medical insurance customer data to explore which demographic and health-related factors influence insurance charges.

The analysis focuses on customer characteristics such as age, sex, BMI, number of children, smoking status and region to identify patterns in medical insurance costs.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Dataset

The dataset contains 1,338 rows and 7 columns, including:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges

## Project Steps

- Loaded and inspected the dataset using Pandas
- Reviewed data types and summary statistics
- Checked for missing values
- Removed one duplicate row
- Created new columns for BMI Category and Age Group
- Analysed insurance charges across customer groups
- Created visualisations to explore patterns and relationships
- Produced business recommendations based on the findings

## Key Insights

- Smoking status showed the clearest difference in insurance charges, with smokers having noticeably higher charges than non-smokers.
- Age had the strongest positive correlation with insurance charges among the numerical variables.
- BMI appeared to influence charges, especially at higher BMI values, although the relationship was stronger when considered alongside other factors.
- Region and number of children showed some variation, but appeared to have a weaker impact compared with smoking status, age and BMI.

## Business Recommendations

- Use smoking status as a key pricing risk factor.
- Consider age-based risk trends when reviewing insurance policies.
- Offer wellness support for customers with higher BMI to help reduce future risk.

## Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- Feature engineering
- Grouping and aggregation
- Data visualisation
- Correlation analysis
- Business insight generation
- Communicating findings through a written report

## Files Included

- `insurance-charges-analysis.ipynb` - Jupyter Notebook containing the Python analysis
- `insurance-charges-analysis-report.pdf` - final presentation/report of findings
- `insurance.csv` - dataset used for the analysis
- `README.md` - project overview and summary
