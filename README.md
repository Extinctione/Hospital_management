# Hospital Management System

A GUI-based project developed in 2023 to streamline hospital operations like patient registration, appointment scheduling, and service management.

---

## Features

- **Patient Registration**  
  Register patients using AADHAAR ID along with name, age, gender, phone number, and blood group.

- **Doctor Appointments**  
  Book appointments with randomly assigned doctors across multiple departments.

- **Doctor Listing**  
  View available doctors, their specialties, and assigned room numbers.

- **Hospital Services**  
  Browse essential services like X-Ray, MRI, CT Scan, etc., and check their availability and room numbers.

- **Data Modification**  
  Update patient details based on AADHAAR number.

- **Search Records**  
  Search and display existing patient records by AADHAAR.

---

## Tech Stack

- **Frontend**: Python Tkinter (GUI)
- **Backend**: MySQL
- **Libraries Used**:
  - `mysql-connector-python`
  - `tkinter` (built-in Python library)

---

## Setup Instructions

1. **Clone or Download the Repository**

2. **Install Required Package**

   ```bash
   pip install mysql-connector-python


Before running the project, make sure your MySQL service is running.  
Update the connection credentials in the Python file (`main.py`) to match your system:

```python
con = sqlcon.connect(
    host="localhost",
    user="root",
    password="your_mysql_password"
)

