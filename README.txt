Parking Management System
-------------------------
-------------------------

Overview
--------

The Parking Management System is a Python-based application developed to streamline parking management operations. Built using Python's Tkinter library for the user interface and MySQL for the backend database, this system allows users to add, view, and delete parking and vehicle records. Designed with scalability and user experience in mind, the system provides a straightforward, responsive, and professional interface suitable for both individual and commercial parking facilities.


Features
--------

- Add Parking Details: Enter information about new parking spaces, levels, free spaces, vehicle numbers, and parking duration.
- View Parking Details: Retrieve and display all current parking records in a structured table.
- Add Vehicle Details: Record details about vehicles, including vehicle number, model, and date of purchase.
- Remove Vehicle Records: Delete vehicle records and their corresponding parking information from the system.
- View Vehicle Details: Fetch specific vehicle and parking information based on the vehicle number.


Installation
----------

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/parking-management-system.git
   ```
   
2. Install Required Libraries:
   Ensure you have `mysql-connector-python` installed:
   ```bash
   pip install mysql-connector-python
   ```

3. Set Up MySQL Database:
   - Create a database named `Parking`.
   - Create tables `parkmaster12` and `vehicle` with the appropriate fields as per the project structure.

4. Update Database Credentials:
   Modify the database connection settings in the code with your MySQL `user`, `password`, and `host`.


Usage
-----
Run the script with the following command:
```bash
python parking_management_system.py
```


Programming Languages Used
---------------------------

- Python: Core logic and GUI (using Tkinter).
- SQL (MySQL): Backend database for storing vehicle and parking information.



System Architecture
------------------

The system consists of:
- Front-End (GUI): Built with Tkinter, featuring a clean layout, easy navigation, and distinct buttons for each operation.
- Back-End (Database): MySQL handles all data storage, supporting the system's add, view, and delete functionalities through relational tables.



Implementation
--------------

1. User Interface: The Tkinter-based interface presents an intuitive layout, allowing users to navigate the various options with ease.
2. Database Operations: The system connects to MySQL, executing SQL commands to add, view, and delete records as needed.



Algorithms/Pseudo Code
----------------------

- Each function includes basic CRUD operations (Create, Read, Update, Delete) implemented via SQL queries.
- Confirmation dialogs and exception handling ensure secure and error-free operations.



Future Enhancements
-------------------

Potential improvements include:
- Advanced Search Options: Allow filtering records by date, vehicle model, or parking level.
- Admin Login System: Implement user roles and authentication.
- Real-Time Data Sync: Sync with external systems or mobile apps for real-time tracking.



License
-------

This project is licensed under the MIT License.



Contributing
------------
Contributions are welcome! If you find any issues or want to enhance the project, feel free to fork the repository and submit a pull request.
