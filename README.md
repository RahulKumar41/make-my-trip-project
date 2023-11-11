Project Write-Up: Automated Web Interaction and File Uploading
Overview
The Web Automation Project is a Java-based automation project designed to create an online travel booking website. This project leverages Selenium WebDriver for web automation, AutoIt for handling file uploads, and a SQL database for storing product data. The objective is to demonstrate end-to-end web automation capabilities, including interacting with web elements, uploading files, and managing a database.

Project Components
1. Selenium WebDriver Integration
Utilizes Selenium WebDriver to automate web interactions.
Opens a web browser and navigates to a travel booking website (e.g., MakeMyTrip).
Implements the Page Object Design Pattern to organize web elements.
2. AutoIt Script for File Uploads
Uses AutoIt, a scripting language for automating the Windows GUI, to handle file uploads.
The script opens a file dialog, selects a file from the desktop, and confirms the selection.
AutoIt script is compiled into an executable (.exe) file.
3. Database Integration
Sets up a SQL database (e.g., MySQL) for storing product data.
Creates a table named "products" with columns for product information (e.g., name, price, description).
Establishes a JDBC connection to the database for performing database operations.
4. Screenshot Capture
Captures screenshots of webpages using Selenium WebDriver.
Saves screenshots within a "Screenshots" folder for reference.
Project Workflow
Web Automation:
Selenium WebDriver opens a web browser, navigates to the travel booking website, and interacts with web elements (e.g., entering origin, selecting dates).
File Upload:
The Java program calls the compiled AutoIt script to handle file uploads, allowing users to upload files seamlessly.
Database Operations:
Establishes a JDBC connection to the SQL database.
Performs database operations, including inserting product data into the "products" table.
Screenshot Capture:
Captures screenshots of webpages at relevant points in the automation process.Saves screenshots in the "Screenshots" folder for documentation and debugging purposes.
