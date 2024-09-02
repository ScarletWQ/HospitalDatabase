# HospitalDatabase  

**Hospital Database Management System** 

**Overview**  
This project implements a database management system for a small-scale private hospital. The system manages various aspects of hospital operations, including departments, employees, patients, doctors, medications, equipment, appointments, prescriptions, and suppliers. The design is focused on managing data related to hospital operations efficiently and ensuring data integrity through various constraints and relationships.  

**Features**  
Departments: Manages hospital departments with unique IDs, names, and managers.
Doctors: Records details about doctors including their IDs, names, contact information, and department assignments.
Patients: Maintains patient information such as IDs, contact details, insurance, and medical history.
Medications: Tracks medications, their stock levels, manufacturing details, and supplier information.
Equipment: Keeps records of hospital equipment including IDs, names, types, and maintenance information.
Suppliers: Manages supplier details for medications and equipment.
Appointments: Manages patient appointments with doctors and generates invoices.
Prescriptions: Handles prescriptions written by doctors, including details of medications prescribed.
Examinations: Records patient examinations involving equipment and doctors.

**Database Schema**
The database schema is designed to support the following entities:

Departments
Doctors
Patients
Medications
Equipment
Suppliers
Appointments
Invoices
Prescriptions
Prescription Medication Orders
Examinations
Each entity has associated attributes and relationships, ensuring comprehensive data management and integrity.

**Installation**    
To set up the database:  

Clone the Repository   

git clone https://github.com/ScarletWQ/HospitalDatabase.git  
cd hospital-database  

Set Up Database Use the provided SQL scripts to create the database schema and populate it with sample data.  

mysql -u yourusername -p < create_schema.sql  
mysql -u yourusername -p < insert_data.sql  
Replace yourusername with your MySQL username and provide your password when prompted.  

**Usage**  
Connect to the Database Use any MySQL client to connect to the database and perform queries or manage data.  

Run Queries Execute SQL queries to interact with the data, such as retrieving patient records, managing appointments, or generating reports.  

Maintenance Regularly back up the database and perform maintenance tasks to ensure data integrity and availability.  

**SQL Scripts**  
create_schema.sql: Contains the SQL commands to create the database schema, including tables and constraints.  
insert_data.sql: Populates the tables with sample data for testing purposes.  


**License**  
This project is licensed under the MIT License - see the LICENSE file for details.  

**Contact**  
For any questions or issues, please contact ScarletWQ.  
