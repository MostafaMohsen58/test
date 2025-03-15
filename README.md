# Inventory Management System

### Team Members:
- Reem Atef Abdelkhaleq Heikal
- Ahmed Mohamed Ramadan
- Mostafa Mohsen Elnahas

## 📌 Project Overview
The **Inventory Management System** is a **desktop application** built with **C# and .NET WinForms**. It helps businesses efficiently track products, suppliers, stock levels, and sales transactions.

### ✨ Key Features:
✅ **Product Management** – CRUD operations, search by name/category/supplier  
✅ **Supplier Management** – Manage supplier details and track supply history  
✅ **Stock Management** – Monitor stock levels, get low-stock alerts, and track stock movements  
✅ **Sales Management** – Process sales transactions, generate receipts/invoices  
✅ **Reports & Analytics** – Generate sales reports, stock reports, and performance analysis (SSRS)  

---

## 🛠️ System Requirements

### Hardware:
- Minimum **4GB RAM** (Recommended: 8GB)
- **2GHz Dual-Core Processor** or higher
- At least **500MB free disk space**

### Software:
- **Windows 10 or later**
- **.NET 9.0**
- **SQL Server 2019 or

## 🚀 Installation & Setup

### 🔹 Step 1: Clone the Repository
```sh
git clone https://github.com/YOUR_USERNAME/Inventory-Management-System.git
cd Inventory-Management-System
```
### 🔹 Step 2: Database Setup
- **Install and configure SQL Server.**
- **Open SQL Server Management Studio (SSMS) and create a new database: InventoryDB.***
- **Create appsettings.json in the DAL layer:**
  ```sh
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=InventoryDB;Trusted_Connection=True;"
  }
```



















Step 3: Application Setup
Open the project in Visual Studio.
Restore NuGet packages (Entity Framework Core, Dapper, etc.).
Build the solution to ensure all dependencies are installed.
Run database migrations if using EF Core:
sh
Copy
Edit
dotnet ef database update
Step 4: SSRS Report Setup
Install and configure SQL Server Reporting Services (SSRS).
Deploy the SSRS reports to the report server.
Update the report server URL in the application settings.
Ensure the app can access SSRS for generating reports.
Step 5: Running the Application
Set WinForms Project as the startup project in Visual Studio.
Press Ctrl + F5 to run the application.
Login using default credentials:
Username: admin
Password: 123456789
Start managing inventory! 🚀
📊 Use Case Diagram
(Replace with actual link if hosted online)

📌 ERD (Entity Relationship Diagram)
(Replace with actual link if hosted online)

👤 User Roles & Permissions
Role	Permissions
Admin	Manage users, products, suppliers, stock, and sales. View reports.
Manager	Manage products, suppliers, stock. Review sales and reports.
Staff	Process sales transactions, add stock, generate receipts.
📷 Screenshots (Optional)


💡 Troubleshooting & FAQs
1. Database connection error?
✔ Ensure SQL Server is running and the connection string is correct.
✔ Verify that InventoryDB exists in SQL Server.

2. Application crashes on startup?
✔ Check if all dependencies are installed.
✔ Run dotnet restore in the project directory.

3. Reports not generating?
✔ Ensure SQL Server Reporting Services (SSRS) is properly installed.
✔ Verify that the report server URL is correctly set in the application.

📜 License
This project is open-source under the MIT License.

📞 Contact & Contributions
Feel free to fork, contribute, or report issues! 😊

🔗 GitHub Repository: Inventory Management System (Replace with actual link)

📧 Contact: [your.email@example.com] (Optional)
