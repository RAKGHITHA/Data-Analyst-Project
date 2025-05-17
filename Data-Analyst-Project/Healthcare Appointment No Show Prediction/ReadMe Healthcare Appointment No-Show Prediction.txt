## Project Title:
Healthcare Appointment No-Show Prediction

This project aims to analyze and predict patient no-shows for medical appointments using machine learning and visualize the insights with Power BI.

## Objective

To predict whether a patient will miss their appointment and provide actionable insights to healthcare providers to optimize scheduling and improve attendance.

---

## Tools & Technologies

- **Python** (Pandas, Scikit-learn)
- **Power BI**
- **Jupyter Notebook**

---

## Dataset Description

The dataset includes information such as:

- Patient demographics: Age, Gender, Neighbourhood
- Appointment details: ScheduledDay, AppointmentDay
- Medical conditions: Hypertension, Diabetes, Alcoholism, Handicap
- SMS_received and Scholarship support
- Target: `No-show` (Yes/No)

---

## Data Preprocessing

- Removed null and duplicate entries
- Transformed date fields to compute the gap between scheduling and appointment
- Grouped Age into bins for better visualization
- Encoded categorical values

---

## Machine Learning Model

- **Model Used**: Decision Tree Classifier
- **Target Variable**: Showed_up (True/False)
- **Features**: Age, Gender, SMS_received, Scholarship, Date difference, Medical flags

---

## Power BI Dashboard

### Key Visuals:

- Show vs. No-Show Distribution
- Age Group Trends
- Gender Comparison
- Neighborhood-wise Attendance
- Impact of SMS and Scholarship

### Filters Used:

- Gender
- Scholarship
- SMS_received

---

## Key Insights

- SMS reminders reduce no-show rates.
- Certain neighborhoods have higher no-show tendencies.
- Scholarship recipients tend to attend more regularly.
- Gender and age affect attendance probability.

---

## Deliverables

-  Cleaned dataset
-  Trained Decision Tree model
-  Interactive Power BI dashboard
-  PDF Report
