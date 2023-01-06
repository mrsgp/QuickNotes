Collection of useful but not daily used commands

<b>Reverse engineer Entity framwork db context using existing database</b>
Scaffold-DbContext "Data Source=server;User Id=userid;Password=pws;Initial Catalog=dbname;MultipleActiveResultSets=True;Connection Timeout=60;Encrypt=false" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Data/Models/Test
