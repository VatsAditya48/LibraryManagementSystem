
A simple desktop-based Library Management System built using **Java Swing** for the GUI and **MySQL** for the backend database. This application allows users to add, delete, search, and view books from a local library database.

---

## 🚀 Features

- Add a new book with ID, title, and author
- Delete an existing book by ID
- Search books by title (partial match supported)
- View all books in a table
- Real-time updates in the GUI
- Automatically creates the required table in the database (if not present)

---

## 🛠️ Technologies Used

- Java (JDK 8 or above)
- Java Swing (GUI)
- JDBC (Database connectivity)
- MySQL (Relational Database)

---

## 🗂️ Project Structure

```
LibraryManagementSystem/
├── src/
│   ├── gui/
│   │   └── LibraryGUI.java        # Main GUI application
│   └── db/
│       └── DatabaseHelper.java    # Database operations (JDBC)
└── README.md                      # Project documentation
```

---

## 🧩 Database Setup

1. Ensure MySQL is installed and running.
2. Create a database named `library_db`:

```sql
CREATE DATABASE library_db;
```

> ✅ No need to create the table manually — it is auto-created when the app runs.

3. Update the database credentials in `DatabaseHelper.java`:
```java
conn = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/library_db", 
    "your_username", 
    "your_password"
);
```

---

## 🧪 How to Run

1. Open the project in your Java IDE (e.g., IntelliJ, Eclipse, NetBeans).
2. Ensure the MySQL JDBC driver (`mysql-connector-java`) is added to your project’s classpath.
3. Run the `LibraryGUI.java` file.

---

## 📸 Screenshots

> _(Optional: Add screenshots of your application in use for better presentation)_

---

## 📌 Notes

- Book IDs must be unique and numeric.
- All input fields are required for adding a book.
- Deletion is confirmed via a dialog box.
- Search is case-insensitive and supports partial title matches.

---

## ✅ Future Improvements

- Edit/update book details
- Export book list to CSV or PDF
- Authentication system for librarian login
- Connection pooling for better scalability

---

## 👨‍💻 Author

Aditya Vatsa , Depanshu Dubey , Harsh Raj , Hridesh Shukla
Feel free to connect or contribute!

---


