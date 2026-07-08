# healthcare_patient_analysis

# **About Dataset**

## **Context**
This dataset contains simulated patient analytics data. It provides a comprehensive view of patient demographics, hospital visits, treatments, and outcomes, making it suitable for practicing data manipulation, visualization, and predictive modeling in the healthcare domain.

## **Content**
The dataset contains records with the following columns:

patient_id: A unique identifier for each patient.  
visit_date: The date of the patient's visit to the healthcare facility.  
age_group: The age category of the patient (e.g., 18-30, 31-50, 51+).  
gender: The gender of the patient.  
region: The geographic region of the patient.  
department: The hospital department visited (e.g., Cardiology, General Practice).  
treatment_type: The type of treatment administered.  
visit_type: The nature of the visit (e.g., Inpatient, Outpatient, Emergency).  
length_of_stay_days: The total number of days the patient stayed in the hospital.  
treatment_cost: The total cost associated with the treatment.  
recovery_score: A score indicating the patient's recovery progress.  
readmission_risk: The assessed risk of the patient being readmitted (e.g., High, Low, Medium).  

## **Acknowledgements**
The dataset is a synthetic construct created to facilitate learning and practice in healthcare data analytics.

## **Inspiration Questions**
* Which departments incur the highest average treatment costs?
* Is there a correlation between the length of stay and the recovery score?
* What factors most significantly contribute to a high readmission risk?
* How do treatment costs vary across different age groups and regions?
* Can we build a model to predict the readmission risk based on patient characteristics and visit details?

## **Tools Used**
* SQL (BigQuery)
* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Tableau

## **Key Findings**
* Patients aged 60+ showed the highest average readmission risk.
* Longer hospital stays were associated with increased readmission risk.
* Neurology had the highest average treatment cost.
* Treatment cost showed little direct relationship with readmission risk.
* Predictive models did not accurately predict readmission risk.

## **View the [Interactive Dashboard](https://public.tableau.com/views/HealthcarePatientAnalysis_17833362098500/HealthcarePatientAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link):**

<img width="1260" height="484" alt="Screenshot 2026-07-08 at 9 56 30 AM" src="https://github.com/user-attachments/assets/5ac113bc-d2a8-4994-b89b-ceb1038ca368" />
<img width="1254" height="549" alt="Screenshot 2026-07-08 at 9 56 19 AM" src="https://github.com/user-attachments/assets/a7fb0650-ee28-4bf1-bec1-981abfe31d46" />
<img width="1255" height="776" alt="Screenshot 2026-07-08 at 9 56 03 AM" src="https://github.com/user-attachments/assets/9d422015-8c0c-4c87-a7a6-4d07d574e55c" />
