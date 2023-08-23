# ml-assignment

## This is code section for macine learning assignment.

> In this study, we harness machine learning to predict salary categories based on various employee attributes. Using a dataset comprising features like job roles, experience, and educational qualifications, we evaluated multiple algorithms, with XGBoost emerging as a top performer. The model provided insights into key determinants of salary classifications, aiding stakeholders in making informed compensation decisions. The findings underscore the potential of predictive analytics in streamlining HR processes, setting competitive salary benchmarks, and enhancing organizational strategies.

## The dataset contains the following features:

> 
    work_year: The year of the data.<br>
    experience_level: The level of experience of the employee.<br>
    employment_type: Type of employment (e.g., full-time, contract).<br>
    job_title: Title of the job.<br>
    salary: Salary value.<br>
    salary_currency: Currency in which the salary is paid.<br>
    salary_in_usd: Salary converted to USD.<br>
    employee_residence: The residence of the employee.<br>
    remote_ratio: The ratio of remote work.<br>
    company_location: Location of the company.<br>
    company_size: Size of the company.<br>

## Before proceeding, we need to decide on how we want to categorize the salary. For instance:
>
 Low salary: < $50,000<br>
 Medium salary: $50,000 - $100,000<br>
 High salary: > $100,000<br>