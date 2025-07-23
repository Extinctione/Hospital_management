project i did back in 2023- Hospital Management System

A GUI-based Hospital Management System built with Python (Tkinter) and MySQL to handle patient registration, appointments, and services efficiently.

 Features

-  Patient Registration  
  Register patients using AADHAAR ID with details like name, age, gender, phone number, and blood group.

- Doctor Appointments  
  Book appointments with randomly assigned doctors across various departments.

- Doctor List  
  View available doctors, their departments, and assigned room numbers.

- Hospital Services  
  Check availability of essential services (e.g., X-ray, MRI, CT Scan) and their room locations.

- Data Modification  
  Update patient details based on AADHAAR number.

-  Search Patient Records  
  Fetch and display existing patient data using their AADHAAR number.

 Tech Stack

- Frontend: Python `Tkinter` (GUI)
- Backend: MySQL database
- Libraries Used:  
  - `mysql-connector-python`  
  - `tkinter` (built-in)

  Setup Instructions

1. Install Required Python Package:
   bash
   pip install mysql-connector-python

Make sure your MySQL service is running. 
con = sqlcon.connect(host="localhost", user="root", password="your_password")

