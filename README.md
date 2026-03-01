# Hospital Performance Analysis
End-to-end data analysis project with Python and Tableau.

## Hospital Performance Dashboard
![Hospital Performance Dashboard](Tableau-dashboard/Hospital%20Admissions%20Performace%20-%202023.png)

## Patient Trends Dashboard
![Patient Trends Dashboard](Tableau-dashboard/Patient%20Trends.png)

## Project Overview:  
This project analyses a simulated hospital admissions dataset to explore:
- Length of Stay
- 30-Day Readmission Rates
- Variations between wards, patient types, and patient ages
- Seasonal admission trends

## Tools Used:
- Python (Pandas, NumPy, Matplotlib)
- Tableau Public
- SQL

## Project Workflow:
- A synthetic dataset was created with 5000 records (notebook 1)
- This data set was then cleaned to remove unrealistic ages, strip whitespace, and normalise capitalisation across categorical fields (notebook 2)
- An exploratiory data analysis was performed with Pandas, relationships were graphed with Matplotlib, and an additional datset was created from data in the original set to explore bed occupancy (notebook 3)
- Key performance indicators were identified and operational insights were relayed and reported (notebook 3)
- An interactive 'Hospital Admissions Performance' dashboard was created with Tableau that allows the filtering of admission numbers by month, ward, and bed occupancy rate. Average length of stay by ward can also be exmained  (https://public.tableau.com/app/profile/jocelyn.sickler/viz/hospital_admissions_dashboard/HospitalAdmissionsPerformace-2023?publish=yes)
- An additional interactive 'Patient Trends' dahboard was created with Tableau that allows filtering by admission type, age group, and ward to analyse average length of stay and readmission rates by demographic (https://public.tableau.com/app/profile/jocelyn.sickler/viz/patient_trends_dashboard/PatientTrends?publish=yes)
 
## Key Findings:
- The average length of stay was 7.46 days over 4120 admission records (Messy dataset before cleaning contains 5000 records)
- The 30-day readmission rate was 11.5%
- Admission numbers increased during the winter months
- Elderly patients (75+) had a 2 day longer length of stay compared to other age groups
- Patients admitted to the Respiratory ward had a higher readmission risk than patients on other wards
   
## Limitations:
- This dataset has been randomly simulated and does not represent real clinical data. Ward allocation and age were randomised and may not reflect reality.
- The dataset covers one year and one hospital only. Attempts were made to find statistics about other NHS hospitals online (sources listed in notebook 3), but it is difficult to form true comparions without additional data.
