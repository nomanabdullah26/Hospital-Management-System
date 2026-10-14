# 🏥 Hospital Management System (HMS)

## 📌 Project Overview

The **Hospital Management System (HMS)** is a web-based application developed to simplify hospital operations and improve the management of doctors, patients, appointments, medical records, and doctor schedules. The system provides separate interfaces for administrators, doctors, and patients to support essential hospital management activities.

The project is built using PHP, JavaScript, CSS, HTML, and MySQL, with JSON files used for certain data and scheduling operations.

## ✨ Key Features

### 👨‍💼 Admin Module
- Admin login and logout.
- Doctor management.
- Add, update, and delete doctor information.
- Manage hospital-related information.

### 👨‍⚕️ Doctor Module
- Doctor registration and login.
- Doctor profile management.
- Create and manage schedules.
- View appointment-related information.
- Access doctor history.

### 🧑‍🤝‍🧑 Patient Module
- Patient registration and login.
- Patient profile management.
- View and manage appointments.
- Access medical records.
- View patient history.

### 📅 Appointment and Schedule Management
- Doctor schedule creation and viewing.
- Appointment-related pages for doctors and patients.
- JavaScript-based schedule interactions.
- PHP scripts for saving and retrieving schedules.

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Data Storage:** MySQL and JSON
- **Local Development Environment:** XAMPP

## 📂 Project Structure

```text
Hospital-Management-System/
│
├── index.html
├── welcome.php
├── contact.php
│
├── admin_login.php
├── Admin_loguot.php
├── delete_doctor.php
├── update_doctor.php
│
├── Doctor.php
├── Doctor_signup.php
├── doctor_login.php
├── Doctor_profile.php
├── Doctor_appointment.php
├── Doctor_schedual.php
├── doctor_history.php
├── save_schedule.php
├── view_schedual.php
│
├── Patient.php
├── Patient_signup.php
├── patient_login.php
├── Patient_profile.php
├── Patient_appointment.php
├── Patient_medicalRecords.php
├── patient_history.php
│
├── D_signup_validation.php
├── Patient_validation.php
├── patient_login_validation.php
├── show_patient_medical_record.php
├── logout.php
│
├── hms1.sql
├── patients.json
├── schedules.json
│
├── create_schedule.js
├── view_schedules.js
├── script.js
│
├── style.css
├── style1.css
├── style_appointments.css
├── style_contact.css
├── style_dhome.css
├── style_dprofile.css
├── style_mrecord.css
├── style_schedual.css
├── style_signup.css
│
└── assets/
    ├── Images
    └── CSS icons
```

*Note: This is a logical overview of the project files, not an exact directory structure. The `assets/` folder is illustrative; your uploaded files may currently be in the repository root.*

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### Prerequisites

Install the following software:

- [XAMPP](https://www.apachefriends.org/)
- A modern web browser
- A code editor such as Visual Studio Code

### Step 1: Clone the Repository

Open your terminal and run:

```bash
git clone YOUR_REPOSITORY_URL
```

Replace `YOUR_REPOSITORY_URL` with your GitHub repository URL.

### Step 2: Move the Project

Copy the project folder into the XAMPP `htdocs` directory.

For Windows, the default location is:

```text
C:\xampp\htdocs\Hospital-Management-System
```

### Step 3: Start Apache and MySQL

1. Open the XAMPP Control Panel.
2. Start **Apache**.
3. Start **MySQL**.

### Step 4: Import the Database

1. Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
2. Create a database using the name expected by the application's PHP database connection.
3. Select the database and open the **Import** tab.
4. Upload the `hms1.sql` file.
5. Click **Import** or **Go** to execute the SQL script.

### Step 5: Configure the Database Connection

Check the PHP files for the database connection settings. Configure the hostname, database name, username, and password according to your local MySQL setup.

For a typical local XAMPP installation, the settings may look like:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "your_database_name";
```

Use the actual database name expected by `hms1.sql` and the application.

### Step 6: Run the Application

Open your browser and visit:

```text
http://localhost/Hospital-Management-System/
```

If the main entry point is `index.html`, the homepage should load through Apache.

## 📊 Database

The project includes `hms1.sql`, which contains the SQL database setup or exported database structure.

The project also contains JSON files:

- `patients.json` — patient-related data, depending on implementation.
- `schedules.json` — schedule-related data, depending on implementation.

The exact tables, fields, and relationships can be confirmed by inspecting the SQL file.

## 🎯 Project Objectives

- Simplify hospital administration through a web-based interface.
- Organize doctor and patient information.
- Support appointment and schedule management.
- Provide access to patient medical records.
- Practice full-stack web development and database integration.

## 🚀 Future Improvements

- Implement role-based access control.
- Improve password security and input validation.
- Add appointment booking and cancellation workflows.
- Introduce automated appointment reminders.
- Improve the user interface and mobile responsiveness.
- Add stronger database security, logging, and backup functionality.
- Deploy the application to a secure hosting environment.

## 🔒 Security Considerations

This project is intended for educational and development purposes. Before using it with real patient information, implement secure authentication, password hashing, prepared SQL statements, session protection, input validation, and appropriate privacy controls.

Avoid uploading real patient records, database passwords, secret keys, or other sensitive information to a public repository.

## 👨‍💻 Author

**Your Name**

- GitHub: [(YOUR_GITHUB_PROFILE_URL)](https://github.com/nomanabdullah26)

## 📄 License

No license has been specified yet. Add an appropriate license file if you intend to distribute or reuse the project publicly.
