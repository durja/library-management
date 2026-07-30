# 📚 Library Management System

## 🔄 Requirements Solved Using Flow

Record-Triggered Flows were implemented to automate routine library operations without writing code.

* 📅 Automatically set the **Issue Date** when a new Book Issue record is created.
* 📧 Send an email notification to the librarian after a book is successfully issued.
* 💰 Automatically create a **Fine** record when a book is returned after its due date.

---

## ✅ Requirements Solved Using Validation Rules

Validation Rules were used to maintain data accuracy and prevent invalid records from being saved.

* Prevent **Issue Date** from being later than the **Due Date**.
* Prevent **Return Date** from being earlier than the **Issue Date**.
* Ensure mandatory fields such as **Book**, **Member**, and **Due Date** are completed.
* Prevent **Available Copies** from becoming less than zero.

---

## 💻 Requirements That Needed Apex

Apex is suitable for implementing business logic that cannot be handled efficiently using declarative tools.

* Prevent issuing a book when no copies are available.
* Support advanced business logic and future enhancements, such as complex fine calculations or integrations with external systems.

---

## 🎯 Why These Solutions?

* **Flow** was chosen to automate repetitive business processes quickly and efficiently without code.
* **Validation Rules** were used to enforce data quality by preventing invalid data from being saved.
* **Apex** was reserved for complex scenarios that require custom programming and greater flexibility.

---

## 🚀 Outcome

The Library Management System combines **Flows**, **Validation Rules**, and **Apex** to automate library operations, improve data accuracy, reduce manual effort, and provide a reliable and efficient book management process.
