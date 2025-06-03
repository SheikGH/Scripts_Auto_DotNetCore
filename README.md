# Scripts_Auto_DotNetCore
By single click create complete .Net Core with MVC template project with Customer GRUD operations in 5 minutes

Step-by-Step Guide to Automatically Create ASP.NET Core Project using Script
✅ Technologies Used
•	ASP.NET Core MVC
•	Entity Framework Core (Code-First)
•	SQL Server
•	Clean Architecture Layers:
o	Core
o	Application
o	Infrastructure
o	Web
________________________________________
📂 Step 1: Download Script File
•	Download the text file (sent via email).
•	Save it to your desired project directory location.

📄 Step 2: Convert to Executable Script
•	Open the saved text file.
•	Save it as:
Scripts_NetCore.txt ➜ Scripts_NetCore.dat
Ensure the file extension is changed from .txt to .bat.
 
🚀 Step 3: Run the Batch Script
•	Double-click Scripts_NetCore.bat.
•	A Windows PowerShell window will pop up.
•	The script will begin creating the project folder and scaffolding all architecture layers automatically.
•	You will see status messages as the script progresses.
  
🔐 Step 4: Enter Database Details
•	When prompted in PowerShell, enter your SQL Server connection details one by one:
o	Server Name
o	Database Name
o	User ID
o	Password
These details are used for the EF Core Code-First database setup.
 
🔧 Step 5: Build and Launch
•	After the setup, wait for the message:
Build Succeeded
•	The application will launch automatically in your default browser.
•	Example URL:
http://localhost:5139/
 
👨💻 Step 6: Explore the Application
•	The created application is a Customer Management System.
•	Features include:
o	View customer list
o	Add, Edit, Delete customers (CRUD operations)
•	You can now test the functionality of the system.

📌 Summary
Feature	Description
Script Execution	=> .bat file via PowerShell
Architecture	    => Clean: Core, App, Infra, Web
ORM	              => Entity Framework Core (Code First)
DB	              => SQL Server
Output	          => Fully working ASP.NET Core MVC Application
	



