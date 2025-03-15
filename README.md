# Inventory Management System

## 📌 Project Overview
The **Inventory Management System** is a **desktop application** built with **C# and .NET WinForms**. It helps businesses efficiently track products, suppliers, stock levels, and sales transactions.

### ✨ Key Features:
✅ **Product Management** – CRUD operations, search by name/category/supplier  
✅ **Supplier Management** – Manage supplier details and track supply history  
✅ **Stock Management** – Monitor stock levels, get low-stock alerts, and track stock movements  
✅ **Sales Management** – Process sales transactions, generate receipts/invoices  
✅ **Reports & Analytics** – Generate sales reports, stock reports, and performance analysis (SSRS)  

## 🔹 Step 1: Prerequisites

* .NET SDK (version compatible with the project)
* SQL Server
* Visual Studio
* SQL Server Reporting Services (SSRS) (optional, for reporting)

## 🔹 Step 2: Database Setup

1.  Create a new database named `InventoryDB` in SQL Server.
2.  Run the provided SQL scripts to create the necessary tables and relationships.
    * (Replace with instructions or link to SQL scripts)

## 🔹 Step 3: Application Setup

1.  Open the project in Visual Studio.
2.  Restore NuGet packages (Entity Framework Core, Dapper, etc.).
3.  Build the solution to ensure all dependencies are installed.
4.  Run database migrations if using EF Core:

    ```bash
    dotnet ef database update
    ```

## 🔹 Step 4: SSRS Report Setup

1.  Install and configure SQL Server Reporting Services (SSRS).
2.  Deploy the SSRS reports to the report server.
3.  Update the report server URL in the application settings.
4.  Ensure the app can access SSRS for generating reports.

## 🔹 Step 5: Running the Application

1.  Set the WinForms project as the startup project in Visual Studio.
2.  Press `Ctrl + F5` to run the application.
3.  Login using default credentials:
    * Username: `admin`
    * Password: `123456789`
4.  Start managing inventory! 🚀

## 📊 Use Case Diagram

* (Replace with actual link if hosted online)

## 📌 ERD (Entity Relationship Diagram)

* (Replace with actual link if hosted online)

## 👤 User Roles & Permissions

| Role     | Permissions                                                                        |
| -------- | ---------------------------------------------------------------------------------- |
| Admin    | Manage users, products, suppliers, stock, and sales. View reports.                 |
| Manager  | Manage products, stock. Review sales and reports.                                  |
| Staff    | Process sales transactions, add stock, generate receipts.                          |

## 📷 Screenshots (Optional)

* (Add screenshots here if desired)

## 💡 Troubleshooting & FAQs

**❓ 1. Database connection error?**

* ✔ Ensure SQL Server is running and the connection string is correct.
* ✔ Verify that `InventoryDB` exists in SQL Server.

**❓ 2. Application crashes on startup?**

* ✔ Check if all dependencies are installed.
* ✔ Run `dotnet restore` in the project directory.

**❓ 3. Reports not generating?**

* ✔ Ensure SQL Server Reporting Services (SSRS) is properly installed.
* ✔ Verify that the report server URL is correctly set in the application.



## 📞 Contact 
### Team Members:
- Reem Atef Abdelkhaleq Heikal : 
- Ahmed Mohamed Ramadan :
- Mostafa Mohsen Elnahas : https://www.linkedin.com/in/mostafa-elnahas/
Feel free to fork, contribute, or report issues! 😊

* 🔗 GitHub Repository: https://github.com/MostafaMohsen58/InventoryManagmentSystem
* 📧 Contact: [your.email@example.com](Optional)
