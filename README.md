# ST10465232 POE Part 2

<img width="1909" height="990" alt="image" src="https://github.com/user-attachments/assets/72e7fc63-fea8-43c9-8d97-1fce9d7613aa" />

# Raceway – Event Management System

## 1. Introduction

Raceway is a web-based event management system developed using ASP.NET Core MVC. It is designed to help manage sporting events such as road races, marathons, walking events and cycling competitions.

The system provides a central place to manage event information, categories, participant enrolments and results. It uses a database to store information and ASP.NET Core Identity for user authentication.

## 2. Technologies Used

- C#
- ASP.NET Core MVC
- .NET 8
- Entity Framework Core
- Microsoft SQL Server
- ASP.NET Core Identity
- HTML, CSS and JavaScript
- Visual Studio 2022
- GitHub

## 3. Main Features

- **User authentication:** Supports user registration and login.
- **Event management:** Manages sporting event information.
- **Category management:** Organises events into different categories.
- **Participant enrolments:** Stores participant registration information.
- **Results management:** Supports recording event results.
- **Database integration:** Stores application data using SQL Server.

The availability of each feature depends on the current implementation of the application.

## 4. Project Structure

| Folder or file | Purpose |
|---|---|
| `Areas/Identity` | Identity and account pages |
| `Controllers` | Handles application requests |
| `Data` | Database context and configuration |
| `Migrations` | Database schema changes |
| `Models` | Application data models |
| `Views` | User interface pages |
| `wwwroot` | CSS, JavaScript and other static files |
| `Program.cs` | Application configuration |
| `appsettings.json` | Application settings and database connection |
| `RaceDayy.csproj` | Project configuration |
| `RaceDayy.sln` | Visual Studio solution |

## 5. Database

Raceway uses Microsoft SQL Server to store application data. Entity Framework Core manages communication between the application and the database.

The main entities include:

- ApplicationUser
- Event
- Category
- Enrolment
- Result

Entity Framework Core migrations are used to manage database changes.

## 6. How to Run the Project

1. Install Visual Studio 2022 and the .NET 8 SDK.
2. Install or configure Microsoft SQL Server.
3. Open `RaceDayy.sln` in Visual Studio.
4. Configure the database connection string in `appsettings.json`.
5. Restore the NuGet packages.
6. Build the solution and fix any errors.
7. Apply pending database migrations if required.
8. Press `F5` to run the application.

## 7. Conclusion

Raceway is designed to make sporting event management easier by bringing event information, categories, participant enrolments and results into one application. The project uses ASP.NET Core MVC and SQL Server to provide a foundation for managing event-related information.

