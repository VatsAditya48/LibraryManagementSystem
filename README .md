# 🧑‍🎓 Student Management System (Java Swing + MySQL)

This is a simple Java desktop application built using **Java Swing** for the UI and **MySQL** as the database backend. The application allows users to **Insert**, **Update**, **Delete**, and **View** student records. It also includes functionality to **count total students** in the database.

---

## 📌 Features

- 📥 Insert student details
- ✏️ Update existing student records
- ❌ Delete student entries
- 📋 Display all students in a table
- 🔢 Show total number of students
- 📅 Format borrowed and return dates using date pickers

---

## 🛠️ Technologies Used

- Java SE (Swing)
- MySQL Database
- JDBC (Java Database Connectivity)
- NetBeans IDE (optional)
- JDateChooser (from `toedter` library for date picking)

---

## 🧰 Prerequisites

- JDK 8 or higher
- MySQL Server
- MySQL JDBC Driver (Connector/J)
- NetBeans IDE or any Java IDE (recommended)
- MySQL Workbench (optional)

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/student-management-swing.git
   cd student-management-swing
   ```

2. **Create the Database and Table**
   Run the following SQL commands in MySQL Workbench or your MySQL CLI:
   ```sql
   CREATE DATABASE librarydb;

   USE librarydb;

   CREATE TABLE student (
       studentid VARCHAR(20) PRIMARY KEY,
       studentname VARCHAR(100),
       email VARCHAR(100),
       address VARCHAR(255)
   );
   ```

3. **Configure JDBC Driver**
   - Download MySQL Connector/J from [here](https://dev.mysql.com/downloads/connector/j/).
   - Add the `mysql-connector-java-x.x.x.jar` to your project libraries.

4. **Run the Application**
   - Open the project in NetBeans or your preferred IDE.
   - Run the `StudentJFrame.java` file.

---

## 🧪 Example Usage

- Enter `Student ID`, `Name`, `Email`, and `Address`, then click **Insert**.
- Select a row from the table, modify values, and click **Update**.
- Select a student ID and click **Delete** to remove the record.
- Click on the **Total** button to view the count of students.

---

## 🧑‍💻 Author

- **Your Name**  
  [GitHub Profile](https://github.com/your-username)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

For any queries or feedback, feel free to open an issue or contact me at `your-email@example.com`.
