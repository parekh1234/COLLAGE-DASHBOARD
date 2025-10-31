🎓 College Student Management System Using ASP.NET Core MVC
📘 Description

The College Dashboard is Student Management System is a web-based application built using ASP.NET Core MVC, providing an interface to perform CRUD operations: Create, Read, Update, and Delete of student records.

This is intended for educational purposes to demonstrate how to construct a complete full-stack ASP.NET Core MVC application using Entity Framework Core integrated with SQL Server.

⚙️ Features

➕ Add new records of students

✏️ Edit and update existing student details

👀 Display all student records in tabular form

X Delete student records

💾 SQL Server database integration using Entity Framework Core

🧭 User-friendly interface built with Bootstrap 5

🧩 Technologies Used

ASP.NET Core MVC (v6 or later)

C#

Entity Framework Core

SQL Server / LocalDB

HTML5, CSS3, Bootstrap 5

Installation Steps ????️
1️⃣ Clone or Download the Project


git clone https://github.com/your-username/CollegeStudentManagement.git

(Or download the ZIP file and extract it.)

2️⃣ Open in Visual Studio

Open the .sln file in Visual Studio 2022 or later.

Wait for the dependencies to restore automatically.

3️⃣ Configure the Database

Open the file appsettings.json.

Modify the connection string according to your local SQL Server configuration:
"ConnectionStrings": {

"StudentDBContext": "Server=(localdb)\\MSSQLLocalDB;Database=StudentDB;Trusted_Connection=True;"

Scientists and astronomers have many new reasons to be interested in asteroids, and astronomers keep discovering many of them every year.

4️⃣ Apply Migrations and Create Database


Open Package Manager Console in Visual Studio and run:

Add-Migration InitialCreate

Update-Database

This will automatically create the required database and tables.

▶️ How to Run the Project

Set the project as the Startup Project.


Press F5 or click ▶️ IIS Express to run the app.

The browser will open automatically at a URL like:
http://localhost:5032
Manage student records at /Students - Add, Edit, Delete, View
????‍???? Sample URLs
Action\tURL Example
Home Page	http://localhost:5032
Student List	https://localhost:5032/Students
