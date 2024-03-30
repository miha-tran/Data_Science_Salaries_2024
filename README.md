<h3 align="center">Capstone Project: Data Science 2024</h3>

 <p align="center">Welcome to the my capstone Project for BrainStation Bootcamp.
  <br />
  <a href="[https://github.com/miha-tran/Data_Science_Salaries_2024]"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a [href="https://github.com//miha-tran/Data_Science_Salaries_2024]">View Demo</a>
    ·
    <a href="https://github.com//miha-tran/Data_Science_Salaries_2024/issues">Report Bug</a>
    ·
    <a href="https://github.com//miha-tran/Data_Science_Salaries_2024/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-overview">Project Overview</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#data-dictionary">Data Dictionary</a></li>
    <li><a href="#simple-roadmap">Simple Roadmap</a></li>
    <li><a href="#detailed-roadmap">Detailed Roadmap</a></li>    
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Project Overview ![wave](https://github.com/miha-tran/Data_Science_Salaries_2024/assets/149928007/169a1d1c-b2bb-476a-9a32-1ec50c60f50c)

### Problem Area and Users
In the dynamic field of data science, understanding salary trends is crucial for professionals and organizations. This dataset provides insights into Data Science Salaries from 2020 to 2024, offering valuable information on trends, regional variations, and factors influencing compensation for data enthusiasts, researchers, and industry professionals.

### The Big Idea
Utilizing machine learning, the insights from the data can be harnessed to understand different factors:

1. **Predictive Modeling**: By analyzing past salary data, machine learning can predict future salary trends, aiding professionals and companies in making informed decisions about compensation.
   
2. **Feature Analysis**: Machine learning can explore various factors affecting salaries, such as skills, experience, and location, helping optimize compensation strategies.
   
3. **Anomaly Detection**: Machine learning algorithms can identify unusual patterns or outliers in salary data, facilitating the detection and rectification of errors.
   
4. **Personalized Recommendations**: Leveraging individual profiles, machine learning can offer tailored advice on career development, skill enhancement, and negotiation tactics to improve salaries.
   
### The Impact:
This project is anticipated to bring tangible benefits to both society and businesses. By leveraging advanced technology, the aim is to assist companies in setting salaries more effectively, thereby increasing employee satisfaction and reducing turnover rates. This could potentially save businesses expenses associated with hiring and training new staff. Additionally, by streamlining the salary negotiation process, both employees and companies can save valuable time. Moreover, offering fair and competitive pay can help companies attract top talent, giving them a competitive edge in the market. In essence, the project aims to enhance the salary determination process for all stakeholders involved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
## Dataset

### Built With
<!--
* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]
-->
- Jupyter Notebook
- Python (+ pandas, numpy, glob and more)
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
## Getting Started

Since the project is made using Jupyter Notebook, you need Jupyter Notebook or a software compatible with .ipynb files.

### Prerequisites

Make sure you download the appropriate datasets and not just the notebook.

<!--
* npm
  ```sh
  npm install npm@latest -g
  ```
  -->
  
### Installation
<!--
1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
 -->

Click here to install Jupyter Notebook: https://jupyter.org/install
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Data Description
The primary dataset was sourced from ai-jobs.net, consisting of 14,299 rows and 11 columns.

### Data Dictionary
### Dataset Description

| Column Name       | Description                                                                                                        |
|-------------------|--------------------------------------------------------------------------------------------------------------------|
| work_year         | The year when the salary was paid.                                                                                 |
| experience_level  | The job experience level categorized as follows: EN (Entry-level / Junior), MI (Mid-level / Intermediate), SE (Senior-level / Expert), EX (Executive-level / Director). |
| employment_type   | Type of employment for the role: PT (Part-time), FT (Full-time), CT (Contract), FL (Freelance).                  |
| job_title         | The role held during the year.                                                                                     |
| salary            | Total gross salary amount paid.                                                                                    |
| salary_currency   | Currency of the salary paid as an ISO 4217 currency code.                                                          |
| salary_in_usd     | Salary converted to USD using statistical data from the BIS and central banks.                                      |
| employee_residence| Employee's primary country of residence during the work year as an ISO 3166 country code.                          |
| remote_ratio      | The percentage of work done remotely, categorized as: 0 (No remote work), 50 (Partially remote/hybrid), 100 (Fully remote).|
| company_location  | Country of the employer's main office or contracting branch as an ISO 3166 country code.                          |
| company_size      | The average number of employees in the company, categorized as: S (Less than 50 employees), M (50 to 250 employees), L (More than 250 employees). |


### Data Source
https://ai-jobs.net/salaries/download/

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


