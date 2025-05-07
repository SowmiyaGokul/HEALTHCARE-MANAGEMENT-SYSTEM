# HEALTHCARE-MANAGEMENT-
About Dataset
Patients Table:

PatientID: Unique identifier for each patient.
firstname: First name of the patient.
lastname: Last name of the patient.
email: Email address of the patient.
This table stores information about individual patients, including their names and contact details.
Doctors Table:
DoctorID: Unique identifier for each doctor.
DoctorName: Full name of the doctor.
Specialization: Area of medical specialization.
DoctorContact: Contact details of the doctor.
This table contains details about healthcare providers, including their names, specializations, and contact information.
Appointments Table:
AppointmentID: Unique identifier for each appointment.
Date: Date of the appointment.
Time: Time of the appointment.
PatientID: Foreign key referencing the Patients table, indicating the patient for the appointment.
DoctorID: Foreign key referencing the Doctors table, indicating the doctor for the appointment.
This table records scheduled appointments, linking patients to doctors.
MedicalProcedure Table:
ProcedureID: Unique identifier for each medical procedure.
ProcedureName: Name or description of the medical procedure.
AppointmentID: Foreign key referencing the Appointments table, indicating the appointment associated with the procedure.
This table stores details about medical procedures associated with specific appointments.
Billing Table:
InvoiceID: Unique identifier for each billing transaction.
PatientID: Foreign key referencing the Patients table, indicating the patient for the billing transaction.
Items: Description of items or services billed.
Amount: Amount charged for the billing transaction.
This table maintains records of billing transactions, associating them with specific patients.
demo Table:
ID: Primary key, serves as a unique identifier for each record.
Name: Name of the entity.

