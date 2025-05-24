# 📚 Library Management System (Java + MySQL)

This is a simple GUI-based Library Management System developed using **Java Swing** for the interface and **MySQL** as the backend database. The application allows you to add books to the library and store them in a persistent database using **JDBC**.

---

## 📁 Project Structure

```
Library-Management-System/
├── src/                         # Java source files
│   ├── MainFrame.java           # Main GUI interface
│   ├── Book.java                # Model class
│   ├── BookDAO.java             # Data Access Object
│   └── DBConnection.java        # JDBC connection + table creation
├── database/
│   └── library_schema.sql       # SQL script to create the database & table
├── .gitignore                   # Git ignored files list
├── LICENSE                      # MIT License
└── README.md                    # Project documentation
```

---

## ✅ Features

- 📘 Add books with title and author
- 🪟 Simple and clean Java Swing UI
- 🗃️ MySQL database connectivity with JDBC
- 🧱 Auto-creates table if it doesn't exist

---

## ⚙️ Setup Instructions

### ✅ Requirements

- Java JDK 8 or later
- MySQL Server
- MySQL JDBC Driver (e.g., `mysql-connector-java-8.x.x.jar`)
- IDE (e.g., IntelliJ, Eclipse, NetBeans)

### 🏁 Steps to Run the Project

1. **Clone or Download the Repository**

   ```bash
   git clone https://github.com/your-username/Library-Management-System.git
   ```

2. **Set Up the MySQL Database**

   - Open MySQL Workbench or CLI
   - Run the SQL script:

     ```sql
     SOURCE path/to/library_schema.sql;
     ```

3. **Configure Database in `DBConnection.java`**

   ```java
   DriverManager.getConnection("jdbc:mysql://localhost:3306/library", "your-username", "your-password");
   ```

4. **Add MySQL JDBC Driver to Project Classpath**

5. **Compile and Run**

   Run `MainFrame.java` to launch the app and start adding books.

---

## 📌 Notes

- On first launch, the app creates the `books` table automatically if it does not exist.
- Make sure MySQL is running before executing the application.

---

## 👤 Author

**Aditya Vatsa**

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
