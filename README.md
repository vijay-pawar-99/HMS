
# Hospital Management System

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

<p align="center">
  <img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png">
</p>

## GETTING INTO THE PROJECT:

Hospital Management System in PHP and MySQL. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project.

![image](https://user-images.githubusercontent.com/36665975/66569676-ad2d8800-eb89-11e9-94e5-ea407622a1fe.png)

'About Us' page (Fig 1.2) allows us to get some more information about the quality and the services of the hospital.

![image](https://user-images.githubusercontent.com/36665975/66569816-f4b41400-eb89-11e9-9377-d9ce53ded088.png)

‘Contact’ page allows users to provide feedback or queries about the services of the hospital. Fig 1.3 shows the ‘Contact’ page.

![image](https://user-images.githubusercontent.com/36665975/66569890-157c6980-eb8a-11e9-9b2f-c0e8a6ef702e.png)

The ‘Home’ page consists of 3 modules:
1. Patient Module
2. Doctor Module
3. Admin Module

---

### Patient Module:

This module allows patients to create their account, book an appointment to see a doctor and see their appointment history.

The registration page (in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.

![image](https://user-images.githubusercontent.com/36665975/66570027-5b393200-eb8a-11e9-9e97-088630b5e583.png)

Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard (Fig 1.5).

![image](https://user-images.githubusercontent.com/36665975/66570123-8c196700-eb8a-11e9-845f-ea02013f1d5c.png)

The Dashboard page allows patients to perform two operations:

#### 1. Book his/her appointment:

Here, the patients can book their appointments to see a doctor. The appointment form (Fig 1.6) requires patients to select the doctor, Date and Time. The consultancy fee will be shown accordingly.

![image](https://user-images.githubusercontent.com/36665975/66570202-c256e680-eb8a-11e9-8839-6c7fef68ac4c.png)

After clicking on the ‘Create new entry’ button, the patient will receive an alert confirming successful appointment. (Fig 1.7)

![image](https://user-images.githubusercontent.com/36665975/66570280-ec100d80-eb8a-11e9-96c2-08e5441954d0.png)

#### 2. View patients’ Appointment History:

Displays Doctor Name, Consultancy Fee, Appointment Date and Time. (Fig 1.8)

![image](https://user-images.githubusercontent.com/36665975/66570349-0ea22680-eb8b-11e9-94fe-22a86070a274.png)

Patients can log in again using their credentials (Fig 1.9).

![image](https://user-images.githubusercontent.com/36665975/66570502-588b0c80-eb8b-11e9-88e3-5294ae896ace.png)

---

### Doctor Module:

Doctors can log in by toggling the tab from ‘Patient’ to ‘Doctor’. (Fig 1.10)

Doctor accounts are registered by the admin.

![image](https://user-images.githubusercontent.com/36665975/66570609-8bcd9b80-eb8b-11e9-8099-9f285aa7fe0f.png)

Once logged in, they’re redirected to their dashboard. (Fig 1.11)

![image](https://user-images.githubusercontent.com/36665975/66570642-a0119880-eb8b-11e9-8d23-be898e1bfa29.png)

---

# 🏥 HMS - Hospital Management System

A complete web-based Hospital Management System built with **PHP**, **MySQL**, **HTML**, and **CSS**. It supports core features for managing hospital operations such as appointments, doctor and patient panels, medical records, and more.

---

## 📌 Features

- 🔐 Secure Login/Logout for Admin and Doctors
- 🧑‍⚕️ Admin Panel to manage Doctors, Patients, and Appointments
- 👨‍⚕️ Doctor Panel to view appointments and patient data
- 🗂️ Patient registration and appointment booking
- 🔍 Real-time search functionality
- 📋 Structured medical and billing records
- 🛠️ MySQL backend with a pre-designed schema

---

## 🛠️ Technologies Used

| Component     | Stack                    |
|---------------|--------------------------|
| Frontend      | HTML5, CSS3, Bootstrap   |
| Backend       | PHP                      |
| Database      | MySQL                    |
| PDF Export    | TCPDF                    |
| Web Server    | XAMPP / LAMP / MAMP      |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/vijay-pawar-99/HMS.git
cd HMS
```

### 2. Import the Database

- Open **phpMyAdmin**
- Create a new database named `myhmsdb`
- Import `myhmsdb.sql` from the project folder

### 3. Configure the Connection

Edit `include/config.php` and set:

```php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "myhmsdb";
```

### 4. Run the Application

Start XAMPP Apache & MySQL, then visit:

```
http://localhost/HMS/
```

---

## 📁 Project Structure

```
Hospital-Management-System-master/
├── assets/               # CSS, JS, images
├── include/              # DB config and PHP includes
├── vendor/               # Composer packages (not tracked)
├── myhmsdb.sql           # Database dump
├── *.php                 # Core logic
└── README.md
```

---

## 🔐 Security & Git

**.gitignore** ensures these files are excluded:
- `.env`
- `*.sql`
- `vendor/`
- IDE/workspace files

---

## 📄 License

This project is open-source and intended for educational or demo use. Customize and reuse with proper credit.

---

## 🙋‍♂️ Author

**Vijay Pawar**  
📫 [LinkedIn](https://www.linkedin.com/in/vijay-pawar-99/)  
💻 GitHub: [@vijay-pawar-99](https://github.com/vijay-pawar-99)
