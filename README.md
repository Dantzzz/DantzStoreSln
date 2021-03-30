# DantzStoreSln
This is a build of a demo MVC app from Adam Freeman's ASP.NET Core 3 Textbook. This is for the purpose of demonstration.

## link
This is an exercise in Adam Freeman's Pro ASP.NET Core 3, Eighth Edition. For more information, follow this link:
[https://www.apress.com/gp/book/9781484254394.](https://www.apress.com/gp/book/9781484254394.)

## Build PowerShell Script

    dotnet new globaljson --sdk-version 5.0.201 --output DansStoreSln/OutdoorProducts
    dotnet new web --no-https --output DansStoreSln/OutdoorProducts --framework net5.0
    dotnet new sln -o DansStoreSln
    dotnet sln DansStoreSln add DansStoreSln/OutdoorProducts
    dotnet new xunit -o DansStoreSln/OutdoorProducts.Tests --framework net5.0
    dotnet sln DansStoreSln add DansStoreSln/OutdoorProducts.Tests 
    dotnet add DansStoreSln/OutdoorProducts.Tests reference DansStoreSln/OutdoorProducts
    
## Step 2
Project running after inital configuration... <br>
![img](images/step1_pg128.JPG)

## Step 3
*What is Entity Framework?* <br>
It is Microsoft's Object-to-Relational Mapping (ORM) framework. 
It is used to link databases and web applications together. 
<br>
*What is a Connection String?* <br>
A connection string points your code toward a database to migrate to.
It is comprised of all the applicable information to connect to and access the database.
<br>
*What is a Database Context?* <br>
While connection strings allow for connection, Database Context is essentially a specific reference <br>
to the database that allows integration of the program Models to the database tables.
<br>
*What is a Model Repository?*<br>

<br>
*Migration vs Scaffolding?* <br>

<br>
*Seeding the database*:<br>

## Step 4
Added page links, tests and styling <br>
![img](images/Fig7-5Pg142.JPG)
![img](images/Fig7-7Pg149.JPG)
![img](images/Fig7-9Pg154.JPG)
    
