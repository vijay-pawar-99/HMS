# Hospital Management System
Hospital Management System using MySQL, Php and Bootstrap


Video Demo : [Hospital Management System - Youtube](https://www.youtube.com/watch?v=W2XGSM5i9P8)

Live Demo : [Hospital Management System - 000webhost by Kishan](https://kishan0725.000webhostapp.com)

## Need to work on:

1. Ability to accept the appointment by the doctor to acknowledge the patient that their appointment has been approved.
2. User should not be allowed to register if he/she tries to provide the already registered email ID.
3. The password should be encrypted and the password field shouldn't be displayed in the admin panel.
4. Implementation of pagination for all the list view across the application.
5. Bug fix - Bill payment receipt contains multiple record if the patient has associated with the same doctor multiple times.
6. Addition of more fields in the prescription statement to make it more specific one.
7. Addition of more details on payment - such as date of the payment made, amount paid, etc.
8. Implementation of export button in admin module to export all details to an excel sheet.

## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with latest version

## Languages and Technologies used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. Php
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

## Steps to run the project in your machine
1. Download and install XAMPP in your machine
2. Clone or download the repository
3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4. Start the Apache and Mysql in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'
6. In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7. Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8. Open a new tab and type 'localhost/foldername' in the url of your browser
9. Hurray! That's it!
    
### SOFTWARES USED
  - XAMPP was installed on the Ubuntu 19.04 machine and APACHE2 Server and MySQL were initialized. And, files were built inside opt/lampp/htdocs/myhmsp
  - Sublime Text 3.2 was used as a text editor.
  - Google Chrome Version 77.0.3865.90 was used to run the project (localhost/myhmsp was used as the url).
  

### Starting Apache And MySQL in XAMPP:
  The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.
  
  
<p align="center"><img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png"></img></p>

## GETTING INTO THE PROJECT:
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project.

![image](https://user-images.githubusercontent.com/36665975/66569676-ad2d8800-eb89-11e9-94e5-ea407622a1fe.png)

'About Us' page (Fig 1.2)  allows us to get some more information about the quality and the services of the hospital.

![image](https://user-images.githubusercontent.com/36665975/66569816-f4b41400-eb89-11e9-9377-d9ce53ded088.png)

‘Contact’ page allows users to provide feedback or queries about the services of the hospital. Fig 1.3 shows the ‘Contact’ page.

![image](https://user-images.githubusercontent.com/36665975/66569890-157c6980-eb8a-11e9-9b2f-c0e8a6ef702e.png)

The ‘Home’ page consists of 3 modules:
1. Patient Module
2. Doctor Module
3. Admin Module

### Patient Module:

  &nbsp; &nbsp; &nbsp; This module allows patients to create their account, book an appointment to see a doctor and see their appointment history.
  The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.
  
  ![image](https://user-images.githubusercontent.com/36665975/66570027-5b393200-eb8a-11e9-9e97-088630b5e583.png)

Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard(Fig 1.5).

![image](https://user-images.githubusercontent.com/36665975/66570123-8c196700-eb8a-11e9-845f-ea02013f1d5c.png)

The Dashboard page allows patients to perform two operations:

**1. Book his/her appointment:**

  &nbsp; &nbsp; &nbsp; Here, the patients can able to book their appointments to see a doctor. The appointment form(Fig 1.6) requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.

![image](https://user-images.githubusercontent.com/36665975/66570202-c256e680-eb8a-11e9-8839-6c7fef68ac4c.png)

After clicking on the ‘Create new entry’ button, the patient will receive an alert that acknowledges the successful appointment of the patient.(See Fig 1.7) 

![image](https://user-images.githubusercontent.com/36665975/66570280-ec100d80-eb8a-11e9-96c2-08e5441954d0.png)

**2. View patients’ Appointment History:**

  &nbsp; &nbsp; &nbsp; Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.(See Fig 1.8).
	
![image](https://user-images.githubusercontent.com/36665975/66570349-0ea22680-eb8b-11e9-94fe-22a86070a274.png)

Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again. Fig 1.9 shows the login page.
Clicking on ‘Login’ button will redirect the patient to his dashboard page which we have seen earlier (Fig 1.5)

![image](https://user-images.githubusercontent.com/36665975/66570502-588b0c80-eb8b-11e9-88e3-5294ae896ace.png)

This is how the patient module works. On the whole, this module allows patients to register their account or login their account(if he/she has one), book an appointment and view his/her appointment history.

### Doctor Module:

  &nbsp; &nbsp; &nbsp; The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’. Fig 1.10 shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.
  
![image](https://user-images.githubusercontent.com/36665975/66570609-8bcd9b80-eb8b-11e9-8099-9f285aa7fe0f.png)

Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard which is shown in Fig 1.11

![image](https://user-images.githubusercontent.com/36665975/66570642-a0119880-eb8b-11e9-8d23-be898e1bfa29.png)

# 🏥 HMS - Hospital Management System

A complete web-based Hospital Management System built with **PHP**, **MySQL**, **HTML**, and **CSS**. It supports core features for managing hospital operations such as appointments, doctor and patient panels, medical records, and more.

---

## 📌 Features

- 🔐 **Secure Login/Logout** for Admin and Doctors
- 👨‍⚕️ Admin Panel to manage:
  - Doctors
  - Patients
  - Appointments
- 👨‍⚕️ Doctor Panel to view appointments and patients
- 🗂️ Patient record management
- 🔍 Real-time search for patients and doctors
- 📦 Modular PHP codebase with reusable components
- 🛠️ Structured database with sample data

---

## 🛠️ Technologies Used

| Category        | Stack                     |
|----------------|----------------------------|
| Backend         | PHP                        |
| Frontend        | HTML5, CSS3                |
| Database        | MySQL (`myhmsdb.sql`)      |
| Dependencies    | Composer, Font Awesome     |
| Web Server      | XAMPP / LAMP / MAMP        |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vijay-pawar-99/HMS.git
cd HMS

---

### 2. Import the Database
Open phpMyAdmin or your MySQL tool.

Create a new database (e.g., hmsdb).

Import the myhmsdb.sql file.

---

### 3. Configure Database Connection
Edit your DB config file (e.g., include/config.php) with:

php
Copy
Edit
$host = "localhost";
$user = "root";
$password = "";
$dbname = "hmsdb";

---

### 4. Start the Application
Start Apache and MySQL from XAMPP.

Navigate to http://localhost/HMS/ in your browser.

----

📁 Project Structure
graphql
Copy
Edit
Hospital-Management-System-master/
│
├── assets/               # CSS, fonts, images
├── include/              # PHP includes/configs
├── vendor/               # Composer dependencies (gitignored)
├── admin-panel.php       # Admin login & dashboard
├── doctor-panel.php      # Doctor login & dashboard
├── myhmsdb.sql           # MySQL database dump
├── README.md             # This file
└── ...                   # Other core PHP files
  
  🔐 Security Notice
Sensitive files like .env, vendor/, and *.sql are added to .gitignore for safe GitHub deployment. Never commit real credentials.

📄 License
This project is open-source and for educational purposes only. You may modify or distribute with proper credit.

🙋‍♂️ Author
Vijay Pawar
📫 LinkedIn
💻 GitHub: @vijay-pawar-99




  
  

  
  
  
  

  
  


	
 
