
# SQL Project: GenZ Workplace Insights

## Overview

The GenZ Workplace Insights project aims to gain valuable insights into the career aspirations, preferences, and expectations of the Generation Z (Gen Z) demographic in a professional setting. The project utilizes a dataset named GenZdataset, comprising information gathered from personalized responses, mission aspirations, learning aspirations, and manager aspirations.

## Data Integration

The project begins by combining relevant data from multiple tables, including personalized_info, mission_aspirations, learning_aspirations, and manager_aspirations. The resulting comprehensive dataset, named 'wholedata,' serves as the foundation for subsequent analysis and exploration.

```sql
-- Creating a comprehensive dataset
WITH wholedata AS (
    -- SQL Join statements to integrate data
)
SELECT * FROM wholedata;
```

## Analytical Queries

The project explores various facets of Gen Z workplace preferences through a series of analytical queries. Each query addresses specific questions related to career choices, working environments, and salary expectations. Here is an overview of the key themes explored:

### 1. Workplace Environment Preferences

- **Percentage of Office Attendance:**
  - Investigates the percentage of male and female Gen Z individuals who prefer to work in an office environment every day.

### 2. Career Aspirations and Influences

- **Parental Influence on Business Operations:**
  - Explores the influence of parents on Gen Z individuals aspiring to work in Business Operations.

### 3. Higher Education Aspirations

- **Interest in Higher Studies:**
  - Examines the percentage of Gen Z individuals interested in pursuing higher education, providing a gender-wise breakdown.

### 4. Mission Alignment and Workplace Choices

- **Willingness to Work Amidst Misaligned Mission:**
  - Investigates the percentage of Gen Z individuals willing or unwilling to work for a company with a misaligned mission, with a gender-based breakdown.

### 5. Female Preferences

- **Preferred Working Environment for Females:**
  - Identifies the most suitable working environment according to female Gen Z preferences.

### 6. Social Impact and Career Choices

- **Impact of Social Likelihood on Career Aspirations:**
  - Calculates the total number of females aspiring to work in their closest career field while considering the likelihood of social impact.

### 7. Higher Education and Parental Influence

- **Males Interested in Higher Education Abroad and Influenced by Parents:**
  - Retrieves the count of males interested in higher education abroad and influenced by parental career choices.

### 8. Social Impact Likelihood

- **Social Impact Likelihood among Higher Education Aspirants:**
  - Determines the percentage of genders with a specific social impact likelihood among those interested in higher education abroad.

### 9. Team Collaboration Preferences

- **Preferences for Team Collaboration:**
  - Provides a detailed split of Gen Z preferences for working with teams, including counts and percentages for male, female, and overall preferences.

### 10. Work Likelihood and Gender

- **Breakdown of Work Likelihood for Each Gender:**
  - Presents a detailed breakdown of the likelihood of Gen Z individuals working for an organization based on their expected work duration.

### 11. Salary Expectations

- **Average Starting Salary Expectations at 3-Year Mark:**
  - Calculates the average starting salary expectations at the 3-year mark for each gender.

- **Average Starting Salary Expectations at 5-Year Mark:**
  - Calculates the average starting salary expectations at the 5-year mark for each gender.

- **Average Higher Bar Salary Expectations at 3-Year Mark:**
  - Computes the average higher bar salary expectations at the 3-year mark for each gender.

- **Average Higher Bar Salary Expectations at 5-Year Mark:**
  - Computes the average higher bar salary expectations at the 5-year mark for each gender.

### 12. Salary Expectations by State (India)

- **Average Starting Salary Expectations at 3-Year Mark by State:**
  - Calculates the average starting salary expectations at the 3-year mark for each gender and each state in India.

- **Average Starting Salary Expectations at 5-Year Mark by State:**
  - Calculates the average starting salary expectations at the 5-year mark for each gender and each state in India.

- **Average Higher Bar Salary Expectations at 3-Year Mark by State:**
  - Computes the average higher bar salary expectations at the 3-year mark for each gender and each state in India.

- **Average Higher Bar Salary Expectations at 5-Year Mark by State:**
  - Computes the average higher bar salary expectations at the 5-year mark for each gender and each state in India.

### 13. Mission Misalignment and Working Preferences

- **Possibility of Working for an Organization with Misaligned Mission:**
  - Provides a detailed breakdown of the possibility of Gen Z individuals working for an organization if the mission is misaligned, categorized by state in India.

## Conclusion

The GenZ Workplace Insights project provides a comprehensive exploration of Gen Z preferences in the professional sphere, offering valuable information for organizations and stakeholders interested in understanding and adapting to the evolving expectations of the next generation workforce.
