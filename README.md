
# ManageMate

## Overview
ManageMate is a simple Java-based Employee Management System that allows efficient management of employee records through a console-based interface. It demonstrates the usage of Object-Oriented Programming (OOP) concepts like Abstraction, Encapsulation, Inheritance, and Polymorphism in Java.

## Features
- Add new Employee details  
- View all Employee records  
- Search Employee by ID  
- Update Employee details  
- Delete Employee record  
- Menu-driven interface for user interaction  
- In-memory data storage using ArrayList  

## Technologies Used
- Java  
- OOP Principles  
- Java Collections Framework (ArrayList)  
- Console-based User Interface  

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/ManageMate.git
cd ManageMate
```

2. Compile the Java files:
```bash
javac *.java
```

3. Run the project:
```bash
java Main
```

## Project Structure
```
├── Main.java               # Entry Point
├── Employee.java           # Employee POJO Class
├── EmployeeManagement.java # Business Logic
└── README.md               # Project Documentation
```

## Sample Functionalities
- Add Employee → Enter name, ID, role, salary  
- View Employees → Lists all added records  
- Search Employee → Get details using Employee ID  
- Update Employee → Modify details  
- Delete Employee → Remove from records  

## Output Example
```
===== ManageMate =====
1. Add Employee
2. View Employees
3. Search Employee
4. Update Employee
5. Delete Employee
6. Exit
Enter your choice:
```

## Future Scope (Optional Enhancements)
- Persistent storage using File or Database  
- GUI using Java Swing/JavaFX  
- Login & Authentication Module  
