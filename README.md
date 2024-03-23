# Employee Attrition Analysis
Employee Attrition is a term used to describe the process or rate at which employees leave an organization or company, either voluntarily (such as resignations) or involuntarily (such as layoffs). It is an important indicator for companies to understand their workforce stability, measure employee satisfaction and engagement levels, and identify factors influencing employee turnover.

## The Main Problem
Out of the 4,410 employees, 16.1% or 710 employees underwent attrition. If the 710 employee attrition is multiplied by $4,700 dollars, the cost amounts to $3,3337,000. So, high employee attrition causes high recruitment costs.

### **Problem Summary**
- Background : The company wants to know why employee to attrite and which variables need to be addressed immediately. <br>
- Goals : Decrease the attrition  rate from 16.1% to at least under 10% in order to reduce cost. <br>
- Objectives : Create a model machine learning to predict potential causes of employee attrition. <br>
- Business Metrics : Attrition Rate (%)

## Exploratory Data Analysis
- **Attrition by Marital Status** <br>
The majority of employees are Married at 45.8%, the lowest are Divorce at 22.2%. The highest attrition rate is Single at 12.5% or 359 employees.

- **Attrition by AgeGroup** <br>
The majority of employees are Middle at 42.1%, the lowest are Elderly at 9.7%. The highest attrition rate is Middle at 13.7% or 472 employees.

- **Attrition by TotalWorkingYears** <br>
The majority of employees are Medium Level at 52%, the lowest are Entry Level at 10.5%. The highest attrition rate is Medium Level at 15.7% or 355 employees.

## Data Preprocessing Flow
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/DPF.jpg)

## Modelling
### **Model Comparison**
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/ME%201.jpg)
Recall measures the ratio between the number of employee that are predicted to attrite who actually left the  company, and the number of employee that are predicted to stay but actually left the company. Maximizing recall means minimizing the number of employee who are incorrectly predicted to not attrite.
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/ME%202.jpg)

## Feature Importance
The most influential features in the model are MaritalStatus_Married, Age, and TotalWorkingYears.
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/FI%202.jpg)

## Recommendation
**1. Recomendation  for MaritalStatus** <br>
   - Develop employee benefits programs by offering additional benefits such as family health insurance, additional leave for family events, or educational support for employees' spouses or children.
   - Develop a family support program that includes family counseling, financial planning assistance, or work time flexibility to help employees balance their work and personal lives.<br>
   
**2. Recomendation  for Age** <br>
   - Develop generation-specific training programs, cross-generational mentoring, or flexible online learning opportunities.
   - Develop mental health counseling, physical fitness programs, or health seminars for age-relevant issues.
   - Offer additional retirement savings options or health insurance with additional coverage for employees approaching retirement. <br>
   
**3. Recomendation  for TotalWorkingYears**
   - Develop additional training, skill development courses, or mentoring programs to help employees improve their competencies and advance their careers.
   - Design internal knowledge management programs or collaboration forums to facilitate the exchange of knowledge and experience between employees.
   - Develop special retention programs that offer incentives or additional benefits to experienced employees to retain them in the long term. <br>

## Business Impact
Before the model, the attrition rate was 16.1%, and it decreased by 7.7% after the model, resulting in an attrition rate of 8.4%.
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/BI%201.jpg)
![alt Text](https://github.com/shaniaw16/Employee-Attrition-Analysis/blob/main/BI%202.jpg)
