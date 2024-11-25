
---

# Juba Teaching Hospital Appointment System  

![](https://github.com/Dau2004/Juba-Teaching-Hospital/blob/main/Screenshots/Screenshot%202024-11-25%20122408.png)  

This project addresses the challenges of hospital overcrowding and inefficient appointment scheduling, especially at Juba Teaching Hospital in South Sudan. It enables patients to book appointments online, reduces unnecessary visits, and allows doctors to manage their schedules effectively. Administrators oversee the system by managing doctors, sessions, and patient data.  

The system has three user roles:  
1. **Administrator**  
2. **Doctors**  
3. **Patients**  

---

## Features  

### Administrator:  
- Add, edit, and delete doctors.  
- Schedule or remove doctor sessions.  
- View patient details and manage their records.  
- Oversee all bookings and system operations.  

![](https://github.com/Dau2004/Juba-Teaching-Hospital/blob/main/Screenshots/Screenshot%202024-11-25%20113211.png)  

### Doctors:  
- View their appointments and scheduled sessions.  
- Access patient details for consultations.  
- Update or delete their accounts.  

![](https://github.com/Dau2004/Juba-Teaching-Hospital/blob/main/Screenshots/Screenshot%202024-11-25%20113211.png)  

### Patients:  
- Create accounts and manage profiles.  
- Book appointments online with doctors.  
- View booking history and manage future appointments.  

![](https://github.com/Dau2004/Juba-Teaching-Hospital/blob/main/Screenshots/Screenshot%202024-11-25%20114437.png)  

---

## Getting Started  

Follow these steps to set up the project locally on your machine:  

### 1. Prerequisites  
Ensure you have the following installed:  
- **XAMPP** or equivalent (Apache, MySQL, PHP).  
- Compatible browser for accessing the app.  

### 2. Setup Instructions  
1. **Start the Server:**  
   Open your XAMPP Control Panel and start **Apache** and **MySQL**.  

2. **Extract Files:**  
   Unzip the downloaded source code and copy the folder into the `htdocs` directory of XAMPP.  

3. **Database Setup:**  
   - Open a browser and go to [PHPMyAdmin](http://localhost/phpmyadmin).  
   - Create a new database named `juba_hospital`.  
   - Import the provided SQL file (`juba_hospital.sql`) from the root folder of the project.  

4. **Access the Application:**  
   - Visit the app in your browser via [http://localhost/juba_hospital](http://localhost/juba_hospital).  

### 3. Built-in Accounts  
Use the following demo accounts for testing:  

**Admin:**  
- **Email:** admin@juba.com  
- **Password:** 123  

**Doctor:**  
- **Email:** doctor@juba.com  
- **Password:** 123  

**Patient:**  
- **Email:** patient@juba.com  
- **Password:** 123  

---

## Technologies Used  
- **Apache Version:** 2.4.39  
- **PHP Version:** 7.3.5  
- **MySQL Version:** 5.7.26  

---

