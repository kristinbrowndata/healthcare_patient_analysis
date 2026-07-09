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

## **Executive Summary**
Executive Summary

This analysis examined 5,000 patient records to identify factors associated with treatment costs, recovery outcomes, and hospital readmission risk. The project included data cleaning using SQL, exploratory data analysis and visualization using Python, and predictive modeling using machine learning techniques.

The analysis found that readmission risk varies across several patient and visit characteristics. Patients aged 60 and older experienced the highest average readmission risk, while patients aged 18–30 had the lowest. Regional differences were also observed, with the East region showing the highest average readmission risk and the North region showing the lowest. Among hospital departments, Neurology had the highest average readmission risk, while Cardiology had the lowest. Treatment type showed a similar pattern, with Observation and Therapy resulting in slightly higher readmission risks than Medication and Surgery.

Length of stay demonstrated the strongest relationship with readmission risk among the variables analyzed. Patients with longer hospital stays generally experienced higher average readmission risks, with patients staying 12 days showing a 13.45% higher readmission risk than patients with no hospital stay. In contrast, treatment cost showed little evidence of a direct relationship with readmission risk despite substantial variation in treatment expenses across patients.

Treatment costs varied by both age group and region. Patients aged 18–30 incurred the highest average treatment costs, while patients aged 60 and older incurred the lowest. Regionally, the South recorded the highest average treatment costs, while the East had the lowest. Neurology was the most expensive department on average, while General Medicine had the lowest average treatment cost.

A predictive modeling exercise was conducted to determine whether patient characteristics and visit details could accurately predict readmission risk. Both a Linear Regression model and a Random Forest Regressor demonstrated poor predictive performance, producing negative R² values. These results indicate that the available variables do not provide sufficient predictive power to reliably forecast readmission risk within this synthetic dataset.

Overall, the analysis identified several meaningful patterns related to patient outcomes and healthcare costs. While demographic characteristics, treatment details, and length of stay showed modest relationships with readmission risk, additional data would likely be required to develop a reliable predictive model for hospital readmissions.

## **View the [Interactive Dashboard](https://public.tableau.com/views/HealthcarePatientAnalysis_17833362098500/HealthcarePatientAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link):**

<img width="1260" height="484" alt="Screenshot 2026-07-08 at 9 56 30 AM" src="https://github.com/user-attachments/assets/5ac113bc-d2a8-4994-b89b-ceb1038ca368" />
<img width="1254" height="549" alt="Screenshot 2026-07-08 at 9 56 19 AM" src="https://github.com/user-attachments/assets/a7fb0650-ee28-4bf1-bec1-981abfe31d46" />
<img width="1255" height="776" alt="Screenshot 2026-07-08 at 9 56 03 AM" src="https://github.com/user-attachments/assets/9d422015-8c0c-4c87-a7a6-4d07d574e55c" />
