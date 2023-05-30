💻 Project
REST API for school management.

The project was developed as the final project of the first module of the Professionalizing course in FullStack development.

:gear: Technologies
List of technologies used in the project:

C#
ASP.NET Core
EntityFrameworkCore
Fluent API
Fluent Validation
SQLite
MVC Pattern

:arrow_forward: Running the project

Clone the repository:
$ git clone https://github.com/mariacarolinaboabaid/REST_API
$ cd API-REST

Change the path at the Connection String in the appsettings.Development.json file to the path of your local folder:
 "ConnectionStrings": {
    "LabSchoolContext" : "Data Source=/yourlocalpath/[alexandre]labschoolbd.db;"
  } 
Install the following packages by running the commands:
 dotnet add package Microsoft.EntityFrameworkCore  

 dotnet add package Microsoft.EntityFrameworkCore.Tools 
 
 dotnet add package Microsoft.EntityFrameworkCore.Design

 dotnet add package Microsoft.EntityFrameworkCore.Sqlite
Run the command:
 dotnet run
The API will be available at http://localhost:5127/swagger.
