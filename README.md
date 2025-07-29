# 🧳 Tourism Management System – Java Project

## 📌 Overview

The **Tourism Management System** is a Java-based application developed to simplify and automate the workflow of travel agencies and tourism companies. This project allows users to manage customer details, tour packages, bookings, and administrative tasks efficiently.

This project is suitable for academic submission or as a beginner-to-intermediate level Java project.

---

## 💻 Tech Stack

- **Language**: Java (Core Java, OOP)
- **Interface**: Command Line Interface (CLI) *(GUI with Swing/JavaFX optional)*
- **Database**: MySQL (via JDBC) or file handling (based on implementation)
- **IDE**: Eclipse / IntelliJ IDEA / NetBeans
- **Build Tool**: Manual (no Maven/Gradle needed for simple setups)

---

## 🚀 Features

- ✅ Add, update, delete customer details
- ✅ List and manage tour packages
- ✅ Book tours and view booking history
- ✅ Assign tour guides to packages
- ✅ Admin section for managing system data
- ✅ Simple and intuitive interface (CLI or Swing-based)

---

## 📁 Project Structure

```
TourismManagementSystem/
│
├── src/
│   ├── Main.java               # Entry point
│   ├── Customer.java           # Customer model
│   ├── TourPackage.java        # Package model
│   ├── Booking.java            # Booking logic
│   ├── Admin.java              # Admin operations
│   └── Database.java           # JDBC connections (optional)
│
├── tourism.sql                 # MySQL schema (if database is used)
├── README.md
└── resources/
    └── banner.txt              # ASCII banner (optional)
```

---

## 🧑‍💻 Getting Started

### 🔧 Prerequisites

- Java JDK 8 or above
- MySQL server (optional)
- IDE like Eclipse, IntelliJ, or any Java compiler

---

### ▶️ Running the Project (CLI Version)

#### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/TourismManagementSystem.git
cd TourismManagementSystem
```

#### Step 2: Compile the Code
```bash
javac src/*.java
```

#### Step 3: Run the Application
```bash
java src.Main
```

---

### 🛢️ Database Setup (If using MySQL)

1. Import the `tourism.sql` file into your MySQL server:
```bash
mysql -u root -p < tourism.sql
```

2. Edit your `Database.java` file with credentials:
```java
String url = "jdbc:mysql://localhost:3306/tourism";
String username = "root";
String password = "yourpassword";
```

---

## 📚 Concepts Practiced

- Core Java (OOP, inheritance, interfaces)
- JDBC for database connectivity
- Exception handling
- Command-line I/O
- File and/or DB-based data storage

---

## 📷 Screenshots

*(Insert CLI or GUI screenshots here if available, e.g., terminal view or Swing UI)*

---

## 🌟 Future Enhancements

- [ ] Migrate to Java Swing or JavaFX GUI
- [ ] Add user login and role-based access
- [ ] Export booking reports to PDF
- [ ] REST API version using Spring Boot
- [ ] Mobile app integration

---

## 🙋‍♂️ Author

**Harsh Krishnatre**  
📧 [Gmail](mailto:krish.15082003@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/harsh-krishnatre-583449339/)  
💻 [GitHub](https://github.com/Harsh-Krishnatre)

---



## 🤝 Contributions

Contributions, suggestions, and pull requests are welcome!  
Feel free to fork this repo and submit improvements.