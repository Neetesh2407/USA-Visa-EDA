
# USA Visa EDA

This project focuses on conducting Exploratory Data Analysis (EDA) on a comprehensive USA visa dataset to uncover insights and patterns in visa applications and approvals.

## Overview

The USA Visa dataset contains detailed information about visa applications, including applicant demographics, job titles, visa types, and application outcomes. The aim of this project is to analyze the dataset to identify trends in visa approvals, refusals, and other factors influencing visa decisions.

## Dataset

- **Source**: [USA Visa Dataset](#)
- **Description**: The dataset includes information about visa applications submitted over several years, containing variables such as applicant details, employer information, job roles, wages, visa types, and decisions.

## Features

Some of the key features in the dataset include:
- **Case Status**: Outcome of the visa application (approved/denied).
- **Employer Name**: Name of the employer submitting the visa application.
- **Job Title**: Title of the job for which the visa is requested.
- **Wage**: Annual wage offered to the applicant.
- **Visa Class**: Type of visa applied for (H1B, etc.).
- **Year**: Year the application was submitted.

## Analysis Performed

1. **Data Cleaning**:
   - Handled missing values and duplicates.
   - Standardized column formats for analysis.
   - Filtered out irrelevant or incomplete records.

2. **Data Visualization**:
   - Bar charts showing visa approval vs. denial rates over time.
   - Distribution of wages by job title and visa class.
   - Popular employers requesting visa applications.
   - State-wise distribution of visa applications.

3. **Key Insights**:
   - Trends in visa approval rates over the years.
   - The impact of wage on visa approval.
   - Top job titles and employers requesting visas.
   - Popular states for visa applications and approvals.

## Tools & Libraries

- **Python**: The programming language used for the analysis.
- **Pandas**: For data wrangling and manipulation.
- **Matplotlib** and **Seaborn**: For visualizing trends and distributions.
- **NumPy**: For efficient numerical operations.

## Usage

To run the project locally, clone this repository and install the required dependencies:

```bash
git clone https://github.com/Neetesh2407/USA-Visa-EDA.git
cd USA-Visa-EDA
pip install -r requirements.txt
```

Run the Jupyter Notebook to explore the analysis:

```bash
jupyter notebook USA_Visa_EDA.ipynb
```

## Conclusion

This USA Visa EDA provides valuable insights into the factors that influence visa outcomes. Understanding these factors can help companies, individuals, and policymakers in their decision-making processes related to visa applications.

## Future Scope

- Deeper analysis of specific job roles and visa outcomes.
- Predictive modeling for visa approval based on key features.
- Exploration of visa trends over longer time periods.

## Author

- **Neetesh Kumar** - Data Scientist
