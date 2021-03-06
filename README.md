Hospital Management System
Mohammed Alamoundi, Mohammed Al Duniawi, Hemanth Nalamothu, Victor Logan

The project that our group will be working on is a Hospital Management System, HMS. The System will be used by a hospital to keep the records of patients and manage the appointments for patients with doctors in the hospital and the cost of visits and operations for patients. 

HMS will record and keep track of patients, appointments, bills, employees, login info, and department.  Each patient will have a unique patient ID, First Name, Last name, Date of birth, Address, and Contact. Each appointment will have a unique Appointment ID, Appointment Date, Appointment Time, prescription, comments from doctor and appointment status. Each Bill will have a unique Bill ID, pending amount, Bill amount, and paid status. Each employee will have a unique employee ID, type of employment, image, First Name, Last Name, Address, Contact, Start Date and End Date. 

There will be four users; The patent, the doctor, the receptionist, and the administrator. The patient can view and update their personal information. They can view bills and make a payment. The doctor can view and update their personal information. The doctor can see their list of appointments and reschedule if need be. The doctor can also make comments on appointments. The receptionist can register patients and create/edit appointments. The administrator can create and edit employees, doctors, and receptionists. 

In terms of queries that will be supported, there will be create/insert, read/select, update and delete/remove. It will be Create New Patient, employee, Doctor, Receptionist, Admin, and new appointment. Read/display current appointments and view personal information. Update personal information, make payments, change appointments. Delete patient, appointment, doctor, and receptionist.  In general, the Doctor will be able to Select, Update, and insert. The receptionist will be able to Insert, Select, Update, and Delete. The Admin will be able to Insert, Update, Delete, Create, and Select.

A patient can have one set of login details. A Patient can have one or many bills and a bill can only have one patient. An employee can be a doctor, a receptionist, or an admin. An employee can have one set of login details. A doctor can have one or many appointments. An appointment can be seen by one or many doctors. An appointment can have one bill and a bill can belong to one appointment.

A Delete Restriction is that a department record must not be deleted if its primary key value is referred to by a foreign key value. If an employee record is deleted from the Employee table, all foreign keys that refer to the primary key of this record will also be deleted.  If a patient record is deleted from the patient table, all foreign keys that refer to the primary key of this record will also be deleted.

