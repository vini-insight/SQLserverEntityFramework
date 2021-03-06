# SQLserverEntityFramework
SQL server Entity Framework

Tutorial 1: Console application with SQL server and Entity Framework
https://www.learnentityframeworkcore.com/conventions/one-to-many-relationship#fully-defined-relationship


    dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 3.1.1

    dotnet add package Microsoft.EntityFrameworkCore.Tools --version 3.1.1


Now modify the .csproj file to include the following additional <ItemGroup> is added to the project. This may not have been added automatically:


    <ItemGroup>
        <DotNetCliToolReference Include="Microsoft.EntityFrameworkCore.Tools.DotNet" Version="2.0.1" />
    </ItemGroup>


EFcore:

    dotnet ef migrations add CreateDatabase

    dotnet ef database update


# TOTORIAIS PARA REVER:

https://www.youtube.com/watch?v=but7jqjopKM
https://balta.io/cursos

https://www.youtube.com/watch?v=ipbSwv09dDU (VINICIUS ANDRADE)
https://github.com/vsandrade/EFCoreCurso
https://github.com/vsandrade/React-CRUD-with-Asp.Net-Core-Web-API/tree/master/WebAPI/WebAPI

web api com EFcore + SQLserver FUNFANDO:
https://www.youtube.com/watch?v=HU-TZfGO-Do
https://github.com/JalpeshVadgama/aspnetcoreefwebapi
web api com EFcore + SQLserver FUNFANDO:

https://daniel-krzyczkowski.github.io/Entity-Framework-Core-with-ASP-.Net-Core-Web-API-jump-start/

PLAYLIST MVC:
https://www.youtube.com/watch?v=CLVJVA9cTuU&list=PL4WEkbdagHIQVbiTwos0E38VghMJA06OT
https://github.com/CuriousDrive/BookStores


Totorial 2: MVC application with SQL server and Entity Framework
https://www.learnentityframeworkcore.com/walkthroughs/aspnetcore-application



https://www.youtube.com/watch?v=7iCnCLQYxc8

https://www.youtube.com/watch?v=WWpauKF__fQ


DEPOIS DE MVP, PESQUISAR RAZO E BLAZOR 

FOR MYSQL LATER:
https://www.youtube.com/watch?v=eP2Plc258lo



