MIMIC-III Dataset Overview
The Medical Information Mart for Intensive Care III (MIMIC-III) is a large, freely accessible critical care database. It contains de-identified health data associated with over 60,000 ICU admissions between 2001 and 2012 at the Beth Israel Deaconess Medical Center in Boston, Massachusetts.

📁 Contents of the MIMIC-III Dataset
The dataset includes detailed information such as:

Patient demographics (age, gender, ethnicity)

Vital signs (heart rate, blood pressure, respiratory rate, etc.)

Lab test results

Medications and prescriptions

Diagnoses (ICD-9 codes)

Procedures performed

Caregiver notes and discharge summaries

Length of stay, ICU admissions, and mortality

Time-stamped clinical events

MIMIC-III is designed to support a wide range of research, including but not limited to:

Predictive modeling (e.g., mortality prediction)

Disease phenotyping

Clinical decision support

Natural language processing (NLP) on clinical notes

📌 Key Tables in the Dataset
Table Name	Description
ADMISSIONS	Admission-level info, including admission time, discharge time, and death time.
PATIENTS	Basic demographic information.
ICUSTAYS	Details of ICU stays for each patient.
CHARTEVENTS	High-resolution data including vitals, labs, and assessments.
LABEVENTS	Laboratory measurements.
DIAGNOSES_ICD	ICD-9 diagnosis codes assigned during hospital stay.
PROCEDURES_ICD	ICD-9 procedure codes.
NOTEEVENTS	Unstructured clinical notes such as nursing and discharge summaries.
PRESCRIPTIONS	Drug prescriptions given during stay.
INPUTEVENTS_MV / INPUTEVENTS_CV	Inputs (e.g., fluids, medications) administered during ICU stay.
OUTPUTEVENTS	Output records (e.g., urine output).

🛡️ Privacy & Access
The dataset has been de-identified in accordance with HIPAA standards.

Access to MIMIC-III requires completion of a data use agreement and the CITI "Data or Specimens Only Research" course.

📎 Access the official dataset here: https://physionet.org/content/mimiciii/1.4/









