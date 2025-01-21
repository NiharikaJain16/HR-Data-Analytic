# HR-Analytics Dashboard
A user-friendly dashboard for exploring and analyzing HR data to uncover hidden trends, data providing insights into employee attrition, demographics, and job satisfaction to inform HR decision-making and enhance employee performance.

## Problem Statement

This HR Data Analytics Dashboard provides a comprehensive and interactive solution of employee attrirtion and retention problems as these are critical concerns for HR-Professionals,with significant impact on organizational productivity,morale, and bottam-line performance.It helps the professionals to identify high-attrirtion departments and age groups.It helps to analyze employee distribution and demographics.


### Steps followed 
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check all columns.
- Step 3 : It was observed that in none of the columns errors & empty values were present. 
- Step 4 : In the report view, under the view tab, theme was selected. 
- Step 5 : visuals of three 'Card' in the visualizations pane and drop the 'employee' attribute as count, 'attrirtion' as count and 'age' attribute as average.
- Step 6 : visual of 'card' is applied and add attrirtion rate =  SUM('HR data'[attrirtion count]) / SUM('HR data'[Employee Count])         
- Step 7 :  visual of 'card' is applied and active employee = SUM('HR data'[Employee Count]) - SUM('HR data'[attrirtion count])
- Step 8 : A pie chart was also added to the report design area representing the department wise attrirtion.'department' is chosen as legend and attrirtion rate as values.
- Step 9 : A Bar Chart is added to show the no. of employee by age group. 'CF_Age band' chosen on X-Axis, 'Sum of employee count' chosen on Y-Axis, 'Gender' added as legend. 
- Step 10 : A matrix is added to show the job satisfaction rating with 'job role' as rows , 'job satisfaction' as columns and sum of employee count as values.
- Step 11 : A clustered bar chart is added to show education wise attrirtion rate  with attributes education field and attrirtion count attributes. 
- Step 12 : In the report view, under the insert tab, text boxes were added to the canvas, with the  name of attrirtion rate by gender for different age groups.
- Step 13 : Four Donat chart was added to show the same.
 - Step 14 : The report was then published to Power BI Service.

# Report Snapshot (Power BI DESKTOP)
![snapshot](https://github.com/user-attachments/assets/194b44a7-3835-4b0d-8040-6cbcec7ef06b)

