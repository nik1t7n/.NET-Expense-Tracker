# Expense Tracker Web Application Documentation

## Overview
The Expense Tracker web application is a robust financial management tool designed to help users track their expenses and income effectively. With features like a dynamic dashboard, transaction categorization, detailed reports, and customizable settings, users can gain valuable insights into their financial activities.

## Preview

**Main Interface**

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/0bf76809-f3f1-4c69-9af2-4ad97b6aa4ab)

**Widgets**

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/4adc3189-31ad-43b2-bed0-a41a0e4e9774)

You can perform all **CRUD** operations with Categories and Transactions:

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/64248134-c145-48fe-905b-930efaf33286)

---

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/2575c7e1-2522-4071-b0a2-0c32b8d4129d)

**Adding and Editing Interface**

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/e12d947a-59b1-4fca-826a-b8d544656f23)

---

![image](https://github.com/nik1t7n/.NET-Expense-Tracker/assets/90299797/bdbb84e0-8f77-4200-ba79-8e4fedb8d241)


## Project Structure
The project follows a structured architecture with the following key components:
- **Controllers**: Contains classes to handle HTTP requests and route them to the appropriate actions.
- **Views**: Houses the user interface components written in Razor syntax for dynamic rendering.
- **Models**: Defines the data models used to represent entities such as transactions, categories, and settings.
- **Data**: Includes the database context and migration files for managing the database schema.
- **wwwroot**: Stores static files like CSS, JavaScript, and images for the frontend.

## Architecture
The Expense Tracker application follows a Model-View-Controller (MVC) architectural pattern, where:
- **Model**: Represents the data entities and business logic.
- **View**: Renders the user interface for interacting with the application.
- **Controller**: Handles user input, processes requests, and updates the model and view accordingly.

## Code-First Approach
The project adopts a code-first approach to database development, where the database schema is defined using C# classes. Entity Framework Core is used to generate the corresponding database based on these classes, allowing for seamless integration of the application logic with the database structure.

## Migrations
Migrations in the Expense Tracker application are used to manage changes to the database schema over time. By creating and applying migrations, developers can update the database structure without losing existing data, ensuring smooth transitions between different versions of the application.

## Technologies Used
The Expense Tracker application is built using the following technologies and frameworks:
- **ASP.NET Core**: Backend framework for developing web applications.
- **Entity Framework Core**: ORM tool for database interactions and management.
- **Razor Pages**: Enables the creation of dynamic web pages with C#.
- **Bootstrap**: Front-end framework for responsive and visually appealing design.
- **Syncfusion**: Component library for data visualization and interactive UI elements.
- **jQuery**: JavaScript library for simplifying DOM manipulation and event handling.
- **HTML/CSS**: Used for structuring and styling the web application.
- **JavaScript**: Enhances interactivity and functionality on the client-side.
- **SQL Server**: Database management system for storing and retrieving transaction data.

## Support
For any technical assistance, feedback, or suggestions, please reach out to the project maintainers or open an issue on the GitHub repository.
