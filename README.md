# Data-Science-and-Data-Engineering-Job-Roles

[![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
![Static Badge](https://img.shields.io/badge/Scikit-%23F7931E?style=for-the-badge&logo=scikit-learn&logoColor=%23F7931E&color=blue)
![Static Badge](https://img.shields.io/badge/Scipy-%238CAAE6?style=for-the-badge&logo=scipy&logoColor=%238CAAE6&color=yellow)
![Static Badge](https://img.shields.io/badge/Numpy-%23013243?style=for-the-badge&logo=Numpy&logoColor=%23013243&color=blue)
![Static Badge](https://img.shields.io/badge/MySQL-%234479A1?style=for-the-badge&logo=MySQL&logoColor=%234479A1&color=black)
![Static Badge](https://img.shields.io/badge/Plotly-%233F4F75?style=for-the-badge&logo=Plotly&logoColor=%233F4F75&color=black)


## Project Overview

The project focuses on creating a dynamic database to predict future opportunities in Data Science and Data Engineering roles, addressing the job market's needs. It aims to provide a platform for students and prospective employees to identify suitable job roles by leveraging various features such as location, stock options, current salary, years of experience, educational level, and more. This initiative is crucial due to the significant impact of Data Science in modern business operations and the ever-evolving nature of the field.

![Logo](Images/Logo.png)

## Data Description

The data utilized in this project was sourced from multiple locations:

**Twitter** : Data regarding Data Science and Data Engineering roles was scraped using the Twitter API through the tweepy library.

**Kaggle and Other Websites**: Additional datasets were obtained from Kaggle and other websites to enrich the database. These datasets were merged into a comprehensive dataset stored across four tables within a SQLite database.


## Methodology

### Data Collection: 

Data was collected via web scraping Twitter and other sources, ensuring a rich dataset representative of current job market trends in Data Science and Engineering.

**Tools Used**: Python (for scripting and data manipulation), Jupyter Notebook (for executing and visualizing the processes), and SQLite (for database operations).

**Process**: Data from various sources was scraped, cleaned, and normalized to ensure it met the 1NF, 2NF, and 3NF normalization standards where applicable, enhancing the database's efficiency and query performance.


### Database Design and Implementation: 

A robust database schema was created to handle diverse data types and relationships effectively.

**SQL Operations**: Included creating, inserting, and utilizing SQL joins to integrate and manipulate the data. View statements were also implemented to facilitate specific use case queries.

**Normalization Practice**: Apart from integrating the initial data, a separate dataset was normalized for practice, applying 1NF, 2NF, and 3NF to ensure optimal database design.


## Findings and Evaluation 

### Data Insights: 
The project successfully demonstrated how to extract actionable insights from complex datasets, particularly focusing on the job market trends for Data Science and Engineering roles.

### Visualizations: 
Various graphs (line graphs, box plots, violin graphs, pie charts) were plotted to visually represent the data, providing intuitive access to data insights like salary distributions, popular roles, and job availability over time.

**Popular DS Roles**:
![Popular](Images/Popular%20DS%20Roles.png)

**Top Roles Based On Average Pay**:
![AveragePay](Images/Top%2010%20Based%20On%20Average%20Pay.png)

**Salary Distribution**:
![SalaryDistribution](Images/Salary%20Distribution.png)

**Experience**:
![Experience](Images/Salaries%20By%20Experience.png)

**Yearly Distribution**
![Year](Images/Salaries%20By%20Year.png)


## Conclusion

The project achieved its goal of creating a comprehensive database system that can predict and illustrate future job market trends in Data Science and Data Engineering. This system serves as a valuable tool for students and job seekers by providing clear, actionable data on potential career paths. Additionally, the project refined data handling and SQL skills, particularly in database normalization and complex query formulation, which are critical competencies in the data-centric roles explored within the project.

