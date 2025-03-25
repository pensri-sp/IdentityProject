# IdentityProject
ASP.NET CORE Login and Registration using Identity. SQL SERVER Database.

- Create Project With ASP.NET CoreWeb App (MVC) C#
- Choose Framework .NET 8.0
- Choose Authen Type = Individual Accounts
- Check Configure for HTTPS
- Change DefaultConnection in appsettings.json to your DB
-  In Program.cs, add app.UseAuthentication(); under the app.UseRouting();
- In Data/ApplicationDbContext.cs Adda method, OnModelCreating(ModelBuilder modelBuilder)
- In Nuget Console, Use 
      >> Add-Migration IdentityDetails
      >> Update-Database
- You will see the new tables in the database.
- In NuGet Package Manager, Install Microsoft.VisualStudio.Web.CodeGeneration.Design Version 8.0.0
- Right click the Identity folder in the Solution Explorer, Add > New Scaffolded Item > Identity > Add
- Select the desired item or select override all files.
- In the Data context class, click + and select the latest one then click Add.
- You may run the website to show the example of using Identity.