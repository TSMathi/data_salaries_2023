# Data Science Job Salaries Analysis
## Objective
Explore the dataset to understand how factors like experience, location, and work mode impact salaries in Data Science roles.

## Key Questions
1. Which roles have the highest salaries?
2. How do salaries vary across countries and Experience Levels?
3. Does remote work influence average salaries?

## Tools
- Power BI
- Power Query
- GitHub
- 
## Overview
This Power BI dashboard visualizes salaries in data-related jobs based on experience levels, work locations, and company regions. The dataset includes data on job roles, salaries, locations, and work modes, offering insights into how these factors influence earnings.

## Dashboard Features

### Filters
- **Experience Level**: EN (Entry), MI (Mid), SE (Senior), EX (Executive)
- **Work Location**: Hybrid, On-Site, Remote

### Visualizations
1. **Average Salary by Job**
   - Bar chart comparing average salaries for Data Analyst, Data Engineer, and Data Scientist roles.

2. **Salary by Experience Level**
   - Scatter plot showing salary variations across experience levels (Entry, Mid, Senior, Executive) for different job roles.

3. **Average Salary by Company Location**
   - Map showcasing regional salary differences around the world.

## Key Insights
- Data Scientists earn the highest average salaries across all regions and work locations.
- Salaries increase consistently with experience levels, with Executive-level professionals earning the most.
- North America and Europe offer higher salaries on average compared to other regions.
- USA and Canada are the countries offering the highest salaries for Remote Job Positions.
- Switzerland is the country with the highest salary for Entry-Level positions.

## Dataset Information
- **Source**: Data Science Job Salaries Dataset [Kaggle](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023/data)
- **Columns**:
  - `work_year`: The year the salary was paid.
  - `experience_level`: Experience level in the job during the year (EN, MI, SE, EX).
  - `employment_type`: Type of employment for the role (e.g., Full-Time, Part-Time).
  - `job_title`: Role worked in during the year (e.g., Data Scientist, Data Analyst).
  - `salary`: Total gross salary amount paid.
  - `salary_currency`: Currency of the salary paid (ISO 4217 code).
  - `salaryinusd`: Salary converted to USD.
  - `employee_residence`: Employee's primary country of residence during the work year.
  - `remote_ratio`: Amount of work done remotely (e.g., 0, 50, 100).
  - `company_location`: Country of the employer's main office or contracting branch.
  - `company_size`: Median number of employees in the company during the year.

## Repository Structure
```plaintext
data_salaries_2023
├── README.md
├── data_salaries_2023.pbix
├── Dashboard_Report.pdf
└── Dataset.csv (if allowed to share)
```
## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/TSMathi/data_salaries_2023.git
   ```
2. Open the `data_salaries_2023.pbix` file in Power BI Desktop.
3. Use the filters to explore data insights.

## Contributing
Feel free to fork this repository and submit pull requests. Feedback is appreciated to improve the dashboard's interactivity and visualizations.

## Contact
For questions or feedback, contact me at mathiascuellar2004@gmail.com or via [LinkedIn](https://www.linkedin.com/in/mathias-cuellar-516754284/).
