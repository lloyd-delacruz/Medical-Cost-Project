# Medical Insurance Charges Analysis

## Introduction
The provided dataset offers a detailed overview of demographic and health-related factors influencing medical insurance charges. It includes information on age, gender, Body Mass Index (BMI), smoking status, number of dependents, region of residence, and insurance costs. Understanding these variables is essential for uncovering trends and relationships that impact healthcare expenses. This report aims to analyze the dataset comprehensively to provide actionable insights into the factors driving insurance costs, offering value to insurers, healthcare professionals, and policymakers.

**Dataset:** Kaggle Insurance Data

## Goals
- 🎯 Provide data-driven insights into the main factors influencing medical insurance charges.
- 📝 Develop actionable recommendations for risk management and pricing strategies.
- 📊 Identify correlations between key variables to improve predictive modeling for insurance costs.

## Questions
- ❓ What is the average medical insurance charge for smokers compared to non-smokers?
- 🌎 Which region has the highest average insurance charges, and what factors contribute to this?
- 📈 How does BMI correlate with medical insurance charges? Are individuals with higher BMI paying more?
- 📆 Which age group incurs the highest medical charges, and does this trend vary across regions?
- 📊 What is the distribution of smokers across different age groups and regions?
- ⚖️ Are men or women paying more for insurance on average, and how does smoking status influence this?
- 🗺️ Is there a significant difference in insurance charges between regions for smokers versus non-smokers?

## Assumptions
- ✔️ **Medical charges reflect the health risk profile of individuals:** Higher charges might indicate higher health risks or a greater need for medical services.
- 🚬 **Smoking status is a significant driver of insurance charges:** Smokers are presumed to have higher charges due to associated health risks.
- 💪 **BMI is a reliable indicator of health-related costs:** Individuals with higher BMI are assumed to have higher medical charges due to potential health complications like obesity.

## Data Description
| Column Name | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `id`        | Unique identifier for each entry.                                          |
| `age`       | Age of the individual.                                                     |
| `sex`       | Gender of the individual (male or female).                                 |
| `bmi`       | Body Mass Index, a numeric value indicating the individual's weight relative to height. |
| `children`  | Number of dependents the individual has.                                   |
| `smoker`    | Indicates whether the individual is a smoker (yes or no).                  |
| `region`    | Region where the individual resides (northwest, northeast, southwest, southeast). |
| `charges`   | Medical insurance charges billed to the individual.                       |

## Data Analysis

### Data Cleaning
- 🧹 Removed duplicate entries.
- 📝 Checked for spelling errors and corrected them.
- 🔍 Verified each column's datatype matches its intended format.

### Analytical Process Using Excel
- 📊 **Descriptive Statistics:** Calculated mean, median, and standard deviation for numerical columns (e.g., charges, age, BMI) to understand data distribution.
- 📋 **Pivot Tables:** Analyzed relationships between categorical variables and numerical data:
  - Average charges by region.
  - Average charges by smoker status.
  - Charges distribution by sex.
- 🔄 **Correlation Analysis:** Computed correlations between BMI, age, and charges using Excel's CORREL function.
- 📈 **Data Visualization:**
  - Created bar charts to compare average charges across regions.
  - Used scatter plots to visualize the relationship between BMI and insurance charges.
  - Built pie charts to show the proportion of smokers vs. non-smokers in the dataset.
- 🔎 **Filters and Conditional Formatting:**
  - Highlighted outliers in charges and identified potential data anomalies.
  - Filtered specific groups (e.g., smokers in the Southeast) for targeted analysis.

## Key Findings

### 🗺️ Regional Variations
- 🔴 Southeast region has the highest average insurance charges at **$14,735**, followed by the Northeast at **$13,406**.
- 🟢 Regions like the Northwest and Southwest incur lower average charges (**$12,417** and **$12,346**, respectively).
- 💡 This suggests the Southeast region may have a higher concentration of individuals with higher health risks or higher healthcare costs.

### 🚬 Impact of Smoking
- Smokers incur significantly higher insurance charges than non-smokers:
  - **Average charges for smokers:** ~$30,000+
  - **Average charges for non-smokers:** ~$10,000
- Smoking is a major risk factor driving healthcare costs.

### 📈 BMI and Insurance Costs
- Individuals with higher BMI (Overweight and Obese categories) consistently face higher medical charges:
  - **Obese individuals** incur the highest average charges (~$15,000).
  - Individuals with normal BMI have comparatively lower charges, emphasizing the financial impact of lifestyle-related health conditions.

### 📆 Age Group Trends
- **Pre-Retirement (56-65)** and **Mature Adults (46-55)** contribute significantly to insurance charges, reflecting the impact of age-related health conditions:
  - These groups face the highest average charges in the dataset.
  - Younger groups, like **Children (0-18)** and **Young Adults (19-25)**, incur noticeably lower charges.

### 🚭 Smokers Across Age Groups
- The **Young Adult (19-25)** and **Adult (26-35)** groups show the highest concentration of smokers, with over 53 smokers in each group.
- 💡 Targeting smoking cessation programs for these age groups can significantly reduce future healthcare costs.

## Recommendations for Action
1. 🚭 **Smoking Prevention Programs:**  
   Develop targeted smoking cessation initiatives for Young Adults and Adults, as they are the most affected groups.
2. 🗺️ **Regional Health Interventions:**  
   Investigate the Southeast region to identify the causes of higher costs and develop cost-containment strategies.
3. 💪 **Lifestyle Health Programs:**  
   Introduce weight management and wellness initiatives for individuals in the Overweight and Obese BMI categories to reduce healthcare costs.
4. 📆 **Support for Older Age Groups:**  
   Allocate resources for Mature Adults and Pre-Retirement age groups, as they face the highest medical costs due to aging-related health conditions.
