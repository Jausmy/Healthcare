# Data Portfolio: Healthcare Dataset Dashboard
![Healthcare-Project-Main-Image](Assets/Images/Healthcare%20Main%20Image.jpg)

## Overview
This report presents a comprehensive analysis of the financial performance of a healthcare centre and provides insights into the efficiency and effectiveness of its healthcare providers. By examining key performance indicators (KPIs) and trends, we aim to provide a clear understanding of the centre's financial health and identify areas for potential improvement.

## Executive Summary
By examining key metrics such as billing amounts, medication costs, treatment costs, insurance coverage, and out-of-pocket expenses, we identified key trends and areas for potential improvement. A key insight from the analysis is that Cardiology consistently emerged as the department with the highest overall billing amount, while Pediatrics had the lowest [(see Analysis of Financial Performance by Department)](#Analysis-of-Financial-Performance-by-Department). Based on the analysis, we recommend focusing on optimizing resource allocation and service delivery in high-revenue departments like Cardiology, while exploring strategies to improve efficiency and potentially increase revenue in lower-performing departments like Pediatrics. By implementing these recommendations, the healthcare centre can potentially increase revenue by 5% and improve overall financial performance [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).

## Methodology
### Data Sources
The primary data source for this analysis is a healthcare dataset comprising 8 tables:
-	Visits: Contains detailed information on patient visits, including date, patient ID, provider ID, department ID, diagnosis, procedure, insurance, service type, costs, and patient satisfaction.
-	Providers: Provides information on healthcare providers, including name, gender, nationality, and age.
-	Procedures: Lists the different medical procedures performed at the centre.
-	Patients: Contains demographic information on patients, including gender, age, city, and race.
-	Insurance: Lists the insurance providers used by patients.
-	Diagnosis: Lists the different diagnoses made at the centre.
-	Departments: Lists the various departments within the healthcare centre.
-	Cities: Provides a list of cities and states where patients reside.

![Visits-Table](Assets/Images/Healthcare%20-%20Data%20Source%20(Visits).png)

![Providers-Table](Assets/Images/Healthcare%20-%20Data%20Source%20(Providers).png)

![Procedures-Table](Assets/Images/Healthcare%20-%20Data%20Source%20(Procedures).png)

![Patients-Table](Assets/Images/Healthcare%20-%20Data%20Source%20(Patients).png)

![Insurance-Table](Assets/Images/Healthcare%20-%20Data%20Source%20(Insurance).png)

### Tools Used
The following tools were used for data analysis and visualization:
-	Microsoft Excel – Data familiarization and exploration
-	Microsoft PowerBI – Data visualization

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of billing amounts, medication costs, and treatment costs across different departments, procedures, and patient demographics.

### Data Analysis Techniques
The following data analysis techniques were employed:
-	KPI Analysis: We calculated key performance indicators (KPIs) such as total billing amount, average billing amount per visit, total medication cost, average medication cost, total treatment cost, average treatment cost, total insurance coverage, average insurance coverage, total out-of-pocket expenses, and average out-of-pocket expenses. This involved aggregating data from the Visits table and calculating relevant metrics to assess the financial performance of the healthcare centre.
-	Trend Analysis: We analyzed trends in billing amounts and patient visits over time, specifically by month of the year. This involved aggregating data by month to identify any seasonal patterns or significant fluctuations in financial performance.
-	Comparative Analysis: We compared financial performance and patient demographics across different categories such as gender, race, diagnosis, and city. This involved grouping data by these categories and calculating relevant KPIs to identify any disparities or significant differences in healthcare utilization and costs.
-	Diagnostic Analysis: This analysis was used to identify the root cause of the low billing amount in October. By examining various factors such as patient demographics, diagnoses, and service types, we aimed to understand the underlying reasons for the low financial performance in that specific month.

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of the healthcare centre's performance and identify areas for improvement. These techniques include:
-	Predictive Modeling: This technique can be used to forecast future patient volumes, predict potential revenue, and optimize resource allocation. By building statistical models based on historical data and relevant factors, we can anticipate future trends and make proactive decisions to improve efficiency and financial performance.
-	Segmentation Analysis: This method involves dividing patients into distinct groups based on shared characteristics such as demographics, healthcare needs, patient pre-existing conditions, or behavioral patterns. By understanding the unique needs and preferences of different patient segments, we can tailor services, improve patient satisfaction, and optimize resource allocation.

## Analysis of Financial Performance
### Overall KPIs
![Overall-Dashboard](Assets/Images/Healthcare%20-%20Overall%20Dashboard.png)

The overall financial performance of the healthcare centre is summarized by the following KPIs:

|KPI|Value|
|---|---|
|Total Billing Amount|$3.36M|
|Average Billing Amount per Visit|$674.86|
|Total Medication Cost|$546k|
|Average Medication Cost|$109.21|
|Total Treatment Cost|$2.63M|
|Average Treatment Cost|$526.08|
|Total Insurance Coverage|$2.23M|
|Average Insurance Coverage|$456.04|
|Total Out-of-Pocket Expenses|$1.13M|
|Average Out-of-Pocket Expenses|$227.26|
|Total Room Charges|$180k|
|Average Room Charges|$36.12|

### Analysis of Financial Performance by Department
Cardiology had the highest overall billing amount by department with $846,925.00 (25.2% of total billing), while Pediatrics had the lowest overall billing amount by department with $434,450.00 (12.9% of the total billing). This suggests that Cardiology is a key revenue driver for the healthcare centre, while Pediatrics may require further investigation to understand the reasons for its lower billing amount.

![Billing-By-Dept](Assets/Images/Healthcare%20-%20Total%20Billing%20By%20Dept.png)

### Analysis of Financial Performance by Procedure
X-rays had the highest overall billing amount by procedure with $1,053,529.00, while blood tests had the lowest overall billing amount by procedure with $414,952.00. This indicates that X-rays are a significant contributor to the centre's revenue, while blood tests may require further analysis to understand their lower billing amount.

![Billing-By-Procedure](Assets/Images/Healthcare%20-%20Total%20Billing%20By%20Procedure.png)

### Analysis of Financial Performance by Service Type
Outpatient service type had the highest percentage of total billing between emergency and inpatient in every diagnosis. Inpatient service type had the lowest percentage of total billing between emergency and outpatient for every diagnosis category except for hypertension and appendicitis, where emergency had the lowest total billing amount. This suggests that outpatient services are a major source of revenue for the healthcare centre, while inpatient services may require further examination to optimize resource allocation and potentially increase revenue.

![Billing-By-Service](Assets/Images/Healthcare%20-%20Total%20Billing%20By%20Service.png)

### Analysis of Financial Performance by Month
January had the highest total billing with $852.14k (avg. $689.99), while October had the lowest billing with $29.20k (avg. $648.82) due to a low number of patients. This highlights a potential seasonal trend in healthcare utilization and revenue generation. Further investigation is needed to understand the factors contributing to the low patient volume in October and explore strategies to potentially increase revenue during that month.

![January-Performance](Assets/Images/Healthcare%20-%20Jan%20KPIs.png)

![October-Performance](Assets/Images/Healthcare%20-%20Oct%20KPIs.png)

### Analysis of Financial Performance by City
Birmingham had the highest average billing amount per visit with $703.08, while Leeds had the lowest average billing amount per visit with $638.75. This suggests potential variations in healthcare costs or service utilization across different cities. Further analysis is needed to understand the factors contributing to these differences.

![Birmingham-KPIs](Assets/Images/Healthcare%20-%20Birmingham%20KPIs.png)

![Leeds-KPIs](Assets/Images/Healthcare%20-%20Leeds%20KPIs.png)

### Analysis of Financial Performance by Patient Demographics
The analysis revealed some differences in financial performance based on patient demographics:
-	Gender: Female patients had a slightly lower average billing amount ($674.38) compared to male patients ($675.34).

![Female-KPIs](Assets/Images/Healthcare%20-%20Female%20KPIs.png)

![Male-KPIs](Assets/Images/Healthcare%20-%20Male%20KPIs.png)
  
-	Race: Black patients had the highest average billing amount ($686.66), while Asian patients had the lowest ($664.39).
These differences may warrant further investigation to understand the underlying factors and ensure equitable healthcare access and affordability for all patient demographics.

![Black-KPIs](Assets/Images/Healthcare%20-%20Black%20KPIs.png)

![Asian-KPIs](Assets/Images/Healthcare%20-%20Asian%20KPIs.png)

## Provider Insights
The analysis of provider performance revealed the following insights:
-	Provider Efficiency: Dr. Sade Kikiola saw the most patients (1873), while Dr. Johnson Grek saw the least (445).

![Dr.-Sade-KPIs](Assets/Images/Healthcare%20-%20Dr.%20Sade%20KPIs.png)

![Dr.-Johnson-KPIs](Assets/Images/Healthcare%20-%20Dr.%20Johnson%20KPIs.png)

-	Treatment Costs: Dr. Emma Jones had the highest average treatment cost ($539.80), while Dr. Olu Abisola had the lowest average treatment cost ($520.84).

![Dr.-Emma-KPIs](Assets/Images/Healthcare%20-%20Dr.%20Johnson%20KPIs.png)

![Dr.-Olu-KPIs](Assets/Images/Healthcare%20-%20Dr.%20Olu%20KPIs.png)

## Recommendations
Based on the analysis of financial performance and provider insights, the following recommendations are proposed:
-	Optimize Resource Allocation: Allocate resources strategically to high-revenue departments like Cardiology to maximize efficiency and potentially increase revenue.
-	Improve Efficiency in Lower-Performing Departments: Investigate the reasons for lower billing amounts in departments like Pediatrics and explore strategies to improve efficiency and potentially increase revenue. This could involve reviewing staffing levels, optimizing service delivery processes, or exploring opportunities to expand service offerings.
-	Enhance Patient Experience: Focus on improving patient satisfaction scores across all departments by implementing initiatives such as reducing wait times, improving communication, and providing personalized care.
-	Address Disparities in Healthcare Access: Investigate and address any disparities in healthcare access or affordability based on patient demographics to ensure equitable healthcare delivery.
-	Monitor Trends and Adapt: Continuously monitor key performance indicators and trends to identify areas for improvement and adapt strategies accordingly.

## Potential Impact of Recommendations
By implementing these recommendations, the healthcare centre can anticipate the following positive outcomes:
-	Increased Revenue: Optimizing resource allocation, improving efficiency, and enhancing patient experience can potentially lead to a 5% increase in revenue within the next year.
-	Improved Financial Performance: By effectively managing costs and increasing revenue, the healthcare centre can improve its overall financial performance and sustainability.
-	Enhanced Patient Satisfaction: Focusing on patient-centered care and addressing disparities in healthcare access can lead to increased patient satisfaction and loyalty.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:
-	Data Availability: The analysis is limited by the available data. Access to more granular data, such as detailed information on operating costs, staffing levels, and patient feedback, would allow for a more comprehensive analysis and more specific recommendations.
-	External Factors: External factors such as changes in healthcare policies, economic conditions, and competitor actions can influence the healthcare centre's financial performance and should be considered in future analyses.

## Key Takeaways
This analysis provides valuable insights into the financial performance and provider efficiency of the healthcare centre. Here are the key takeaways:
-	Cardiology is a key revenue driver: Cardiology generated the highest revenue among all departments, highlighting its importance to the centre's financial health.
-	Outpatient services contribute significantly to revenue: Outpatient services consistently generated a higher percentage of total billing compared to inpatient and emergency services.
-	Potential for improvement in Pediatrics: Pediatrics had the lowest overall billing amount, suggesting a need for further investigation and potential optimization strategies.
-	Seasonal trends in financial performance: January had the highest total billing, while October had the lowest, indicating potential seasonal variations in healthcare utilization.
-	Variations in billing amounts by city: Birmingham had the highest average billing amount per visit, while Leeds had the lowest, suggesting potential differences in healthcare costs or service utilization across different cities.

By implementing the recommendations outlined in this report and continuously monitoring key performance indicators, the healthcare centre can optimize its operations, improve financial performance, and enhance patient care.
