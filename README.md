# Doctor Appointment System (PHP)
This project is a Doctor Appointment System built using PHP. It allows patients to book appointments with doctors online, manage their appointments, and enables doctors to track and manage patient bookings. The system streamlines the booking process, making it easier for both patients and doctors to manage their schedules efficiently.

## Features

- Patient Registration & Login: Patients can create an account, log in, and manage their profile.
- Doctor Registration & Login: Doctors can sign up, log in, and view their profile.
- Appointment Booking: Patients can search for available doctors and book appointments based on doctor availability.
- Appointment Management: Doctors can view their appointments and manage time slots.
- Admin Panel: An admin can manage both doctors and patients, including adding new doctors, managing appointments, and more.
- Email Notifications: Patients receive notifications via email upon booking or cancellation of appointments.
- Search Functionality: Users can search for doctors based on specialization or name.

## Technologies Used
- Backend: PHP, MySQL
- Frontend: HTML, CSS, JavaScript
- Database: MySQL
- Server: Apache

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShravanDalavi/Doctor-Appointment-System_PHP.git
   ```
2. Move the project folder to your web server directory (e.g.,` htdocs` for XAMPP):
   ```bash
   mv Doctor-Appointment-System_PHP /path/to/your/htdocs/
   ```
3. Import the database:
    - Open PHPMyAdmin and create a new database (e.g., `doctor_appointment_system`).
    - Import the SQL file located in the `database` folder of the project.
4. Update the database configuration:
Open `config.php` and update the database credentials as per your local server setup.
```php
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'your_username');
define('DB_PASSWORD', 'your_password');
define('DB_NAME', 'doctor_appointment_system');

```
5. Start the server and navigate to the project in your browser:
   ```arduino
   http://localhost/Doctor-Appointment-System-PHP/

   ```
   
## Usage
- For Patients: Register, search for doctors, and book an appointment.
- For Doctors: Log in, manage availability, and view appointments.
- For Admin: Log in, manage users (doctors and patients), and track appointments.

## How to run the Doctor Appointment Management System Project Using PHP and MySQL

1. Download the zip file : [**`Download ZIP`**](https://github.com/shravandalavi/Doctor-Appointment-System-PHP/archive/refs/heads/main.zip).

2. Extract the file and copy dams folder

3. Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/HTML)

4. Open PHPMyAdmin ( http://localhost/phpmyadmin )

5. Create a database with the name damsmsdb

6. Import damsmsdb.sql file(given inside the zip package in the SQL file folder)

7. Run the script http://localhost/dams

## Doctor Login

Username: anu@gmail.com

Password: 123456

Or Register a new user.

## Contributors ✨
- Shravan Dalavi
  - Contact: shravandalavi137@gmail.com
  - GitHub: [Profile](https://github.com/ShravanDalavi)
    
- Ashwini Sonawane
  - Contact: ashwinisonawane@gmail.com
  - GitHub:  [Profile](https://github.com/SonawaneAshwini)
    
**If you like this tutorial, please [give it a ⭐ star](https://github.com/ShravanDalavi/Web-Mini-Projects).**

**Thank you for visiting my repository! I hope you find my projects interesting and useful. 😊**
