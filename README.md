# Student Enrollment Form - JsonPowerDB

> A lightweight, serverless web application for managing student enrollment records, built using HTML, CSS, JavaScript, and JsonPowerDB.

## Table of Contents
- [Description](#description)
- [Illustrations](#illustrations)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Release History](#release-history)
- [Sources & Acknowledgements](#sources--acknowledgements)

---

## Description
This project is a micro-project designed to demonstrate the implementation of a serverless web application. It features a **Student Enrollment Form** that stores and retrieves data directly from **JsonPowerDB (JPDB)** via REST APIs. 

The application logic automatically checks if a student's Roll Number (Primary Key) already exists in the database. If it is a new record, the user can save the details. If the record exists, the form dynamically retrieves the data and allows the user to update it.

---

## Illustrations
*(Note to developer: Take a screenshot of your form running in the browser, save it as `form-screenshot.png` in your repository, and uncomment the line below to display it!)*

<!-- ![Student Enrollment Form UI](./form-screenshot.png) -->

---

## Benefits of using JsonPowerDB
This project leverages JsonPowerDB, a Real Time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. Its key benefits include:
* **Serverless Architecture:** Eliminates the need for a middle-tier server (like Node.js or PHP). The frontend HTML/JS directly communicates with the database.
* **Schema-Free:** No need to pre-define tables and columns. The database automatically adapts to the JSON data sent to it.
* **Incredibly Fast:** Built on a proprietary architecture designed to deliver high performance for real-time applications.
* **Low Code Development:** Reduces backend code development time significantly by providing ready-to-use APIs for CRUD operations.
* **Cost-Effective:** Minimal setup and maintenance overhead compared to traditional SQL databases.

---

## Scope of Functionalities
The application currently supports the following features:
* **Dynamic Form Control:** Input fields and buttons are dynamically enabled or disabled based on the user's interaction state.
* **Existence Check:** Automatically queries the database upon entering the Primary Key (Roll No) to determine if it is a new entry or an existing one.
* **Data Validation:** Prevents form submission if any input fields are left blank.
* **Create (Save):** Inserts new student records into the database.
* **Update:** Modifies existing student records without overwriting the Primary Key.
* **Reset:** Clears the form and returns it to its default initialization state.

---

## Examples of Use

### How to Run the Project Locally
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)


Release History 
v1.0.0 - August 2026

Initial Release.

Added HTML/CSS UI design.

Integrated jQuery AJAX calls to JsonPowerDB IRL and IML URIs.

Implemented Step-2 form initialization logic, Data Validation, Save, Update, and Reset functionalities.



Sources & Acknowledgements
atabase Backend: JsonPowerDB by Login2Explore

Micro-Project Guidelines: Developed as part of academic/learning coursework requirements.

Author: Gaurang
