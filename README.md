# Capstone Project: Data Science 2024

## Project Overview

### Problem Area / Users
In the dynamic field of data science, understanding salary trends is crucial for professionals and organizations. This dataset provides insights into Data Science Salaries from 2020 to 2024, offering valuable information on trends, regional variations, and factors influencing compensation for data enthusiasts, researchers, and industry professionals.

### The Big Idea
Utilizing machine learning, the insights from the data can be harnessed to understand different factors:

1. **Predictive Modeling**: By analyzing past salary data, machine learning can predict future salary trends, aiding professionals and companies in making informed decisions about compensation.
   
2. **Feature Analysis**: Machine learning can explore various factors affecting salaries, such as skills, experience, and location, helping optimize compensation strategies.
   
3. **Anomaly Detection**: Machine learning algorithms can identify unusual patterns or outliers in salary data, facilitating the detection and rectification of errors.
   
4. **Personalized Recommendations**: Leveraging individual profiles, machine learning can offer tailored advice on career development, skill enhancement, and negotiation tactics to improve salaries.
   
5. **Regional Disparities Analysis**: By analyzing data from different regions, machine learning can uncover disparities in salaries, providing insights into geographical variations in compensation.

### Impact
This project is anticipated to bring tangible benefits to both society and businesses. By leveraging advanced technology, the aim is to assist companies in setting salaries more effectively, thereby increasing employee satisfaction and reducing turnover rates. This could potentially save businesses expenses associated with hiring and training new staff. Additionally, by streamlining the salary negotiation process, both employees and companies can save valuable time. Moreover, offering fair and competitive pay can help companies attract top talent, giving them a competitive edge in the market. In essence, the project aims to enhance the salary determination process for all stakeholders involved.

### The Data
The primary dataset was sourced from ai-jobs.net and LinkedIn.com, consisting of:

- **Dataset 1**: 6,600 rows and 11 columns, including Company Name, Job Title, Location, Contract Type, Experience Level, Sector, Description, Applications Count, Published At, and Salary information.
- **Dataset 2**: 5,547 rows and 9 columns, containing features such as Title, Company, Description, Onsite/Remote status, Salary, Location, Criteria, Posted Date, and Link.
- **Dataset 3**: 7,927 rows and 15 columns, featuring attributes like Job ID, Job Title, Location, Company ID, Company Name, Work Type, Full-time Remote status, Number of Employees, Number of Applications, Posted Day Ago, Alumni status, Hiring Person details, LinkedIn Followers of the hiring person, Hiring Person's LinkedIn profile link, and Job Details.

## Data Processing
Using Anaconda to create a new environment for the Jupyter notebook.
1. Create a New Environment: Create a new conda environment using the command:
           conda create --name myenv
2. Activate the Environment: Activate the newly created environment using:
        conda activate myenv
3. Launch Jupyter Notebook: Start a Jupyter Notebook 
4. Write Python Script: Write a Python script in the Jupyter Notebook or any text editor to read, clean, and merge the CSV files using the pandas library.
5. Save the Cleaned Data: Save the cleaned data as a new CSV file using the pandas DataFrame to_csv method.
6. Deactivate Environment: After completing the task, deactivate the conda.
7. Export Environment (Optional): If you want to share the environment with others, export it to a YAML file using:
         env export > environment.yml
