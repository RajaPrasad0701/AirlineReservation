# Airline Reservation System

## Overview
This project is a simple **Airline Reservation System** developed in **C++** with **MySQL** as the database backend. It allows users to view available flights, reserve seats, and manage flight bookings. The program interacts with a MySQL database to store and retrieve airline reservation data dynamically.

## Features
- Connects to MySQL database
- Displays available flights
- Allows users to reserve seats
- Updates seat availability dynamically
- Handles error messages for database interactions

## Technologies Used
- **Programming Language:** C++
- **Database:** MySQL
- **Libraries:**
  - `<mysql.h>` for MySQL connectivity
  - `<windows.h>` for system operations
  - `<sstream>` for data type conversions

## Installation and Setup
1. **Install MySQL Server**
   - Ensure MySQL is installed and running on your system.
2. **Set Up the Database**
   - Create a database named `mydb`.
   - Create a table named `Airline` using the following SQL schema:
   
   ```sql
   CREATE TABLE Airline (
       Fnumber VARCHAR(10) PRIMARY KEY,
       Departure VARCHAR(50),
       Destination VARCHAR(50),
       Seat INT
   );
   ```
3. **Update Database Credentials**
   - Modify the `HOST`, `USER`, `PW`, and `DB` variables in the code to match your MySQL configuration.
4. **Compile and Run the Program**
   - Compile the program using a C++ compiler with MySQL support.
   - Run the executable.

## How to Use
1. Upon execution, the program connects to the MySQL database.
2. It inserts predefined flight records into the database.
3. Users are presented with options to:
   - View available flights
   - Reserve a seat
   - Exit the program
4. When a seat is reserved, the database updates the seat count dynamically.
5. The program exits upon user request.

## Future Enhancements
- Implement user authentication for booking verification.
- Add a graphical user interface (GUI) for better usability.
- Enable cancellation and modification of reservations.

---

# Resume Content for C/C++ Developer Role

## **Projects**
### **Airline Reservation System**
**Technologies Used:** C++, MySQL, Windows API
- Developed a **C++-based airline reservation system** that connects with a **MySQL database**.
- Implemented **flight booking, seat reservation, and real-time database updates**.
- Used **MySQL C API** to interact with the database and manage flight data.
- Optimized database queries for better performance.
- Improved error handling for database connectivity and user inputs.

## **Technical Skills**
- **Programming Languages:** C, C++
- **Database Management:** MySQL, SQL
- **Data Structures & Algorithms**
- **Operating Systems:** Windows, Linux
- **Version Control:** Git
- **Problem Solving & Debugging**

## **Work Experience / Internships**
- [Add any relevant work experience related to C++ development]

## **Certifications & Achievements**
- Certification in C++ Programming (if any)
- Competitive programming participation (if any)

---
This README provides clarity on the project, and the resume content highlights the relevant experience for a C/C++ role. Let me know if you need any modifications!

