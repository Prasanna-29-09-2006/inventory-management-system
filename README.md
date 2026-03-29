INVENTORY MONITORING SYSTEM

A Java Spring Boot based Inventory Management System that helps businesses manage products, monitor stock levels, track inventory changes, and generate reports efficiently.

This system provides role-based access control, low stock alerts, dashboard analytics, and exportable reports in CSV and PDF formats.

 FEATURES
 
Secure Login Authentication,
Role-Based Access (Admin / User),
Product Management (Add / Update / View Products),
Stock Update Tracking,
Low Stock Detection,
Inventory Dashboard Analytics,
Stock Change Logs,
Export Reports (CSV / PDF),
Automated Email Alerts for Low Stock.

TECHNOLOGY STACK
 
BACKEND

Java,
Spring Boot,
Spring Security,
Spring Data JPA.

FRONTEND

Thymeleaf,
HTML,
CSS,
Bootstrap.

DATABASE

MySQL

TOOLS

Maven,
Git & GitHub,
IntelliJ IDEA,
iText PDF,
OpenCSV.

 PROJECT STRUCTURE
 
src └── main ├── java │ └── com.enterprise.inventory │ ├── config │ ├── controller │ ├── entity │ ├── repository │ ├── security │ └── service │ └── resources ├── templates └── application.properties


---

 DEFAULT LOGIN CREDENTIALS

### Admin Login

Username: admin,
Password: admin123

### User Login

Username: user1,
Password: admin123



  SYSTEM MODULES

1) AUTHENTICATION MODULE

Provides secure login using **Spring Security**.

 2) PRODUCT MANAGEMENT MODULE

Allows adding, updating, and managing inventory products.

 3) INVENTORY TRACKING MODULE

Tracks stock updates and monitors product quantity levels.

 4) DASHBOARD ANALYTICS

Displays inventory statistics and product insights.

 5) STOCK LOG SYSTEM

Maintains history of inventory updates.

 6) REPORTING MODULE

Generates reports in **CSV and PDF format**.

 7) EMAIL NOTIFICATION SYSTEM

Automatically sends alerts when stock quantity falls below the reorder level.

##  PROJECT SCREENSHOTS

###  Login Page
![Login](./screenshot/login.png)

###  Dashboard
![Dashboard](./screenshot/dashboard.png)

###  Products Page
![Products](./screenshot/product.png)

###  Add Product
![Add Product](./screenshot/add-product.png)

###  Low Stock Monitoring
![Low Stock](./screenshot/low-stock.png)

###  Visualization / Analytics
![Analytics](./screenshot/analytics.png)

###  Stock Logs
![Stock Logs](./screenshot/stock-logs.png)

###  Settings
![Settings](./screenshot/settings.png)

  HOW TO RUN THE PROJECT

 1) CLONE THE REPOSITORY

git clone https://github.com/ponkarthika96/inventory-monitoring-report-system.git


 2) OPEN IN IntelliJ IDEA

Open the project using **IntelliJ IDEA**.

 3) CONFIGURE DATABASE

Edit `application.properties`


spring.datasource.url=jdbc:mysql://localhost:3306/inventory_db
spring.datasource.username=root
spring.datasource.password=yourpassword


 4) RUN THE APPLICATION

Run the Spring Boot application:

InventoryApplication.java


5) OPEN BROWSER

http://localhost:8080/login


---

 AUTHOR

**Ponkarthika**

GitHub: https://github.com/ponkarthika96

 CONTRIBUTORS

Team members who contributed and supported:

- Prasanna Venkatesh V
- Prasanna S
- Vihashini R

---

 LICENSE

This project is licensed under the **MIT License**.
