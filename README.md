Step 1: Clone the repository 

Step 2: Open the project on Visual Studio

Step 3: Restore the NuGet packages
-   Enter 'dotnet restore' on Powershell (Package Manager Console)

Step 4: Add Migrations
- dotnet ef migrations add InitialCreate --context BookstoreContext
- dotnet ef database update --context BookstoreContext
- dotnet ef migrations add IdentityInitial --context ApplicationDbContext
- dotnet ef database update --context ApplicationDbContext

Step 5: Build the Project
- dotnet build

Step 6: Run the application

