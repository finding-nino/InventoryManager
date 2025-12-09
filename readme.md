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


## Running on macOS

### Prerequisites
1. Install .NET 9 SDK 
2. Install Visual Studio Code with C# extensions
3. For MAUI, you might need to run: `dotnet workload install maui`

### First-Time Setup on macOS
Since macOS blocks unsigned apps, you need to:

**Option A: Run with Terminal (Recommended)**
```bash
# Navigate to project folder
cd InventoryManager
# Restore dependencies
dotnet restore

# Build and run (macOS will ask for permission)
dotnet build -t:Run -f net9.0-maccatalyst
# OR for Mac Desktop:
dotnet build -t:Run -f net9.0-macos
