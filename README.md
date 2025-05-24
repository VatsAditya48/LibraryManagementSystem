# GUI Library Management System

This is a Java Swing-based Library Management System that uses MySQL to store and manage book information.

## Features

- Add new books
- Delete books by ID
- Search books by ID
- View all books
- Automatically creates table if not present

## Requirements

- Java JDK 8+
- MySQL
- MySQL Connector/J (add to classpath)

## How to Run

1. Compile the Java file:
   ```
   javac -cp .:mysql-connector-j.jar src/LibraryGUI.java
   ```

2. Run the compiled class:
   ```
   java -cp .:mysql-connector-j.jar src.LibraryGUI
   ```

*Replace `mysql-connector-j.jar` with your actual path.*

## Author

Aditya Vatsa , Depanshu Dubey , Harsh Raj
