﻿# TodoApi
TodoApi is a web service created in .NET Core 2.1, PostgreSQL 10 &amp; Visual Studio Code on macOS

### Set up

1. Get the [Mac C# SDK](https://www.microsoft.com/net/download)
    (verify this by executing dotnet on your terminal - you should see output text)
<<<<<<< HEAD
2. Get [Visual Studio](https://visualstudio.microsoft.com/)
3. Clone this repo with: 
    $ git clone git@github.com:lindseydew/TodoApi.git
4. Open folder TodoApi in your Visual Studio editor, and double click on `TodoApi.csproj`
5. Install postgres (if you haven't got it already) with 
    $brew install postgresql and start with
    $brew services start postgresql
6. Run the sql migration scripts with:
=======
2. Get [VSCode](https://code.visualstudio.com/)
3. Open VSCode and install the following extensions
  * C#
  * C# Extensions
  * C# XML Documentation Comments
  * Code Runner
4. Clone this repo with:
   ```$ git clone git@github.com:lindseydew/TodoApi.git```
5. Open folder TodoApi in your VSCode editor
6. Install postgres (if you haven't got it already) with 
       - ```$brew install postgresql``` and start with
       - ```$brew services start postgresql```
7. Run the sql migration scripts with:
>>>>>>> ff175a4d9d4711285b1be2a19a8510d7d77253a4
    dotnet ef database update    
7. Run your server with: 
   dotnet watch run
    (verify this by hitting https://localhost:5001/api/todo)


