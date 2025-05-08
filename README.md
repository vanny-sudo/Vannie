
---

# 🏛️ E-Government Feedbacks and Complaints Management System

📢 A modern, user-centric platform that allows citizens to **submit feedback** and **lodge complaints** about government services in a transparent and accountable way. This system helps the government to track issues, respond efficiently, and improve public services.

---

## 📌 Features

### Citizens can:

* 📝 Submit feedback and complaints
* 📄 View submission history
* 📬 Get notifications about responses

### Government officials can:

* 📊 Manage and categorize feedback/complaints
* 🕵️ Track and respond to submissions
* 🧾 Generate reports for transparency

### System features:

* 🔐 Role-based access control (Admin, Official, Citizen)
* 🗃️ Secure Oracle database backend
* 🔄 Real-time status updates
* 🧠 Intelligent categorization and filtering

---

## 📚 Project Development Phases

This system was developed through the following seven structured and successfully completed phases:

### ✅ Phase I: Project Planning and Requirement Gathering.

**Problem Statement:**
Citizens lack an efficient channel to report government service issues, leading to unresolved concerns and reduced public trust in government responsiveness.
  
**Requirements:** This project will be a 5-7 month project which requires user account management, complaint submission/tracking, and admin oversight functionalities. Technical needs include a mobile-responsive application with secure authentication, while maintaining an intuitive interface with accessibility features and multi-language support.

**Solutions:**
* User-friendly digital platform for submitting feedback and complaints
* Transparent tracking system for complaint status and resolution
* Notification system to keep citizens updated on resolution progress.

https://1drv.ms/p/c/1f79cabbe4beca38/Ea_bopKwzuRAvaJ-pZclZ0wBSIgUXAqsuSfim_10v-ijMg?e=k8gAwo
### ✅ Phase II: Conceptual Design
![image](https://github.com/user-attachments/assets/6420ecad-2b31-46f9-8654-44d25a99fb71)
📘 Business Process Modeling.
This phase focuses on designing the core process of how citizens interact with the system and how government departments handle complaints.

🎯 Key Goals:
Enable citizens to submit and track complaints digitally.
Improve government response times and accountability.
Use complaint data to enhance public service delivery.

👥 Main Roles:
Citizens: Submit and follow up on issues.
Staff: Validate, assign, and resolve complaints.
Departments: Handle specific issues and implement improvements.
System Entities: Manage records, responses, and document attachments.

📈 Outcome:
A transparent, structured, and efficient feedback process that improves trust, speeds up resolutions, and supports data-driven decisions.

### ✅ Phase III: Logical Design
![image](https://github.com/user-attachments/assets/ac459309-8d7b-44bf-9a20-13236c3f9e53)
* Details.
  
This Logical Model design of an E-Government Feedback & Complains Management System schema includes:

1.	Citizens - Stores citizen information including ID, name, address, phone number, and national ID
2.	Departments - Contains department information with ID, name, description, and contact details
3.	Complaints_Feedbacks - Records citizen complaints with references to both citizens and departments
4.	Responses - Tracks official responses to complaints
5.	Attachments - Manages files attached to complaints
   
In additional there is Officials which is necessary for tracking who responded to complaints.
The schema includes appropriate foreign key relationships to connect the tables, as well as indexes for better query performance. 


### ✅ Phase IV: Physical Implementation

* Implemented the schema using Oracle 19c
* Created and tested all database tables with necessary constraints

### ✅ Phase V: Data Manipulation and Advanced Queries

* Developed and tested `INSERT`, `UPDATE`, `DELETE`, and `SELECT` queries
* Created useful views and reports for system users

### ✅ Phase VI: Application Programming and User Interaction

* Built a Java-based interface (CLI/Web) with user login and role separation
* Connected application logic to Oracle using PL/SQL procedures and functions

### ✅ Phase VII: Advanced PL/SQL Programming and Auditing

* Implemented triggers for:

  * Logging data changes
  * Enforcing data restrictions
* Designed audit tables to track actions like deletions and updates

---

## 🧑‍💻 Technologies Used

| Component           | Technology                            |
| ------------------- | ------------------------------------- |
| 👨‍💻 Backend       | PL/SQL (Oracle), Triggers, Procedures |
| 🗄️ Database        | Oracle 19c                            |
| 🌐 Interface        | Java (CLI-based or web UI)            |
| 🔍 Logging & Audits | PL/SQL Triggers & Audit Tables        |

---

## 🛠️ Setup Instructions

1. **Set up the Oracle Database:**

* Import SQL scripts from the `db/` directory
* Run triggers, procedures, and constraints

2. **Run the application:**

   * Use the Java-based interface (CLI/Web)
   * Login as **admin**, **official**, or **citizen**

---

## 🗃️ Folder Structure

```
e-gov-feedbacks-complaints/
├── db/                   # SQL scripts, triggers, procedures
├── docs/                 # Documentation and reports
└── README.md             # Project readme
```

---

## 🧪 Testing & Validation

* ✅ Unit tested PL/SQL procedures and triggers
* ✅ Data validation with constraints and input checks
* ✅ Manual role-based scenario testing

---

## 📈 Project Objectives

🎯 Increase government transparency and citizen trust by:

* Empowering citizens to express concerns
* Ensuring structured and traceable responses
* Leveraging technology to drive civic engagement

---

## 🔒 Security & Integrity

* 🔐 Role-based access control
* 🧾 Full audit logs for changes and deletions
* ⚠️ Triggers ensure data consistency

---

## 🤝 Contributors

* 👨‍🎓 **Name:** IRAKOZE Grace Vanny – Developer & Database Designer
* 🆔 **ID:** 26425
* 🏢 **Role:** PL/SQL Programmer

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

## 📬 Feedback & Issues

Feel free to [open an issue](https://github.com/yourusername/e-gov-feedbacks-complaints/issues) or suggest improvements. Contributions are welcome!

---
