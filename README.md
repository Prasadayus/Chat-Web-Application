# Web-based Chat Application
This is a real-time chat application developed using HTML, CSS, PHP, MySQL, and pure JavaScript Ajax. Follow the steps below to set up and run the application on your local machine using XAMPP.

# Prerequisites
* XAMPP: Ensure XAMPP is installed on your system. You can download it from here.
* Browser: Any modern web browser (Chrome, Firefox, Edge, etc.).
  
# Installation and Setup
### Step 1: Set up XAMPP
* Start XAMPP Control Panel.
* Start the Apache and MySQL modules.
### Step 2: Set up the Project
* Download or clone the chat application project to your local machine.
* Copy the entire project folder to the htdocs directory of your XAMPP installation. The default path is usually:
 ```
 C:\xampp\htdocs\
```
For example, if your project folder is named chatapp, it should be:
 ```
C:\xampp\htdocs\chatapp\
 ```
### Step 3: Create and Import the Database
* Open your web browser and navigate to:
  ```
  http://localhost/phpmyadmin
  ```
 * Create a new database named chatapp.
* After creating the database, click on the Import tab.
* Click on the Choose File button and select the SQL file provided with the project i.e. chatapp.sql.
* Click on the Go button to import the SQL file into the newly created database.

