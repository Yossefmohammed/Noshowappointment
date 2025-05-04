# Medical Appointment No-Show Analysis

## Project Overview
This project analyzes a dataset of medical appointments to understand and predict patient no-show behavior. The dataset contains information about 110,527 medical appointments in Brazil, focusing on whether patients showed up for their scheduled appointments.

## Dataset Description
The original dataset contains the following features:
- PatientId: Unique identifier for each patient
- AppointmentID: Unique identifier for each appointment
- Gender: Patient's gender (M/F)
- ScheduledDay: Day when the appointment was scheduled
- AppointmentDay: Day of the actual appointment
- Age: Patient's age
- Neighbourhood: Location of the hospital
- Scholarship: Whether the patient is enrolled in the Brazilian welfare program (0/1)
- Hipertension: Whether the patient has hypertension (0/1)
- Diabetes: Whether the patient has diabetes (0/1)
- Alcoholism: Whether the patient is an alcoholic (0/1)
- Handcap: Number of handicaps the patient has (0-4)
- SMS_received: Whether the patient received an SMS reminder (0/1)
- No-show: Whether the patient showed up for the appointment (Yes/No)

## Data Preprocessing
- Removed unnecessary columns: PatientId, AppointmentID, ScheduledDay, AppointmentDay, and Neighbourhood
- Analyzed basic statistics of the remaining features
- Split the data into age groups (≤40 and >40) for demographic analysis

## Key Findings
- The dataset contains 110,527 appointments
- Average age of patients: 37.09 years
- 9.83% of patients are enrolled in the scholarship program
- 19.72% of patients have hypertension
- 7.19% of patients have diabetes
- 3.04% of patients are alcoholics
- 32.10% of patients received SMS reminders

## Age Distribution
- Patients aged 40 and below: 60,684 appointments
- Patients aged above 40: 51,245 appointments

## Next Steps
The analysis can be extended to:
1. Build a predictive model for no-show appointments
2. Analyze the impact of SMS reminders on attendance
3. Study the relationship between chronic conditions and appointment attendance
4. Investigate the effect of scholarship status on attendance rates

## Dependencies
- Python 3.x
- NumPy
- Pandas
- CSV module

## Usage
1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook `project1_Noshowappointment.ipynb`

## Contact Information
For any questions or inquiries about this project, please contact:
- Name: Youssef
- Email: [Your Email]
- GitHub: [Your GitHub Profile]
