# InventoryManager

An inventory management system made in C# with .NET MAUI. Supports full CRUD using an SQLite database connection.

For college we had to create an inventory management system, with the coding language of our choice. I was interested in C#, and thus made the choice to create my first actual application. 
I started with small challenges in C# (https://mbogodigital.nl/csharp/). After completing most I ventured into .NET MAUI, as this was a good chance to experiment with something new. My mentor recommended .NET MAUI because of its cross-platform sustainability. 
The app has been made on a Macbook and thus is programmed to work on MacOS.

Things I learnt:

- C# concepts like classes, constructor etc.
- Learning .xaml for front-end. 
- Managing to connect a SQLite database, allowing for offline storage of databases.
- User login system with admin role.
     (Temporarily hardcoded to username "123456"
                               password: "admin")
                               
- Full CRUD operations based on user role.


App should run when using the command:

dotnet build -t:Run -f net9.0-maccatalyst

