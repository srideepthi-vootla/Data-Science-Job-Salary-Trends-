# Data Science Market Insights Dashboard

## Overview

The **Data Science Market Insights Dashboard** is an interactive visualization project designed to analyze the global data science job market. The dashboard provides insights into salary trends, employment types, company size, job roles, and geographic distributions, helping professionals and organizations make informed decisions about hiring, career planning, and workforce analysis.

This project leverages Python for data preprocessing and Tableau for creating the visualizations. The dataset used contains information on work years, salaries, job titles, company locations, and employee residences, offering a comprehensive view of the data science landscape.

---

## Key Features

### 1. Salary Trends Over Years
- Tracks changes in average salaries across multiple years.
- Highlights industry growth and fluctuations in compensation.

### 2. Top 10 Employee Residences
- Visualizes the top countries where data science professionals reside.
- Helps identify geographic workforce concentrations.

### 3. Companies by Size and Location
- Analyzes the distribution of companies hiring data professionals based on size (Small, Medium, Large).
- Provides insights into organizational dynamics and geographic spread.

### 4. Average Salary by Job Title and Experience Level
- Detailed breakdown of salaries for various job roles and experience levels.
- Helps professionals benchmark compensation based on their roles and expertise.

### 5. Employment Type Analysis
- Examines salary variations for Full-time, Part-time, Freelance, and Contract employment.
- Reveals patterns in compensation tied to employment types.

### 6. Global Salary Distribution
- A geospatial map showing average salaries by country.
- Highlights disparities in pay scales across regions.

### 7. Final Interactive Dashboard
- Integrates all visualizations into a single, intuitive Tableau dashboard.
- Allows users to apply filters, such as Job Title, Experience Level, and Company Location, for deeper analysis.

---

## Dataset Description

The project uses two datasets:
1. **`ds_salaries.csv`**:
   - Raw data containing salaries, job roles, and company details.
2. **`ds_salaries_cleaned.csv`**:
   - Preprocessed dataset after cleaning and handling missing values.

### Fields
- **work_year**: Year in which the salary data was recorded.
- **experience_level**: Levels include Entry-level, Intermediate, Senior, and Expert.
- **employment_type**: Types include Full-time, Part-time, Freelance, or Contract.
- **job_title**: Titles like Data Scientist, Machine Learning Engineer, etc.
- **salary_in_usd**: Annual salary converted to USD for comparison.
- **company_location**: Location of the hiring company.
- **employee_residence**: Country of residence for the employee.

---

## Setup Instructions

1. Clone the Repository
   ```bash
   git clone https://github.com/your_username/DataScience-Market-Insights.git
   cd DataScience-Market-Insights
   
2. Install Python Dependencies
   ```bash
   pip install -r requirements.txt

3. Run the Analysis Notebook
   - Open and run exploratory_analysis.ipynb for data preprocessing and preliminary insights.

4. Explore the Tableau Dashboard
   - Open DataScienceTableau.twb in Tableau to interact with the visualizations.
  
---

## Key Insights
### 1. Geographic Trends:
   - The United States has the largest concentration of data science professionals with the highest salaries.
   - Emerging economies like India offer opportunities but at lower pay scales.

### 2. Role and Experience Trends:
   - Senior roles such as Machine Learning Scientist and Lead Data Scientist have the highest average salaries.
   - Salaries increase significantly with experience levels.

### 3. Employment Types:
   - Full-time roles dominate the market, accounting for over 95% of all roles.

### 4. Salary Trends Over Time:
   - A steady increase in salaries across the years, reflecting the growing demand for data professionals.

---

## Technology Stack
- **Data Processing:** Python (Pandas, NumPy)
- **Visualization:** Tableau, Matplotlib, Seaborn
- **Geospatial Mapping:** Tableau Mapbox Integration
- **Reporting:** Microsoft Word, Markdown

---

## Future Enhancements
1. **Dynamic Updates:**
   - Automate data ingestion for real-time analysis.
   
2. **Additional Metrics:**
   - Include metrics such as skill demand and remote work ratios.   

3. **Enhanced Interactivity:**
   - Add more granular filters, such as specific skills and industries.   
