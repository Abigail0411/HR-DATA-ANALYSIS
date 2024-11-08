# HR-DATA-ANALYSIS
---

## Context
[Project Overview](#project-overview)

[Project Objectives](#project-objectives)

[Data Sources](#data-sources)

[Data Tool Used](#data-tool-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

## Project Overview
---
This project focuses on creating a data-driven approach to analyze attrition rates within a company. The project seeks to uncover trends that forecast future attrition and help Hr make informed decions by examining the employee demographics, performance and othey key metrics.

## Project Objectives
---
This project focuses on analyzing factors that contribute to employees attrition such as the education field, job role and  job satisfaction. It also focuses on identifying and predicting future attrition risk and provide actionable insights and strategic recommendations for HR to improve on employee satisfaction and reduce attrition rates.
## Data Sources
The data used was collected from the HR of Cloud Wares company.
- Data Collected
  * Attrition
  * Business Travel
  * CF_age band
  * CF_attrition Level
  * Education Field
  * Department
  * Employee Number
  * Gender
  * Job Role
  * Marital Status
  * Overtime
  * No. of Training times
  * CF_current employee
  * Daily Rate
  * Distance from home
  * Education
  * Employee Count
  * Environment satisfaction
  * Hourly rate
  * Job Involvement
  * Job Level
  * Job Satisfaction
  * Monthly Income
  * Monthly rate
  * No. of Companies Worked for
  * Percent Salary Hike
  * Performance rating Relationship Satisfaction
  * Standard Hours
  * Total Working Years
  * Stock Option Level
  * Work Life Balance
  * Work at Company
  * Years in Current Role
  * Years since Last Promotion
  * Years with Current manager

## Data Tool Used
---
Power Bi: Used to create interactive visualization on dashboard.

## Data Cleaning and Preparations
Column quality check was carried out on the data tocheck for any errors and make sure it it free of errors

## Data Analysis
---
•	Dax Functions 
1.	Measure
   i. To calculate Attrition rate
  	 ```dax
    Attrition Count = Sum(Attrition Count) / Sum(Employee Count)
    ```
    ii. To calculate Average age of the employees
 	 ```dax
    Average Age = Avg(Age)
    ```
2.	Conditional Function
   i. Used to convert Attritiom text to numbers to find the attrition count
  	
   |Heading 1|Heading 2|Heading 3|Heading 4|
   |--------|--------|--------|--------|
   |Column Name|Operator|Value|Output|
   |Attrition|equals|Yes|1|
   |Else 0|
  	
## Data Visualization
---
## POWER BI Dashboards
![Screenshot (174)](https://github.com/user-attachments/assets/f5667a6d-2dfc-4ce3-8d56-8c96886af
![Screenshot (173)](https://github.com/user-attachments/assets/cf4bfc74-cf96-42d3-b847-fe815692889a)
af9)


## Filtered Dashboard for Life Sciences Education Field
![Screenshot (167)](https://github.com/user-attachments/assets/e8bdf9a3-d615-4777-b325-74c2e09d1684)
## Filtered Dashboard for Human Resources Education Field
![Screenshot (168)](https://github.com/user-attachments/assets/d2f3d15d-6da9-4e5c-8411-c4a91617acf8)
## Filtered Dashboard for Manger's Role
![Screenshot (169)](https://github.com/user-attachments/assets/429563a1-18e0-4cae-bcaf-e32e25c5ea04)
## Filtered Dashboard for Master's Degree Education Level
![Screenshot (165)](https://github.com/user-attachments/assets/34a4b0b3-cd52-4338-b4d4-eb155a29e87c)
## Filtered Dashboard for Bachelor's Degree Education Level
![Screenshot (166)](https://github.com/user-attachments/assets/7ba8b0af-b074-40f6-9dfb-b78062b1dca1)

## 1. Attrition by Education Field
### i. Inferences
-	Life Sciences and Medical field: High attrition might be due to strees andburnout which might indicate a need for worklife balance. 
-	Marketing: Marketing often experience moderate attrition rate due to frequent shifts in company focus, client demands and competitive pressure. The attrition by marketing field might be due to high competition.
-	Technical Degree: The attrition count can be due to strong external job opportunities or remote work options and also the need for growth opportunities or higher salaries.
-	HR: Experiences lower attrition as they focus on stability and employee engagement, but should be monitored for any signs  of stagnation. 
-	Others: this represents employees with varied education background, they experience low attrition in this category if the specialized skills and market demand is low.
### ii. Strategic Recommendation
-	For fields like Life sciences, medical and technical degrees, Cloud Wares should offer advanced training programs to retain highly skilled employees.
-	To reduce burnout, they can provide flexible work options and work load management strategies.
-	For marketing field where creativity is essential, the company should implement incentives and reward systems based on performance and innovation so as to improve on retention.
### iii. Conclusion
- Effective retention strategies should focus on aligning employee expectations and aspirations, Cloud Wares can create an environment where employees will feel valued and motivated to stay. 

## 2. Attrition count by Job Roles and Job Satisfaction
### i. Inferences
- Satisfied and Very Satisfied: Most of the employees that left the company were satisfied with their job roles but still left the company. This may be due to the following; better opportunities for roles with greater growth potential, or when they receive attractive offers with higher incentives or changes in personal goals.
- Dissatisfied and Very Dissatisfied: A total of 46 and68 employees were dissatisfied and very dissatisfied with their roles respectively. This may be due to lack of career growth, imbalance work life or inadequate compensation or incentives. 
### ii. Strategic Recommendations
- Addressing Very Dissatisfied and Dissatisfied roles: The HR team should focus on addressing the root cause of dissatisfaction in the roles which may involve adjusting incentives and salaries, redefining responsibilities as well as providing clear career path.
- Maintain Satisfaction for the Satisfied and Very Satisfied roles: The company can retain its skilled employees by implementing recognition programs and promoting positive workplace culture.
- The HR team should request for regular feedback so as to shape the workplace in a way that would help prevent high levels of dissatisfaction.
### iii. Conclusion
Addressing dissatisfaction drivers and maintaining satisfaction among the roles will lead to a more motivated and stable workforce.

## 3. Attrition by Department
## i. Inferences
- Research & Development: Has the highest attrition rate with more of the employees satisfied with their Job. This may indicate or suggest lack of clear career  growth or the perception of Limited growth in the company.
- Sales: The attrition count could arise from the stress that comes with high performance expectations and the pressures  to meet  quotas. 
- HR has the least attrition count but with most of them very dissatisfied with the job.  This could indicate emotional  fatigue, workload or burnout due to the fact that HR personnels manage the difficult conversations and are  expected to handle all issue pertaining the employees’ behavior. 
### ii. Strategic Recommendations
- The HR team in the company should enhance career development opportunities for the R&D department by providing training programs, mentorship and clear paths for promotions to encourage the employees.
- They should also adjust salaries and incentives to motivate the employees leading to retention.
- For the Sales department: Restructuring sales incentives to align with achievable targetds and reward high performers adequately.
- Consider increasing staffs for HR Department to help reduce workload so as to increase their ability to focus on strategic initiatives.

### iii. Conclusion
Addressing attrition in each departments requires a targeted approach tailored to each department's needs. The recommendations stated above should be implemented to ensure long-term retention.


## 4. Attrition by Environment Satisfaction
### i. Inferences
- More employees that left were very dissatisfied with their work environment, likely due to lack of support by management, issues with work culture or inadequate facilities to work effectively and efficiently
- The satisfied group probably left the company because of better opportunities and greater rewards.
### ii. Strategic Recommendations
Workplace environment satisfaction is very crucial to retaining employees. The following should be taken into consideration and implemented;
- For Very Dissatisfied and Dissatisfied Employees:
   * Improvement of their work space should be considered so as to create a comfortable atmosphere.
   * Implementation of regular survey sessions to identify specific environmental issues inorder to act on them as soon as possible.
- For Satisfied employees:
   * Offer career development opportunities such as trainging staffs to keep the employees engaged and connected to the growth of the company.
   * Implement regular recognition on achivements and offer rewards to increase their satisfaction.
### iii. Conclusion
Environment satisfaction in workplaces is a critical factor in employees retention. High levels of dissatisfaction lead to greater turnover while satisfaction leads to employee stability. Improving on physical conditions, address specific issues laid out by employees can reduce attrition in a company.

## 5. Attrition by Age Group and Gender
## i. Inferences
As shown In the donut chart, male dominated the attrition count with a total of 150 out of 237.
- #### Age group Under 25
   * At this stage, employees are seeking for faster advancements in that they prioritize their experience and might leave if  they do not perceive limited growth in the role they were assigned.
   * In a case where the young employees posses skills that are of high demand such as technology, medical, they tend to receive attractive offers from other companies.
   * Young employees priorities flexibility and work-life balance and do not like being stressed. If the company does not offer flexible hours of work, they tend to leave.
- #### Age group 25-34
   * This age group has the highest number of attrition. At this stage, employees are seeking for jobs and roles with growth or leadership opportunities. The attrition count at this age may indicate that the employees felt stagnant in their career.
   * As employees gain experience and skills, they expect to receive salary that matches their skills or reflects their value. They leave if they find better paying jobs.
   * Employees in this age group may have just started a family making work life balance a significant factor. Attrition increases if the roles are too involving.
- #### Age group 35-44
   *	Attrition in this age group might be due to them not having promotions or leadership roles.
   * It could also indicate that the have more financial responsibilities than their pay and they leave if the job is not paying them well.
- #### Age group 45-54
   * Attrition in this age group may indicate them not feeling satisfied work or the roles are not aligning to their expertise or due to them not having promotions or leadership roles.
   *It might also indicate that the compensation they receive does not meet their financial responsibility.
- #### Age group Over 55
   * This age group has the least attrition count of 11. At the age, attrition my indicate that the employees are ready and willing to retire and may want to work with flexibility.
### ii. Strategic Recommendations
- The HR can consider offering mentorship and skills development for the young employees so as to satisfy their need for career advancements.
- They should benchmark salaries and benefits against industry standards regularly, proving incentives and bonuses to help retain employee.
- Support and provide work-life balance by promoting work options and flexible work hours.
- They should also offer leadership opportunities, professional development programs and also creating a pathway for upward movement within the company for employees aged 45 and above.
### iii. Conclusion
Attrition among age group results from the need for stability, work-life balance and financial stability. If all those issues are address then the company will experience less attrition rate.



