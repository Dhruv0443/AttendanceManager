**📌 Overview** 

Camera-Based Attendance Management Using QR is an efficient and contactless attendance system that leverages QR codes and camera-based scanning to record attendance. The system automates attendance tracking, ensuring accuracy and ease of use in various environments such as schools, offices, and events.

**⚡ Features**

QR code-based identification for students/employees.

Camera integration for QR code scanning.

Secure database storage for attendance records.

User-friendly interface built in Apache NetBeans.

Real-time logging and reporting.

**🏗 Technologies Used**

Apache NetBeans (Integrated Development Environment)

Java (Core programming language)

MySQL (Database management)

Swing (GUI development)

**🚀 Installation & Setup**

Prerequisites
Ensure you have the following installed:

Apache NetBeans IDE

Java Development Kit (JDK)

MySQL Database Server


Steps to Set Up
Clone the repository:

bash
git clone https://github.com/Dhruv0443/AttendaceManager.git

Open the project in Apache NetBeans.

Set up the MySQL database using the provided schema.

Run the project and start scanning QR codes.

📁 Camera-Attendance-QR
 ├── 📁 src
 │   ├── 📁 dao
 │   │   ├── 📜 ConnectionProvider.java
 │   │   ├── 📜 tables.java
 │   ├── 📁 forms
 │   │   ├── 📜 Dashboard.java
 │   │   ├── 📜 UserRegistration.java
 │   │   ├── 📜 ViewUser.java
 │   │   ├── 📜 UpdateUser.java
 │   │   ├── 📜 DeleteUser.java
 │   │   ├── 📜 GenerateQR.java
 │   │   ├── 📜 ViewQR.java
 │   │   ├── 📜 MarkAttendance.java
 │   │   ├── 📜 ViewAttendance.java
 │   ├── 📁 images
 ├── 📁 qrCodes
 ├── 📁 utility
 │   ├── 📁 images
 │   ├── 📜 Utility.java
 ├── 📜 README.md
 ├── 📜 LICENSE
 ├── 📜 .gitignore


✨** How It Works**

A unique QR code is generated for each individual.

The camera scans the QR code and extracts information.

The extracted details are checked against the database.

Attendance is marked and stored securely.
