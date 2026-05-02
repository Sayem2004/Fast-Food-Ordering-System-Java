#  Fast Food Train Ordering System (Java)

##  Overview

This project is a **Java Swing-based Fast Food Ordering System** developed during our **2nd semester (2022)** at university.

It is a desktop application that allows users to browse food items, place orders, and simulate a basic payment process. The system also includes an **Admin Panel** for managing users and monitoring information.

This project demonstrates **GUI design, event-driven programming, and file-based data handling** in Java.

---

##  Features

###  User Authentication

* User Registration
* Login System
* Forgot Password (Recovery System)

###  User Panel

* Category-based food browsing
* Multiple product pages
* Interactive UI

###  Product System

* View food items with price
* Select quantity
* “Buy Now” option

###  Payment System

* Simple payment interface
* Input-based payment simulation

###  Admin Panel

* Admin Login
* View all user data
* Add/Delete users

---

##  Technologies Used

* **Java**
* **Java Swing (GUI)**
* **File Handling (TXT files)**
* Event-driven programming

---

##  Project Structure

* `Start.java` → Entry point
* `Login / Registration` → Authentication system
* `UserDashboard` → User interface
* `AdminDashboard` → Admin functionalities
* `Category & Product` → Food items
* `Payment` → Payment system
* `Data` → Stores user/admin data
* `image` → UI resources

---

##  Data Storage

* Data is stored using **text files (no database)**
* Files used:

  * `admin_data.txt`
  * `user_data.txt`

---

##  How to Run

1. Open the project in any Java IDE (IntelliJ / Eclipse / NetBeans)
2. Make sure these folders are included:

   * `Classes`
   * `Interfaces`
   * `Data`
   * `image`
3. Run the `Start.java` file

---

##  Limitations

* Uses file-based storage instead of database
* Passwords are stored in plain text (not secure)
* Repetitive code in product classes

---

##  Future Improvements

* Integrate database (MySQL)
* Add password encryption
* Apply MVC architecture
* Reduce code duplication
* Improve UI/UX design

---

##  Authors

* **Md Al-Imran Sayem**
  ID: 22-48023-2
  Email: [22-48023-2@student.aiub.edu](mailto:22-48023-2@student.aiub.edu)

* **Md Mushaddek Al Mubdi**
  ID: 22-47839-2
  Email: [22-47839-2@student.aiub.edu](mailto:22-47839-2@student.aiub.edu)

---

##  Final Note

This project represents our early learning phase in Java and GUI development.
It helped us understand real-world application structure, user interaction, and basic system design.
