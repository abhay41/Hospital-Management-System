# 🏥 Hospital Management System

A **Java-based desktop application** that simplifies hospital operations such as patient management, ambulance search, employee information, department listing, room check, and more. Built using **Java Swing** for GUI and **MySQL** for database management, this system provides a smooth and efficient experience for hospital staff and administrators.

---

## ✨ Features

- 🆕 **New Patient Registration**  
  Add new patient records with all essential details like name, gender, disease, room number, etc.

- 📝 **Update Patient Details**  
  Modify or update existing patient data such as room number, treatment status, or deposit amount.

- 📋 **Patient Info**  
  View all patients and their details in a tabular format fetched from the database.

- 🔍 **Search Room**  
  Search available or assigned rooms for patients.

- 🛏️ **Room Check**  
  Display room availability and assigned patient status.

- 🚑 **Search Ambulance**  
  Find ambulance records, including availability, number, driver, and location.

- 🧑‍⚕️ **Employee Info**  
  Display all hospital staff with roles, department, and contact details.

- 🏬 **Department Listing**  
  View departments like Cardiology, Neurology, Emergency, etc., along with assigned doctors.

- 💳 **Patient Discharge**  
  Discharge patients and update the database with discharge date and final payment status.

- 📞 **Reception Module**  
  A hub to access patient registration, appointments, and navigation to other modules.

---

## 🛠️ Technologies Used

- **Programming Language**: Java  
- **GUI Framework**: Java Swing  
- **Database**: MySQL  
- **IDE**: IntelliJ IDEA / Eclipse  
- **JDBC**: For database connectivity  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/abhay41/Hospital-Management-System.git
```
## 2. Open the Project in Your IDE
Use IntelliJ IDEA or Eclipse to open the project.

## 3. Set Up the MySQL Database
1. Create a new database in MySQL:
```bash
CREATE DATABASE hospital_db;
```
2. Create the following tables
   - patient_info2
   - room
   - employee
   - department
   - ambulance
   - discharge
💡 Make sure your table fields match those used in the Java code, such as ID, Name, Gender, Room, Disease, Time, Deposit, etc.

## 4. Update Database Connection
Edit the conn.java file with your MySQL database credentials:

```bash
Connection con = DriverManager.getConnection(
  "jdbc:mysql://localhost:3306/hospital_db", "your_username", "your_password"
);
```

## 5. Run the Application
Run the Reception or Main class to launch the GUI-based Hospital Management System.

## 🤝 Contributing
 Contributions are welcome!
 If you'd like to contribute to this project, follow these steps:
1. Fork the repository

2. Create a new branch:
   ```bash
    git checkout -b feature-name
    ```

4. Commit changes:
 ```bash
  git commit -m "Add feature"
 ```
5. Push to the branch:
 ```bash
    git push origin feature-name
  ```
6. Open a Pull Request
## 📽️ Demo Video

[Download/View Demo Video](HMS_Demo_Video.mp4)
