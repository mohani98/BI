# HealthCare:Advancing Healthcare Analysis through Data Insights:PowerBI
Tools Used:  PowerBI
Industry Context:
The healthcare industry is experiencing a digital transformation, driven by the need for better patient outcomes, cost efficiency, and operational improvements. The increasing volume of healthcare data—from patient records, clinical trials, insurance claims, and wearable devices—creates an opportunity to leverage data analytics for enhanced decision-making. 

Dashboards can track the utilisation of resources such as hospital beds, medical equipment, and staff, helping to optimise their allocation and reduce wait times.
Insights from data analytics can inspire new approaches to care delivery, such as telemedicine, remote monitoring, and personalised treatment plans.

Project Objective:
The goal is to create a comprehensive, interactive dashboard in Power BI that presents a cohesive narrative of the healthcare data.
Identify trends and patterns across key parameters such as the patient demographics and treatment outcomes, cost implications of various medical procedures, and overall hospital performance metrics.

Elevating patient care and operational efficiency while establishing solutions.

About Data:
Utilised the healthcare dataset of HealthStat Solutions which spans from .2021 to 2023.

There are two datasets: 'Patient Medical Records' and 'Hospital Treatment Details'. The 'Patient Medical Records' dataset contains detailed information on patients, including their age, gender, blood type, diagnosis, treatments, admission and discharge dates, and total bills. The 'Hospital Treatment Details' dataset provides insights into the hospitals treating these patients, including the treating doctor, room number, daily costs, treatment types, and recovery ratings.

Data Preprocessing:
Imported both datasets into Power BI and performed an initial review to identify data quality issues or inconsistencies.
Merge the datasets on the PatientID column, ensuring accurate integration and completeness of data. Address any missing values, duplicate entries, and irrelevant data points to maintain data integrity.
Convert date columns (AdmissionDate and DischargeDate) to appropriate date formats and calculate the length of stay for each patient. Categorised patients using DAX into age groups (e.g., Child, Adult, Senior) to identify predominant age demographics and analyse their distribution.

Key Results:
The hospital's average recovery rating stands at 5.43, showing an upward trend in recovery outcomes.
Patient admissions show a cyclical pattern, with peaks during certain seasons or months.
Predictive models are used to forecast future patient admissions, aiding in resource allocation and capacity planning.
Business Impact:
The cyclical pattern in patient admissions allows the hospital to anticipate and prepare for peak periods, ensuring adequate staffing, resources, and reducing potential strain on hospital infrastructure.
The average medical bill of $10,000 and daily cost of $1,000 per patient underscore the importance of optimising billing processes and exploring new revenue streams or cost-saving initiatives.
An upward trend in recovery ratings indicates improved patient outcomes, which can enhance the hospital’s reputation and attract more patients. Continuous monitoring and efforts to further improve recovery ratings are essential.
The  gender distribution and high number of patients with diabetes  emphasise the need for tailored treatment plans and specialised care programs to address diverse patient needs effectively.
The high patient count for surgery and other treatments like counselling and medication  suggests the potential for the hospital to specialise in these areas, offering advanced treatments and attracting patients seeking these services.
Utilising predictive models for admissions forecasting and resource allocation highlights the importance of investing in technology and data analytics to enhance operational efficiency and decision-making.


