Collection of useful but not daily used commands

<b>Reverse engineer Entity framwork db context using existing database</b>
Scaffold-DbContext "Data Source=server;User Id=userid;Password=pws;Initial Catalog=dbname;MultipleActiveResultSets=True;Connection Timeout=60;Encrypt=false" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Data/Models/Test

Entity Framework Core CLI commands
https://www.entityframeworktutorial.net/efcore/cli-commands-for-ef-core-migration.aspx

EF CLi command using spcific environment
>dotnet ef migrations list -- --environment SGP_DEV
