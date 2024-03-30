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

<!-- SIMPLE ROADMAP -->
## Simple Roadmap

- [x] Finding the right dataset(s)
- [x] Cleaning the dataset and filling the empty values as needed
- [x] Trying multiple types of prediction models
- [ ] Finding the best model for the current situation
- [ ] Training the model for maximum efficiency
- [ ] Export a clean dataframe/CSV on Kaggle for other users
- [ ] Hosting the project on a website for easy utilization
- [ ] Updating the dataset every quarter or every year, for maximum efficiency of the predictions


<!-- DETAILED ROADMAP -->
## Detailed Roadmap

- [x] Finding the right dataset(s)

Finding the right dataset was difficult. When I started this project, I wanted to make it about predicting both game ratings as well as game sales. However, after checking some datasets regarding sales, it seemed like most of the datasets were incomplete. I could find more info on VGChartz, but I would have to do all of it line by line. After a few lines, I also realized that I had to search every game separately, as the data was not at the same place for all the games. And it was also hard to find the data outside of "Total Sales".

I debatted still keeping sales but because of the time constraint, I decided to drop sales for now and focus on the rating prediction.

- [x] Cleaning the dataset and filling the empty values as needed

Just like the first point, I tried to fill the values line by line at first, when I was still working on both ratings and sales. However, I since I turned out to only find about 2000 lines of data, I deemed it incomplete and I stopped filling in the values. I also wanted to fill in the values regarding story-focused games and gameplay-focus games, but I realized that it was most of the time correlated with the genre. So I also stopped doing that.

When I only kept the rows with the info in the Metacritic Score, it was about 14k and I decided it was enough.

- [x] Trying multiple types of prediction models

Right after I finally decided to go on with the ratings and not the sales, I threw in some models. I had to adjust the cut-off value for the categories a few times, to make it easier to categorize the games. After deciding on 3 categories, I found the sweet spots and decided to change notebook after that. The first notebook was getting long and slow and it would be better to start anew for the modelling. I transferred the first few models I did to the bottom of the new notebook and then started the pre-processing. (still in the works)


- [ ] Finding the best model for the current situation
- [ ] Training the model for maximum efficiency
- [ ] Export a clean dataframe/CSV on Kaggle for other users
- [ ] Hosting the project on a website for easy utilization
- [ ] Updating the dataset every quarter or every year, for maximum efficiency of the predictions

<br>
And of course, updating the README.md everytime I add new features or the project gets closer to completion.
<br>
See the [open issues](https://github.com/benji02/capstone_project/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing
<!--
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
-->
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License
<!--
Distributed under the MIT License. See `LICENSE.txt` for more information.
 -->
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Benjamin Lavoie - [LinkedIn](https://www.linkedin.com/in/minh-hai/ ) - mihari.tran@gmail.com

Project Link: [https://github.com/benji02/capstone_project](https://github.com/miha-tran/Data_Science_Salaries_2004)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



