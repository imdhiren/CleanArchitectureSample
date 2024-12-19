# CleanArchitectureSample

## Description
A sample ASP.NET MVC project demonstrating Clean Architecture principles. This project includes core entities, use cases, repositories, and controllers/views in a single project setup.

## Technologies Used
- ASP.NET MVC 4
- Entity Framework 6
- SQL Server (or any other database)


3. **Set up the environment**:
- Ensure .NET Framework 4.5.2 or later is installed.
- Configure your database connection in `Web.config`:
  ```xml
  <connectionStrings>
    <add name="DefaultConnection" connectionString="YourConnectionString" providerName="System.Data.SqlClient" />
  </connectionStrings>
  ```

4. **Run the application**:
- Open the project in Visual Studio and set it as the startup project.
- Press `F5` to run the application.

## Usage
- Access the application at `http://localhost:port/`.
- Navigate through the Controllers (`Products`, `Categories`) to manage items.
- The Views provide the front-end UI for CRUD operations.

## Contributing
Feel free to fork the repository and submit pull requests. Any contributions are welcome!
