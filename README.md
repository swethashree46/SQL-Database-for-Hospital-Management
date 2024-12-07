# SQL-Database-for-Hospital-Management

This project involves the creation of a hospital management database to handle key aspects such as patient records, doctor details, resources, appointments, and clinical divisions. The database consists of multiple tables designed to organize and manage hospital data efficiently.

## Tables Included

1. **Patients Table**  
   Stores information about hospital patients, such as their personal details and medical history.

2. **Doctors Table**  
   Contains data about the hospital's doctors, including their specialization, contact details, and availability.

3. **Resource Table**  
   Keeps track of various hospital resources like medical equipment, rooms, and facilities available within the hospital.

4. **Appointment Table**  
   Manages appointments, linking patients with doctors, scheduling dates, and tracking appointment statuses.

5. **Clinical Division Table**  
   Holds information about various departments or divisions within the hospital (e.g., Cardiology, Pediatrics, etc.).

## Purpose

The purpose of this database is to create a system that helps in efficiently managing hospital operations. It is designed to support the following functionalities:
- Storing and retrieving patient information.
- Managing doctor schedules and patient appointments.
- Keeping track of hospital resources.
- Organizing different clinical divisions.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hospital-database.git
   ```

2. Navigate to the project folder:
   ```bash
   cd hospital-database
   ```

3. Run the SQL scripts in your preferred SQL environment to create the tables and insert sample data (if applicable).

4. Review and modify the schema as needed for your use case.

## Requirements

- SQL Database (ORACLE)
- SQL client (OCDA)

## Usage

Once the database is set up, you can run SQL queries to interact with the data. For example:
- To view all patients:
  ```sql
  SELECT * FROM Patients;
  ```
- To schedule an appointment:
  ```sql
  INSERT INTO Appointment (patient_id, doctor_id, appointment_date) VALUES (1, 3, '2024-12-10');
  ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the open-source community for providing SQL templates and resources that were used in building this project.
```
