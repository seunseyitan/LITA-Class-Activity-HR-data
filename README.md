# LITA-Class-Activity
This is a project executed as class activity in Power BI during my data analysis learning period at LITA(Ladies in Tech Africa). 
This project contains employee data with focus on the attrition of the employees.  Attrition in this data refers to the employees who have left the organisation.
It aims at providing insights on rate of employees attrition in the organisation, causes of attrition, satisfaction of employees at the job roles, areas of improvement for the organisation to reduce attrition rate.

**DATASET**

** HR Data

**TOOLS USED**

** Power BI

**DATA VISUALIZATIONS**

** **EMPLOYEE TOTAL COUNT**:
The total sum of employee count was visualised using the card visual and dragging the **employee count** column head to build the visual.

The total employee count was **1,470**

** **EMPLOYEE CURRENT COUNT**:

The total sum of current employee count was visualised using the card visual and dragging the **CF_current Employee** column head to build the visual.

The total employee count was **1,470**


**  **ATTRITION COUNT**

The attrition count was obtained using conditional column 'If, else'

** **ATTRITION RATE**

The attrition rate was obtained through a **new measure** formula: 

**Attrition rate = SUM('HR data'[Attrition Count]) / SUM('HR data'[Employee Count])**
 visualised using the card visual.

 The attrition rate of employees is 16.12%

 
