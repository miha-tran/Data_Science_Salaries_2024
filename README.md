# Capstone Project: Data Science 2024

Welcome to the Data Science Capstone Project for the year 2024!

This repository contains all the necessary resources, code, and documentation for our capstone project in data science. Throughout this project, we aim to apply advanced data science techniques to solve real-world problems and gain valuable insights from data.

## Table of Contents

- [Project Overview](#project-overview)
- [Introduction](#introduction)
- [Story Behind](#story-behind)
- [Problem Statement](#problem-statement)
- [Our Solution](#our-solution)
- [Objectives](#objectives)
- [Potential Impact](#potential-impact)
- [Dataset](#dataset)
  - [Data Description](#data-description)
  - [Data Dictionary](#data-dictionary)
  - [Data Source](#data-source)
  - [Data Coverage](#data-coverage)
- [Project Roadmap](#project-roadmap)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Feature Engineering](#feature-engineering)
  - [Feature Selection](#feature-selection)
  - [Model Development](#model-development)
  - [Model Interpretation](#model-interpretation)
  - [Model Deployment](#model-deployment)
    - [User Interface Development](#user-interface-development)
- [Conclusion](#conclusion)
  - [Insights & Findings](#insights--findings)
  - [Key Takeaways](#key-takeaways)
  - [Future Directions](#future-directions)
  - [Final Thoughts](#final-thoughts)

## Project Overview

### Introduction
#### Problem Area / Users
In the dynamic field of data science, understanding salary trends is crucial for professionals and organizations. This dataset provides insights into Data Science Salaries from 2020 to 2024, offering valuable information on trends, regional variations, and factors influencing compensation for data enthusiasts, researchers, and industry professionals.

#### The Big Idea
Utilizing machine learning, the insights from the data can be harnessed to understand different factors:

1. **Predictive Modeling**: By analyzing past salary data, machine learning can predict future salary trends, aiding professionals and companies in making informed decisions about compensation.
   
2. **Feature Analysis**: Machine learning can explore various factors affecting salaries, such as skills, experience, and location, helping optimize compensation strategies.
   
3. **Anomaly Detection**: Machine learning algorithms can identify unusual patterns or outliers in salary data, facilitating the detection and rectification of errors.
   
4. **Personalized Recommendations**: Leveraging individual profiles, machine learning can offer tailored advice on career development, skill enhancement, and negotiation tactics to improve salaries.
   
5. **Regional Disparities Analysis**: By analyzing data from different regions, machine learning can uncover disparities in salaries, providing insights into geographical variations in compensation.

#### Impact
This project is anticipated to bring tangible benefits to both society and businesses. By leveraging advanced technology, the aim is to assist companies in setting salaries more effectively, thereby increasing employee satisfaction and reducing turnover rates. This could potentially save businesses expenses associated with hiring and training new staff. Additionally, by streamlining the salary negotiation process, both employees and companies can save valuable time. Moreover, offering fair and competitive pay can help companies attract top talent, giving them a competitive edge in the market. In essence, the project aims to enhance the salary determination process for all stakeholders involved.

### Story Behind
The genesis of this project stems from my personal inquiry regarding my career trajectory. Dissatisfied with the limited and often unreliable data available online through Google searches, I embarked on this capstone project to procure accurate and pertinent information for not only myself but also my classmates.

### Problem Statement
The project aims to address the challenge of inadequate and unreliable data available online regarding salary trends in the dynamic field of data science. Existing resources often provide limited insights, leaving professionals and organizations without a comprehensive understanding of salary dynamics. This lack of accurate and up-to-date information hampers individuals' ability to make informed decisions about their career paths and compensation negotiations. Therefore, the project endeavors to bridge this gap by providing robust, data-driven insights into Data Science Salaries from 2020 to 2024, empowering professionals and organizations to navigate the landscape with confidence.

### Our Solution
To address the challenge of inadequate and unreliable data regarding salary trends in data science, we propose the following solution:

- Comprehensive Data Collection: We will gather a diverse range of data sources spanning from 2020 to 2024, ensuring a comprehensive representation of salary trends in the field of data science.

- Data Cleaning and Processing: Rigorous data cleaning and preprocessing techniques will be applied to ensure the accuracy and consistency of the dataset.

- Exploratory Data Analysis (EDA): We will conduct in-depth exploratory data analysis to uncover patterns, trends, and insights within the dataset, providing a solid foundation for subsequent analysis.

- Machine Learning Modeling: Leveraging advanced machine learning algorithms, we will develop predictive models to forecast future salary trends and identify key factors influencing compensation in data science.

- Model Interpretation and Evaluation: We will interpret the results of our models and evaluate their performance, ensuring the reliability and accuracy of our predictions.

- Visualization and Communication: We will communicate our findings through intuitive visualizations and clear, concise reports, enabling stakeholders to easily understand and utilize the insights generated by our analysis.

### Objectives
The objectives of this capstone project are as follows:

- Data Collection: Gather a diverse range of data sources spanning from 2020 to 2024, capturing salary trends in the field of data science.

- Data Cleaning and Processing: Clean and preprocess the collected data to ensure accuracy and consistency.

- Exploratory Data Analysis (EDA): Conduct exploratory data analysis to uncover patterns, trends, and insights within the dataset.

- Machine Learning Modeling: Develop predictive models to forecast future salary trends and identify key factors influencing compensation in data science.

- Model Interpretation and Evaluation: Interpret the results of our models and evaluate their performance to ensure reliability and accuracy.

- Visualization and Communication: Communicate our findings through intuitive visualizations and clear, concise reports, enabling stakeholders to easily understand and utilize the insights generated by our analysis.

### Potential Impact
The potential impact of this capstone project spans across various stakeholders within the data science community:

- Professionals: Data science professionals will benefit from access to accurate and comprehensive salary trends, enabling them to make informed decisions about their career paths, negotiate better compensation packages, and plan for their future growth and development.

- Organizations: Companies operating in the data science space will gain valuable insights into salary dynamics, allowing them to benchmark their compensation packages against industry standards, attract top talent, and retain skilled employees. Additionally, businesses can use this information to optimize their hiring strategies and allocate resources more effectively.

- Educational Institutions: Academic institutions offering data science programs will have access to real-world salary data, allowing them to tailor their curriculum to meet the evolving needs of the industry and provide students with relevant and practical skills.

- Policy Makers: Policy makers and regulators may use the insights generated by this project to inform policies related to workforce development, talent retention, and economic growth in the data science sector.

- Community: By fostering transparency and knowledge-sharing within the data science community, this project contributes to the overall advancement and professionalism of the field, empowering individuals to make informed decisions and drive positive change.

## Dataset

### Data Description
The primary dataset was sourced from ai-jobs.net, consisting of 14,299 rows and 11 columns.

### Data Dictionary
- work_year: The year the salary was paid.
- experience_level: The experience level in the job during the year with the following possible values:
-- EN: Entry-level / Junior
-- MI: Mid-level / Intermediate
-- SE: Senior-level / Expert
-- EX: Executive-level / Director
- employment_type: The type of employment for the role:
-- PT: Part-time
-- FT: Full-time
-- CT: Contract
-- FL: Freelance
- job_title: The role worked in during the year.
- salary: The total gross salary amount paid.
- salary_currency: The currency of the salary paid as an ISO 4217 currency code.
- salary_in_usd: The salary in USD (FX rate divided by avg. USD rate of respective year) via statistical data from the BIS and central banks.
- employee_residence: Employee's primary country of residence during the work year as an ISO 3166 country code.
- remote_ratio: The overall amount of work done remotely, possible values are as follows:
-- 0: No remote work (less than 20%)
-- 50: Partially remote/hybrid
-- 100: Fully remote (more than 80%)
- company_location: The country of the employer's main office or contracting branch as an ISO 3166 country code.
- company_size: The average number of people that worked for the company during the year:
-- S: less than 50 employees (small)
-- M: 50 to 250 employees (medium)
-- L: more than 250 employees (large) (large) |

### Data Source
https://ai-jobs.net/salaries/download/

### Data Coverage

The dataset provides comprehensive coverage of various aspects related to Data Science Salaries, including:

- **Work Year:** The year in which the salary was paid, providing a longitudinal view of salary trends from 2020 to 2024.

- **Experience Level:** Categorization of experience levels into Entry-level, Mid-level, Senior-level, and Executive-level, offering insights into salary distributions across different career stages.

- **Employment Type:** Classification of employment types into Part-time, Full-time, Contract, and Freelance, facilitating analysis of salary variations based on employment arrangements.

- **Job Title:** Description of the roles held during the respective year, allowing for the examination of salary disparities across different positions within the data science field.

- **Salary:** The total gross salary amount paid, serving as the primary metric for analyzing compensation trends.

- **Salary Currency:** The currency of the salary paid, providing clarity on the currency denomination for international comparisons.

- **Salary in USD:** Conversion of salaries into USD, allowing for standardized analysis and comparison across different regions.

- **Employee Residence:** Employee's primary country of residence during the work year, enabling the assessment of salary differentials based on geographical location.

- **Remote Ratio:** Quantification of remote work percentages, ranging from no remote work to fully remote arrangements, elucidating the impact of remote work on salary structures.

- **Company Location:** The country of the employer's main office or contracting branch, offering insights into regional variations in salary levels.

- **Company Size:** Categorization of company sizes into small, medium, and large, providing context on the organizational scale and its influence on salary distributions.

With these comprehensive data attributes, the dataset offers a rich resource for analyzing and understanding Data Science Salaries across various dimensions and contexts.

## Project Roadmap
1. **Data Collection and Preparation**
   - Gather data from diverse sources spanning from 2020 to 2024.
   - Handle missing values, inconsistencies, and outliers through initial data cleaning.
   - Standardize data formats and ensure compatibility for further analysis.

2. **Exploratory Data Analysis (EDA)**
   - Performing exploratory data analysis to understand dataset distribution and characteristics.
   - Explore correlations between variables and uncover potential predictors of salary.

3. **Feature Engineering**
   - Engineer new features or transform existing ones to enhance predictive modeling capabilities.
   - Utilize techniques like one-hot encoding or feature hashing for extracting relevant information from categorical variables.

4. **Model Development**
   - Selecting appropriate machine learning algorithms and hyperparameters for salary prediction.
   - Split dataset into training and testing sets and train multiple models using different algorithms.

5. **Model Interpretation**
   - Interpret model results and analyze feature importance to identify influential variables in predicting salary.
   - Validating model assumptions and assessing model robustness through sensitivity analysis.

6. **Model Deployment**
   - Deploy trained model in a production environment and develop a user-friendly interface for accessing model predictions.
   - Implement monitoring and maintenance procedures to ensure continued performance and accuracy.

7. **Evaluation and Validation**
   - Evaluating deployed model's performance using real-world data and relevant metrics.
   - Validate model predictions against actual salary data to assess reliability and effectiveness.

8. **Documentation and Reporting**
   - Documenting project workflow, including data preprocessing, modeling techniques, and evaluation results.
   - PDF report summarizing key findings, insights, and recommendations.
   - PowerPoint presentation slides communicating project outcomes to stakeholders.

### Data Cleaning
1. Handling Missing Values:

- Identify missing values in the dataset.
- Identify outliers in the dataset using statistical methods or visualization techniques.
- Identify inconsistencies in the dataset, such as spelling errors, formatting issues, or conflicting information.
- Standardize variables to ensure consistency across the dataset, such as converting text to lowercase, removing special characters, or converting dates to a consistent format.

2. Handling Duplicate Entries:

- Identify duplicate entries in the dataset, which may arise due to data entry errors or system issues.
- Decide on a strategy for handling duplicate entries, such as removing duplicates, merging duplicate entries, or flagging them for further investigation.

3. Encoding Categorical Variables:

- Identify categorical variables in the dataset.
- Decide on an appropriate encoding scheme for categorical variables, such as one-hot encoding, label encoding, or frequency encoding.
- Implement the chosen encoding scheme to transform categorical variables into a format suitable for analysis.

4. Dealing with Skewed Data:

- Identify skewed distributions in the dataset, which may impact the performance of machine learning algorithms.
- Decide on an appropriate transformation to address skewness, such as log transformation, square root transformation, or Box-Cox transformation.

5. Ensuring Consistency and Integrity:

- Check for consistency and integrity constraints in the dataset, such as referential integrity between related tables or logical constraints within the dataset.
- Implement checks and validations to ensure that the dataset adheres to these constraints and that the data is internally consistent.


### Exploratory Data Analysis
1. Data Profiling:
- Examine the structure and size of the dataset.
- Identify the types of variables (numerical, categorical, etc.) present in the dataset.
- Determine the range and distribution of values for each variable.

2. Univariate Analysis:

- Analyze individual variables in isolation to understand their distributions and characteristics.
- For numerical variables, compute summary statistics such as mean, median, standard deviation, and percentiles. Visualize distributions using histograms, box plots, or density plots.
- For categorical variables, compute frequency counts and percentages for each category. Visualize distributions using bar charts or pie charts.

3. Bivariate Analysis:

- Explore relationships between pairs of variables to identify potential associations or patterns.
- For numerical variables, compute correlation coefficients and visualize relationships using scatter plots or heatmaps.
- For categorical variables, compute contingency tables and visualize relationships using stacked bar charts or mosaic plots.
- Explore interactions between numerical and categorical variables using grouped box plots or violin plots.

4. Multivariate Analysis:

- Extend bivariate analysis to include multiple variables simultaneously.
- Identify complex relationships and interactions between multiple variables using techniques such as clustering, dimensionality reduction, or regression analysis.
- Visualize multivariate relationships using techniques like scatterplot matrices, parallel coordinate plots, or trellis plots.

5. Feature Engineering:

- Generate new features or transformations based on insights gained from EDA.
- Create derived variables that capture additional information or relationships between existing variables.
- Remove redundant or irrelevant features that do not contribute to the analysis.

6. Identifying Patterns and Anomalies:

- Search for patterns, trends, or anomalies in the data that may require further investigation.
- Use visualization techniques such as time series plots, trend lines, or anomaly detection algorithms to identify interesting patterns or outliers.
