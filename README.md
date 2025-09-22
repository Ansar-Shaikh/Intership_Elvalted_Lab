1. Date Handling

Converted date columns to proper format

Extracted useful features: year, month, day of week

Calculated waiting days between scheduling and appointment

2. Data Cleaning

Checked for duplicates (none found)

No missing values in the dataset

3. Feature Engineering

Renamed No-show to AppointmentStatus

Encoded categorical variables (Gender, Neighbourhood, AppointmentStatus)

drop  PatientId and AppointmentID as identifiers

4. Final Dataset
 17 features + 1 target variable
Target: AppointmentStatus (0 = Showed up, 1 = No-show)
