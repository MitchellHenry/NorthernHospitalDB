# NorthernHospitalDB

Groups will have to ensure inserting a Patient and Staff correctly concatenates the password literal with the salt before hashing

 - frequency and frequencySetDate added to PatientMeasurement (used to Alert Patient when Clinician changes measurement frequency)
 - Added ConditionDetails table to populate PatientDetails in Patient APP
 
Ignore/delete the following tables if not working on the Patient app or not creating Patient Resources from the database:
- TemplateResource
- Resource
- PatientResource
- ResourceDialog
- ResourceType
