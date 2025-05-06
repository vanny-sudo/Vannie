
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

### ✅ Phase I: Project Planning and Requirement Gathering

<img width="626" alt="001" src="https://github.com/user-attachments/assets/8d0bca5b-9279-4aa3-8746-0024e7d8dcf6" />
<img width="629" alt="002" src="https://github.com/user-attachments/assets/52a43c01-6225-46fa-9468-962b91b09523" />
<img width="626" alt="003" src="https://github.com/user-attachments/assets/b18c35f0-0b67-4313-9450-e57d155e6a91" />


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

* Converted the ER model into a normalized relational schema (3NF)
* Designed tables, defined data types, primary and foreign keys

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
