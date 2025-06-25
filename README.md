# 🎓 Student Record Management System (Java CLI Project)

## 📖 Description

The **Student Record Management System** is a console-based Java application that enables users to manage student data with basic CRUD (Create, Read, Update, Delete) operations. Each student record includes an ID, name, and marks.

This beginner-friendly project demonstrates key Java concepts including:
- Object-Oriented Programming (OOP)
- Encapsulation through private fields and public getters/setters
- Use of `ArrayList` from Java Collections Framework
- Menu-driven CLI using loops and conditionals

---

## ✅ Objective

Create a Command Line Interface (CLI) based system to:
- Add new student records
- View all student records
- Update a student record
- Delete a student record

---

## 🛠️ Tools & Technologies

- **Programming Language**: Java
- **IDE**: VS Code or IntelliJ Community Edition
- **Build Tool**: javac (Java Compiler)
- **Data Storage**: In-memory `ArrayList`

---

## 🔑 Key Concepts Used

| Concept                  | Usage Description |
|--------------------------|-------------------|
| **Classes**              | `Student` class holds student data fields |
| **Collections (ArrayList)** | Stores and manages multiple student objects |
| **Loops**                | Controls menu interaction and record iteration |
| **Encapsulation**        | Student data fields are private with public access methods |

---

## 📂 Project Structure

StudentRecordSystem/
├── Student.java # Student class (fields + methods)
└── StudentManagementSystem.java # Main application logic (menu + operations)


---

## 📋 Features (CRUD Operations)

- **➕ Add Student**: Enter ID, name, and marks to add a student record.
- **📄 View Students**: Display all stored student records.
- **✏️ Update Student**: Modify name and marks by providing student ID.
- **🗑️ Delete Student**: Remove student record by ID.
- **🚪 Exit**: Safely exit the application.

---

## 🚀 How to Run

1. **Save Files**
   - `Student.java`
   - `StudentManagementSystem.java`

2. **Open terminal in project folder** and compile:
   
   javac Student.java StudentManagementSystem.java
Run the application:


java StudentManagementSystem
