# HospitalAPIapp
The application is hosted on the following server port : 3.27.209.147
The api end points used in the application are : 
- 3.27.209.147/api/doctors/register → register a doctor with username and password
- 3.27.209.147/api/doctors/login → returns the JWT to be used for authentication
- 3.27.209.147/api/patients/register --> to regiter a patient
- 3.27.209.147/api/patients/:id/create_report --> to create a report of a patient.
- 3.27.209.147/api/patients/:id/all_reports → List all the reports of a patient oldest to latest
- 3.27.209.147/api/reports/:status → List all the reports of all the patients filtered by a specific status
