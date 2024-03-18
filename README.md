**Adeola University Project ReadMe**

## Overview
Welcome to the Adeola University project! This project is a simple web application designed to manage the data of a fictional university, Adeola University. It allows administrators to manage courses, instructors, and students, providing basic CRUD (Create, Read, Update, Delete) functionality for each entity.

## Features
1. **Course Management**: Add, view, edit, and delete courses.
2. **Instructor Management**: Add, view, edit, and delete instructors.
3. **Student Management**: Add, view, edit, and delete students.
4. **Department Management**: Add, view, edit, and delete departments.
5. **Enrollment Management**: Enroll students in courses and view enrollment details.
6. **Responsive Design**: The application is designed to be responsive, ensuring a consistent user experience across different devices.

## Technologies Used
- **ASP.NET Core MVC**: The project is built using ASP.NET Core MVC framework, providing a robust architecture for building web applications.
- **Entity Framework Core**: Entity Framework Core is used for data access, providing a convenient way to interact with the database.
- **Bootstrap**: Bootstrap is used for styling the UI, ensuring a clean and modern look.
- **C#**: The backend logic is written in C#, a powerful and versatile programming language.
- **HTML/CSS**: HTML and CSS are used for building the frontend interface, providing structure and styling to the web pages.

## Getting Started
To run the Adeola University project locally, follow these steps:
1. Clone the repository to your local machine.
2. Ensure you have the necessary prerequisites installed, including .NET Core SDK and Visual Studio (or Visual Studio Code).
3. Open the project in Visual Studio (or Visual Studio Code).
4. Restore the NuGet packages and build the solution.
5. Set up the database by running the Entity Framework Core migrations. Use the following commands in the Package Manager Console:
   ```
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```
6. Run the application using IIS Express or press `F5` in Visual Studio.
7. The application should launch in your default web browser. You can now start exploring and using the features.


## Acknowledgements
- This project is inspired by the Contoso University tutorial from Microsoft's ASP.NET documentation.
