# Employee Payroll Management System
# Employee Payroll System – Java  

## 📌 Overview  
The **Employee Payroll System** is a Java-based application that manages employee salary records for both **Full-Time** and **Part-Time** employees.  
It demonstrates **OOP concepts** like **abstraction**, **inheritance**, **polymorphism**, and **encapsulation**, while providing functionalities such as adding, removing, and displaying employees along with their calculated salaries.  

---

## 🎯 Features  
- **Add Employees** – Supports both full-time and part-time employees.  
- **Remove Employees** – Remove employees using their unique ID.  
- **Display Employees** – View all employees with their name, ID, and calculated salary.  
- **Salary Calculation**:  
  - Full-Time: Fixed monthly salary.  
  - Part-Time: Salary = `Hours Worked × Hourly Rate`.  
- Demonstrates **core Java concepts**.  

---

## 🛠️ Technologies Used  
- **Language:** Java (JDK 8+)  
- **Concepts:** OOP (Abstraction, Inheritance, Polymorphism, Encapsulation)  
- **IDE:** IntelliJ IDEA / Eclipse / VS Code  

---

## 📂 Project Structure  

EmployeePayrollSystem/
│
├── Main.java # Main class to run the program
├── Employee.java # Abstract base class
├── FullTimeEmployee.java # Full-time employee implementation
├── PartTimeEmployee.java # Part-time employee implementation
└── PayrollSystem.java # Manages employee records

---
## 📖 Concepts Demonstrated
Abstract Class – Employee is abstract with an abstract method calculateSalary().

Method Overriding – Full-time and part-time salary calculations are implemented differently.

Polymorphism – Both employee types are stored in a single list.

Encapsulation – Private fields with getters.

Inheritance – Full-time and part-time classes extend Employee.

## ✨ Future Enhancements
Add database integration (MySQL/SQLite).

Add GUI using JavaFX or Swing.

Implement file-based data persistence.

Include employee search functionality.
---

## Author
Abhishek Upadhyay  
Email: abhishekjaysain777@gmail.com  
GitHub: [Theupadhyay](https://github.com/Theupadhyay)  

---

## 🚀 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/EmployeePayrollSystem.git
cd EmployeePayrollSystem
javac Main.java
java Main


Initial Employee Details :
Employee [Name=Abhishek, id=1, salary=100000.0]
Employee [Name=Ashish, id=2, salary=80000.0]

Removing Employees
Remaining Employee Details
Employee [Name=Abhishek, id=1, salary=100000.0]




