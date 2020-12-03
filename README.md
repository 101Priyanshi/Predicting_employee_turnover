Employee turnover, or employee turnover rate, is the measurement of the number of employees who leave an organization during a specified time period, typically one year. <br/>
<br/> The dataset has the following input features: <br/> <br/>
* satisfaction_level <br/>
* last_evaluation <br/>
* number_project - number of projects on which employee has worked<br/>
* average_montly_hours - hours spent by employee on an average in a month <br/>
* time_spend_company -  time from which employee has been a part of the company<br/>
* Work_accident - the number of accidents employee had<br/>
* promotion_last_5years -  umber of promotions empoyee had in last 5 years<br/>
* department - It can be either one of Sales, IT, accounting, HR, marketing, technical, management, support, product_mng, RandD <br/>	
* salary - takes values low/medium/high <br/>
The output feature "Quit" takes label 0 or 1 <br/>
* 0 - employee quits <br/>
* 1 - employee stays <br/>
It has 15000 instances <br/>
## Turnover frequency vs salary <br/>
![](salaryVSquit.png) <br/>
Employees with higher wages are less likely to quit as compared to their low and medium salary co-workers. Employees with lower salary are the most likely to quit. <br/>

## Turnover frequency vs department <br/>
![](deptVSquit.png) <br/>
Employees from sales department, technical department and support department are the most likely to quit so the company's management should pay special attention to these department so that they do not quit like maybe providing them some additional benefits or bonus. <br/>

## Feature Importance <br/>
![](FeatureImportance.png) <br/>
Satisfcation level plays a major role in determining whether or not a employee quits or not so the comapny's management should focus on increasing the average satisfaction level of employees.
Apart from that, number of projects, time spent in company, average monthly hours, last evaluation also play a major role in determining the employee turnover. <br/>
## ROC curve for random forest classifier <br/>
![](ROCrf.png) <br/>
## ROC curve for decision tree classifier <br/>
![](ROCdt.png) <br/>


