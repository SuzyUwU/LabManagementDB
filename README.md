# 🗄️ Lab Management Database (MongoDB)

This repository contains the **MongoDB database structure** used by the **Lab Management System** project.

It provides the required collections and data format so the main application can run correctly.

---

## 🔗 Main Application Repository

👉 **Lab Management System (Java + MongoDB):**  
[Lab Management system](https://github.com/SuzyUwU/LabManagement)

Clone and run the application from the repository above.

---

## 📦 Collections Used

The database uses the following MongoDB collections:

- `Users` – Stores user accounts and credentials
- `Counters` – Generates auto-incremented user IDs
- `Labs` – Stores laboratory information
- `Activities` – Stores lab activities and time slots
- `UserActivities` – Tracks user participation in activities

Collections will be created automatically if they do not already exist.

---

## ⚙️ Usage

1. Import or connect this database to MongoDB (local or Atlas)
2. Ensure the connection URI matches the one used in the main application
3. Run the Lab Management System application

---

## 📌 Notes

- Designed for **educational purposes**
- Works with the official **MongoDB Java Driver**
- No authentication or role system is enforced at database level

---

## 📜 License

This database structure is intended for **learning and academic use**.
