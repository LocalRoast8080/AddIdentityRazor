# Welcome!

This is the starter project for [Secure a .NET web app with the ASP.NET Core Identity framework](https://docs.microsoft.com/learn/modules/secure-aspnet-core-identity/). A completed version of the project is located on the `solution` branch.

# Steps Taken
dotnet tool install dotnet-aspnet-codegenerator --version 6.0.2 --global



dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design --version 6.0.2
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore --version 6.0.3
dotnet add package Microsoft.AspNetCore.Identity.UI --version 6.0.3
dotnet add package Microsoft.EntityFrameworkCore.Design --version 6.0.3
dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 6.0.3

dotnet aspnet-codegenerator identity --useDefaultUI --dbContext RazorPagesPizzaAuth


update _layout with
<partial name="_LoginPartial" />

to add the login page on all pages