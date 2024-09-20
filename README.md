# Hospital Management System

This is a **Hospital Management System** desktop application built using **Python** and **Tkinter**. It allows managing patient information, generating prescriptions, and handling hospital records with a graphical user interface.

## Features

- Patient Information Management
  - Add, update, delete, and clear patient details.
  - Store details such as patient ID, name, date of birth, address, and NHS number.
  
- Prescription Management
  - Generate and display prescription details.
  - Include medication information such as name, dose, number of tablets, issue date, expiration date, and more.
  
- Data Storage
  - Store patient and prescription data using **MySQL**.
  
- User Interface
  - Built using **Tkinter** for a responsive GUI.
  - Includes scrollable table views for better data handling.
  
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Screenshots](#screenshots)
- [License](#license)

## Installation

1. **Clone the repository**  
   Clone this repository to your local machine.
   ## Installation

2. **Install Python dependencies**  
   Install the necessary Python libraries using `pip`. For this project, you need to install `mysql-connector-python` to connect to the MySQL database.

3. **Set up MySQL Database**  
   Ensure you have MySQL installed on your machine. Create a new database and a table to store the hospital data. Use the following SQL commands to create the database and table:

   ```sql
   CREATE DATABASE mydata;

   USE mydata;

   CREATE TABLE hospital (
       Nameoftablets VARCHAR(255),
       Reference_No VARCHAR(255),
       Dose VARCHAR(255),
       Numberoftablets VARCHAR(255),
       Lot VARCHAR(255),
       Issuedate VARCHAR(255),
       ExpDate VARCHAR(255),
       DailyDose VARCHAR(255),
       Storage VARCHAR(255),
       NHSNumber VARCHAR(255),
       PatientName VARCHAR(255),
       DOB VARCHAR(255),
       PatientAddress VARCHAR(255)
   );
  
   ```
## Configure Database Connection

Update the database connection parameters in the Python script (`hospital_management_system.py`) with your MySQL credentials, including host, user, password, and database name.

## Usage

1. Run the application by executing the Python script `hospital_management_system.py`.
2. The GUI will open, allowing you to manage hospital records.
3. Use the buttons to perform various actions:
   - Add a new patient record.
   - Update existing records.
   - Delete records.
   - Clear input fields.
   - Generate prescriptions.

## Technologies Used

- **Python**: The programming language used for the application.
- **Tkinter**: The library used for building the graphical user interface (GUI).
- **MySQL**: The database used for storing patient and prescription information.

## Screenshots

*Add screenshots of the application here to provide visual context.*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

