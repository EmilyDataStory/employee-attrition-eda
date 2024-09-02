# Employee Attrition Analysis Project ![image](https://github.com/user-attachments/assets/02cd653b-d013-488f-a95c-1cf8d4e9801b)


## Project Significance
This project demonstrates the application of data analysis techniques to solve real-world business problems. While focused on employee attrition, the methodologies and skills showcased here are transferable to various domains:

- Customer churn analysis in telecommunications or subscription-based services
- Patient readmission prediction in healthcare
- Student retention strategies in education
- Environmental studies on factors contributing to biodiversity loss or climate change impacts
- Product adoption and customer behaviour in market analysis

The ability to clean data, perform exploratory analysis, create insightful visualisations, and derive actionable recommendations is valuable across industries. This project exemplifies how data-driven insights can inform strategic decision-making in any field.

## Business Context
Employee attrition is a critical issue for organisations, impacting costs, productivity, and organisational stability. This project analyses factors contributing to employee attrition to help develop targeted retention strategies.

## Questions To Explore
What factors are associated with employee attrition, and how are they related to turnover patterns in our workforce?

1. Which employee segments show higher attrition rates, and what characteristics are associated with these segments?
2. What job-related factors are correlated with employee attrition and retention patterns?

## Dataset
The analysis uses an IBM HR Analytics Employee Attrition & Performance dataset, featuring:
- 1,470 employee records
- 35 attributes per employee
- Includes demographics, job-related factors, and satisfaction metrics
  ![image](https://github.com/user-attachments/assets/200d20e6-ffdc-4145-95e7-99b7684e43bb)

- Dataset Source & Reference:
> https://www.kaggle.com/datasets/thedevastator/employee-attrition-and-factors/data?select=HR_Analytics.csv.csv
> https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data

## Exploratory Data Analysis (EDA)
This project conducts an EDA using Python (Jupyter Notebook) to gain deeper insights into the dynamics affecting employees. Key visualisations include:

* Histograms / Boxplots for continuous variable distribution analysis.
 ![image](https://github.com/user-attachments/assets/7907995c-ef87-430b-a909-be5b5da8ff09)
 
* Bar charts for categorical data comparison.  
 ![image](https://github.com/user-attachments/assets/a88b4dca-8a01-4203-a0ac-8c6e079544c2)

* Correlation matrices to identify attribute relationships.  
 ![image](https://github.com/user-attachments/assets/91804c3c-46e7-42f4-839b-7384fa26d986)

## Python Packages Used
* Pandas & NumPy for data manipulation
* Matplotlib & Seaborn for data visualisation
* Scipy for statistical testing

## Key Findings 
### 1. Which employee segments show higher attrition rates, and what characteristics are associated with these segments?
* Sales representatives and Laboratory Technicians 
* Young employees in their early 20s
 ![image](https://github.com/user-attachments/assets/e6708cc5-4fa6-416f-affa-7d228f31a70b)
* Single employees
  
  ![image](https://github.com/user-attachments/assets/e1491aba-d8fb-4598-a8a9-32b5d489d7b0)
* Employees with longer commutes or more varied job histories
 ![image](https://github.com/user-attachments/assets/1c87c57d-6531-432a-9d00-d02e4c209c42)

### 2. What job-related factors are correlated with employee attrition and retention patterns?
* Lower job levels, job involvement & monthly income
  ![image](https://github.com/user-attachments/assets/fb594309-347d-4a17-846f-325718e944f2)

* Overtime work
  
  ![image](https://github.com/user-attachments/assets/19159d00-3599-4a30-b319-9e1ed040c896)

* Critical period in the first 2.5 years
 ![image](https://github.com/user-attachments/assets/e09eeade-c9f0-4521-ae0e-8ae15f70a329)

* Salary increases alone don't show strong correlation with improved retention
  ![image](https://github.com/user-attachments/assets/dc1eb973-2242-44cf-b2b1-817d82d7f6b4)

* 50% of employees who left were promoted within the past 2 years
 ![image](https://github.com/user-attachments/assets/2a3e0f30-e53d-4bd7-a3de-10f760cfe8d9)


## Recommendations
1. Develop targeted retention strategies for high-risk groups
2. Strengthen onboarding and integration programmes for the first 2.5 years of employment or new role transitions
3. Investigate factors beyond compensation that may influence retention, especially for recently promoted employees

## Repository Contents
- `hr_employee_attrition_eda_by_Emily.ipynb`: Jupyter notebook with full analysis
- `IBM-HR-Employee-Attrition.csv`: Original dataset
- `hr_attrition_analysis_eda_by_emily.pptx`: Presentation slides


## Future Work
- Conduct predictive modelling to forecast attrition risk
- Perform time-series analysis if temporal data becomes available
- Expand the dataset to include more recent and company-specific information


## Conclusion
This project underscores the power of data analysis in understanding and mitigating employee attrition. The insights and methodologies applied here are not only pivotal for enhancing employee retention but are also versatile enough to be adapted to other fields such as customer retention, student performance tracking, or any area requiring analysis of turnover and engagement.

## About the Author
Emily Huang - Data Science enthusiast with a passion for turning data into actionable insights. 

Feel free to connect with me via my [LinkedIn Profile](www.linkedin.com/in/emily-huang-3021212as)
