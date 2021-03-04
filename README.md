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





