# LITA-Class-Activity
This is a project executed as class activity in Power BI during my data analysis learning period at LITA(Ladies in Tech Africa). 
This project contains employee data with focus on the attrition of the employees.  Attrition in this data refers to the employees who have left the organisation.
It aims at providing insights on rate of employees attrition in the organisation, causes of attrition, impact of attrition on the organisation, satisfaction of employees at the job roles, areas of improvement for the organisation to reduce attrition rate.

**DATASET**

** HR Data

**TOOLS USED**

** Power BI (Query Editor, DAX Functions)

**DATA VISUALIZATIONS**

** **EMPLOYEE TOTAL COUNT**:
The total sum of employee count was visualised using the card visual and dragging the **employee count** column head to build the visual.

The total employee count was **1,470**

** **EMPLOYEE CURRENT COUNT**:

The total sum of current employee count was visualised using the card visual and dragging the **CF_current Employee** column head to build the visual.

The total sum of current employee count was **1,233**


**  **ATTRITION COUNT**


** **ATTRITION RATE**

The attrition rate was obtained through a **new measure** formula: 

**Attrition rate = SUM('HR data'[Attrition Count]) / SUM('HR data'[Employee Count])**
 visualised using the card visual.

 The attrition rate of employees is 16.12%

 **AVERAGE AGE OF EMPLOYEES**
 The average age of employees was calculated using the DAX Function 'Average()'.  The average age of employees is **'34 years old'** which was obtained using '**Average Age = AVERAGE('HR data'[Age])**.

**ATTRITION BY GENDER**
This provide insights on the total number of attrition based on gender and whether employees gender has a major impact on attrition rate or there is gender discrimination in the HR department. 
Attrition count by gender: Male (150) which is 63.29% of attrition, Female (87, 36.71%).
The rate of attrition for the male gender is higher than the female, this should be looked into to determine whether there is an underlying determining factor for this or not.

**


 

 
