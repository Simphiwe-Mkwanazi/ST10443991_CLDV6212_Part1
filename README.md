ABCRetailers.V2 - README Report
📌 Project Overview
ABCRetailers.V2 is a .NET 6 MVC web application designed to streamline online retail operations. The system enables the management of customers, products, and orders while supporting Azure Storage integration for scalability. The project demonstrates real-world retail management solutions, including file uploads, order processing, and customer data management.
🚀 Features
•	Customer Management – Create, edit, and list customer records.
•	Product Management – Maintain product catalog with CRUD operations.
•	Order Management – Place, edit, and view customer orders.
•	File Uploads – Upload and manage product-related files.
•	Azure Integration – Uses IAzureStorageService for blob/file storage.
•	User-Friendly Interface – Razor views with shared layouts.
🛠️ Tech Stack
•	Language: C#
•	Framework: .NET 6 MVC
•	Frontend: Razor Pages (CSHTML)
•	Database: SQL Server / Azure Storage (configurable via appsettings.json)
•	Cloud Services: Azure Blob & File Share Storage
•	IDE: Visual Studio 2022
⚙️ Installation & Setup
Prerequisites
•	.NET 6 SDK
•	Visual Studio 2022 (with ASP.NET and web development workload)
•	SQL Server or Azure Database
•	Azure Storage account (for blob/file operations)
Steps
1.	Clone the repository or unzip the provided project files.
2.	Open the solution in Visual Studio (ABCRetailers.sln).
3.	Update configuration in appsettings.json with database and Azure connection strings.
4.	Build and run the project with dotnet build and dotnet run.
5.	Access the application at https://localhost:5001.
📂 Project Structure
ABCRetailers.V2/
│
├── ABCRetailers/
│   ├── Controllers/        # Business logic & routing
│   ├── Models/             # Entity and ViewModels
│   ├── Services/           # Azure storage integration
│   ├── Views/              # Razor views for UI
│   ├── appsettings.json    # Configuration
│   ├── Program.cs          # App entry point
│   └── README.md           # Documentation


