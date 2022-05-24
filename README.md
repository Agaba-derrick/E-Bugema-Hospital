# E-Bugema-Hospital
Bugema Hospital E-care system is a web based application project built in PHP.
Moving on, this hospital management system project in PHP focuses mainly on dealing with the patient, doctor, and hospital records. Also, the system displays all the available hospital departments and their respective doctors. In addition, the system allows creating a patient’s personal account too. This project is divided into three categories. They are the Admin Panel, Patient Panel, and Doctor Panel. In an overview of this web application, the user can simply make an appointment. Meaning, each user will have to fill up an appointment form from the client side. The form consists of fields such as patient name, address, number, and selection of department and doctor. During this procedure, the system creates personal accounts for each patient too.
Bugema University, a newly upgraded hospital from a health center receives a number of patients daily exceeding their capacity especially mothers with newly born babies, Students from the University and some other people form the  community yet there is no proper management of patients records and medical history to aid the health care givers. 
It is against this background that the study attempts to propose an E-Health care and management system for Online Health Records for Bugema University Hospital.
It helps patients from far and within Bugema to book appointment at the hopsital
Helps the doctors to meet appointment by the patients 
it has a database that keeps information about the patients and all the medical records of a patient

## How to log access E-bugema system
How to run the E-Bugema Hospital Management System Project
1. Download the file / Clone the file

2.copy hospital folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

4. Open PHPMyAdmin (http://localhost/phpmyadmin)

5. Create a database with name hms

6. Import hms.sql file(given inside the zip package in SQL file folder)

7.Run the script http://localhost/hospital (frontend)

Login Details
Login Details for admin : admin/Test@12345
Login Details for Patient: test@gmail.com/Test@123
Login Details for Doctor: test@demo.com/Test@123

### System and User Requirements
Registration Process of SRS (Software Requirements Specification)
● Adding Patients: The Health Management system enables the staff/admins in the front desk to include new patients to the system.
● Assigning an ID to the patients: The Health care Management System enables the staff in the front desk to provide a unique ID for each patient and then add them to the record sheet of the patient. The patients can utilize the ID throughout their hospital stay.
Check Out of SRS:
● Deleting Patient ID: The staff in the administration section of the system can delete the patient ID from the system when the patient's checkout from the hospital.
Report Generation of SRS:
● Information of the Patient: The Hospital Management System generates a report on every patient regarding various information like patients name, Phone number, the doctor's name whom it assigns, ward name, and more.
Database of SRS:
● Mandatory Patient Information: Every patient has some necessary data like phone number, their first and last name, personal health number, postal code, country, address, city, patient's ID number, etc.
● Updating information of the Patient: The hospital management system enables users to update the information of the patient as described in the mandatory information included.
Non Functional Requirements
There are a lot of software requirements included in the non-functional requirements of the Hospital Management System, which contains various processes, namely Security, Performance, Maintainability, and Reliability.
Security:
● Logon ID: Any users who make use of the system need to hold a Logon ID and password.
● Modifications: Any modifications like insert, delete, update, etc. for the database can be synchronized quickly and executed only by the ward administrator.
● Admin Rights: The staff in the admin section can view any data in the Hospital Management system, add new patients records to the HMS but they don't have any rights to alter any data in it.

####  Implementation 
PHP/MySQL and HTML, CSS,and bootstrap were used for system implementation. PHP helps to
dynamically capture information from web forms to MySQL database, and HTML,Javascript
CSS3/FrontPage help to create attractive interfaces.

