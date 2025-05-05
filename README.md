# Credit-Debt-and-Income-Analysis-for-Wealthwise-Co
## Introduction

In today’s fast-paced economy, the ability to manage credit and debt wisely is more crucial than ever. Behind every financial transaction lies a story of ambition, challenges, and financial discipline. The way individuals handle their income, manage their debt, and maintain their credit scores not only affects their personal financial health but also reflects broader socioeconomic patterns.

This analysis dives into the credit and income profiles of individuals across different age groups, regions, and income brackets to uncover how behaviors differ, where risks are concentrated, and what patterns can help businesses and policymakers make informed decisions.

### Objective of the Project

The primary goal of this project is to perform a comprehensive analysis of credit and income profiles using key metrics such as debt-to-income ratio, total debt, credit scores, and monthly debt trends. The objective is to extract meaningful insights from the data and highlight patterns that can inform financial planning, credit risk management, and targeted financial product offerings.

## Story of Data

### Story of Data

In order to generate accurate and impactful insights, it is essential to understand the origin, structure, and characteristics of the data. The journey of this dataset from its source to its transformation, plays a pivotal role in ensuring the reliability of the analysis. This section sheds light on how the data was obtained, the key variables it contains, and the inherent challenges it presents.

### Data Source

The dataset used in this project was obtained from internal company records that reflect real-world financial behaviors over a 12-month period.

### Data Collection Process

The data was compiled through secure transaction logs, credit bureau reports, and demographic databases, ensuring a wide coverage of income, debt, and credit-related metrics.

### Data Structure

The dataset is structured with rows representing individual profiles and columns capturing features such as TransactionID, Age, Debt Amount, Monthly Income, Credit Score, Region, Gender, Income Bracket, Retirement Age, and Number of Credit Cards.

### Important Features and Their Significance

* **Debt to Income Ratio**: A critical metric that compares an individual's total monthly debt payments to their gross monthly income. It serves as a gauge of financial stress and indicates how much of a person’s income is dedicated to repaying debt, thus reflecting their borrowing capacity and financial stability.
* **Credit Score**: A numerical representation of an individual's creditworthiness, typically ranging from 300 to 850, used by lenders to assess the likelihood of repayment and financial reliability.
* **Region**: Helps identify geographic disparities.
* **Age Group and Retirement Age**: Tracks lifecycle patterns in financial behavior.
* **Number of Credit Cards**: Suggests credit accessibility and potential exposure.

### Data Limitations or Biases

The data might be limited in scope due to under-representation of certain regions and age groups. Additionally, credit behavior captured over a single year might not reflect long-term financial habits.

## Data Splitting and Preprocessing

### Data Cleaning

The dataset was cleaned by removing duplicates, correcting data entry errors, and validating consistency across demographic and financial variables.

### Handling Missing Values

Missing values were addressed using appropriate techniques such as:

* Median imputation for income and debt fields
* Mode imputation for categorical values like Region and Gender

### Data Transformations

New variables were engineered, such as:

* Monthly Debt Ratio
* Age Categories (e.g., 18–27, 28–37)
* Credit Score Groupings (Low, Medium, High)

### Data Splitting

Data was divided into dependent variables (e.g., Debt Amount, Credit Score) and independent variables (e.g., Age, Gender, Region) for targeted analysis.

### Industry Context

This project pertains to the **finance and credit management** industry. Insights are especially relevant to credit bureaus, lenders, personal finance platforms, and policy analysts.

### Stakeholders

The findings from this project will benefit:

* Credit risk analysts
* Financial advisors
* Lending institutions
* Consumer advocacy groups

### Value to the Industry

By uncovering behavioral trends and risk profiles within credit and debt data, the financial industry is better positioned to identify vulnerabilities, anticipate default risks, and support financial wellness across diverse demographics. Specifically, this understanding enables the industry to:

* Enhance lending models
* Develop targeted financial products
* Promote responsible credit usage through data-driven policies

## Pre-Analysis

### Identify Key Trends

* Younger individuals (18–27) have the **highest debt-to-income ratios**, indicating higher financial risk.
* Region 40 leads as the **most indebted region**, signaling potential localized financial stress.
* Males hold slightly **higher average credit scores** than females.

### Potential Correlations

* A possible inverse relationship between age and debt levels.
* Credit score may positively correlate with income bracket.

### Initial Insights

* Monthly debt peaked in the **second month**, suggesting either seasonal behavior or irregular expenses.
* Individuals retiring between **65–69** carry the highest total debt.

## In-Analysis

### Unconfirmed Insights

* Females hold **more credit cards** on average, despite slightly lower average credit scores.
* Medium income earners surprisingly have the **highest average credit scores** compared to high-income earners.

### Recommendations

* Credit education should target **young adults and Region 40**.
* Financial products should cater to **medium-income brackets**, leveraging their strong credit behavior.
* Evaluate card usage among **females** to assess potential overextension.

### Analysis Techniques Used in Excel

* Pivot Tables for aggregation by demographics
* Line and Bar Charts for trend visualization
* Conditional formatting for risk highlighting
* Data Filters and Slicers for segmentation

## Post-Analysis and Insights

### Key Findings

* The debt burden is highest among the youngest age group and retirement-aged individuals.
* Region 40 consistently shows the highest total debt, necessitating localized financial strategies.
* Medium income earners exhibit the most stable credit behavior, contrary to expectations.

### Comparison with Initial Findings

While early trends hinted at high risk among younger groups, the confirmed insights show this risk extends into retirement age. Also, while high-income groups were expected to have better credit, **medium-income groups outperformed**.

## Data Visualizations & Charts

* **Debt to Income Ratio by Age**: Highlights highest ratios among 18–27 group.
* **Most Indebted Regions**: Visualizes Region 40’s dominance.
* **Monthly Debt Trend**: Identifies spikes and seasonal fluctuations.
* **Credit Score by Gender and Income Bracket**: Displays gender gap and unexpected score patterns.
* **Total Debt by Retirement Age**: Shows accumulation patterns near retirement.
* **Credit Cards by Gender**: Indicates credit usage trends.

Each visualization was built using Excel’s charting tools, providing dynamic filtering through slicers for interactivity.

## Recommendations and Observations

### Actionable Insights

* **Introduce debt education programs** for young adults and retirees.
* **Enhance credit monitoring tools** for medium-income individuals to maintain high credit scores.
* **Target Region 40** with customized financial literacy campaigns and debt relief options.

### Optimizations or Business Decisions

* Develop age-specific credit card offerings with financial safeguards.
* Tailor financial products for medium earners with robust repayment behaviors.
* Investigate seasonal trends to better align marketing and loan disbursement periods.

### Unexpected Outcomes

* Medium-income individuals had better credit scores than high-income individuals, challenging assumptions about wealth and credit reliability.

## Conclusion

### Key Learnings

* Financial behavior varies significantly by age, region, and income level.
* Data-driven insights challenge assumptions and provide clarity for targeted interventions.

### Limitations

* Dataset is limited to a 12-month period.
* Missing values and underrepresented demographics may skew some findings.

### Future Research

* Extend analysis across multiple years for trend validation.
* Incorporate behavioral metrics (e.g., payment history) for deeper insights.

## References & Appendices

* Internal financial dataset, Wealthwise Freedom Co.
* Excel: Microsoft 365 Toolkit
* Charts & formulas included in Appendix A
* Raw data samples and transformation logic included in Appendix B
![Picture7](https://github.com/user-attachments/assets/544aba48-0294-4b06-a896-424db38f503a)
