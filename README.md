# Data Science Job Salary EDA : Project Overview
* Estimated Data Science salaries to help new data science negotiate their income.  
* Identified key factors influencing salaries, namely job titles and years of experience.  
* Optimized the Catboost model with hyperparameter tuning to achieve the final desired outcomes.  

## Let's get started!
I will conduct a thorough Exploratory Data Analysis (EDA) on the dataset, and based on various scenarios, I will contemplate different approaches. Ultimately, I plan to utilize CatBoost for salary prediction.  

**In the explanations below, I will provide brief descriptions of some content. For more detailed information, please feel free to click on the notebook.** 
### Let's take a look at our dataset :  
Data Science Job Salaries Dataset contains 11 columns, each are:

1. **work_year:** The year the salary was paid.  
2. **experience_level:** The experience level in the job during the year  
3. **employment_type:** The type of employment for the role  
4. **job_title:** The role worked in during the year.  
5. **salary:** The total gross salary amount paid.  
6. **salary_currency:** The currency of the salary paid as an ISO 4217 currency code.  
7. **salaryinusd:** The salary in USD  
8. **employee_residence:** Employee's primary country of residence in during the work year as an ISO 3166 country code.  
9. **remote_ratio:** The overall amount of work done remotely  
10. **company_location:** The country of the employer's main office or contracting branch  
11. **company_size:** The median number of people that worked for the company during the year
#### The distribution of salaries.
![download](https://github.com/Elvis-YAL/Data-Science-Salary_EDA/assets/40426433/a9fa139e-6368-430b-b2d0-2040faa8425d)
#### Now, let's examine the distribution of data for each feature:  
![download](https://github.com/Elvis-YAL/Data-Science-Salary_EDA/assets/40426433/177f5252-8fe7-4cc4-bd00-fb95fd17cc01)
#### Also, we can explore the relationship between these features and salary:
![download](https://github.com/Elvis-YAL/Data-Science-Salary_EDA/assets/40426433/58178b32-4ac6-47d1-89e2-0f8024156610)
![download](https://github.com/Elvis-YAL/Data-Science-Salary_EDA/assets/40426433/de9a02c2-923d-44fc-942a-46e890a3a95a)
#### The most importace thing, salary distribution in different ob title:
![download](https://github.com/Elvis-YAL/Data-Science-Salary_EDA/assets/40426433/f81c616e-240a-432a-82fa-57f25be69c52)
### Explore these data is interesting, but I'd like to conclude here. If you have any more questions or need further assistance in the future, please don't hesitate to ask. Good luck with your data analysis endeavors!
