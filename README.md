<h3 align="center">Capstone Project: Data Science 2024</h3>

<p align="center">Welcome to my capstone Project for BrainStation Bootcamp.
<br />
<a href="https://github.com/miha-tran/Data_Science_Salaries_2024/tree/main/code"><strong>Explore the jupyter file »</strong></a>
<br />
<br />
<a href="https://github.com/miha-tran/Data_Science_Salaries_2024/tree/main/dataset">Dataset</a>
·
<a href="https://github.com/miha-tran/Data_Science_Salaries_2024/issues">Report Bug</a>
·
<a href="https://github.com/miha-tran/Data_Science_Salaries_2024/pulls">Request Feature</a>
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


## Built With
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
- Jupyter Notebook/ Kernel3
- Python
- Detail of libraries ( <a href="[https://github.com/miha-tran/Data_Science_Salaries_2024/code]">)
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Since the project is made using Jupyter Notebook, you need Jupyter Notebook or a software compatible with .ipynb files.

  
### Installation

Click here to install Jupyter Notebook: https://jupyter.org/install
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Data Description
The primary dataset was sourced from ai-jobs.net, consisting of 14,299 rows and 11 columns.

### Data Dictionary

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

<!-- SIMPLE ROADMAP -->
## Simple Roadmap

- [x] Identifying and acquiring relevant IT salary datasets
- [x] Data preprocessing and cleaning to ensure data quality
- [x] Experimentation with various predictive modeling techniques
- [x] Selection and optimization of the most effective prediction model for IT salaries
- [x] Refinement and training of the chosen model to enhance prediction accuracy
- [ ] Publishing the refined dataset as a clean CSV on Kaggle to benefit the community
- [ ] Deployment of the prediction model on a web platform for user-friendly access
- [ ] Periodic data updates (quarterly or annually) to maintain and improve prediction relevance


<!-- DETAILED ROADMAP -->
## Detailed Roadmap

- [x] Identifying and acquiring relevant IT salary datasets

Securing the right dataset was challenging. Available datasets were either too small or outdated. After reviewing several sources, I opted for a comprehensive dataset with around 15,000 entries, which offers a good balance between volume and recency.

- [x] Data preprocessing and cleaning to ensure data quality

Initially, I manually processed each data entry. However, given the scale, I streamlined the process, focusing only on the most impactful variables for IT salaries. This approach led to a cleaner, more focused dataset conducive to predictive modeling.

- [x] Experimentation with various predictive modeling techniques

I began by applying several predictive models to understand which best fits our data's nature. Adjustments were made to fine-tune these models, focusing on categorizing IT roles and experience levels accurately. This iterative process was essential for narrowing down to the most suitable model for salary prediction.

- [ ] Selection and optimization of the most effective prediction model for IT salaries
- [ ] Refinement and training of the chosen model to enhance prediction accuracy
- [ ] Publishing the refined dataset as a clean CSV on Kaggle to benefit the community
- [ ] Deployment of the prediction model on a web platform for user-friendly access
- [ ] Periodic data updates (quarterly or annually) to maintain and improve prediction relevance

<br>
Updates to the README.md will be made regularly to reflect progress and new features.
<br>
Visit the [open issues](https://github.com/miha-tran/Data_Science_Salaries_2024/issues) for a comprehensive list of planned enhancements and known issues.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing
Contributions are essential for the continuous enhancement and accuracy of IT salary predictions. Suggestions and contributions are warmly welcomed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Project Contact - Miha Tran - mihari.tran@gmail.com

LinkedIn: [https://www.linkedin.com/in/minh-hai/](https://www.linkedin.com/in/minh-hai/)

Project Link: [https://github.com/miha-tran/Data_Science_Salaries_2024](https://github.com/miha-tran/Data_Science_Salaries_2024)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


