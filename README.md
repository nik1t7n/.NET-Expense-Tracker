# Expense Tracker Web Application

## Overview
This project is a web application designed for tracking expenses and managing categories. It provides functionalities to view total income, total expense, and category management.

## Technologies Used
- C#
- ASP.NET Core MVC
- Entity Framework Core
- HTML
- CSS
- JavaScript

## Features
1. **Category Management**
- Users can view and manage categories.
- Categories are populated dynamically using the `PopulateCategories` method.

2. **Dashboard**
- Summary widgets display total income and total expense.
- Users can view and manage expenses.

3. **Menu Navigation**
- The menu items are dynamically generated based on the user's role.
- Menu items include options for the dashboard and category management.

## Controllers
1. **CategoryController**
- Manages category-related actions such as viewing categories and details.

## Views
1. **Dashboard**
- Displays summary widgets for total income and total expense.

2. **Category Management**
- Allows users to view and manage categories.

## Models
1. **Category**
- Represents a category with properties like `CategoryId` and `Title`.

## Setup Instructions
1. Clone the repository to your local machine.
2. Open the project in Visual Studio or your preferred IDE.
3. Update the connection string in `appsettings.json` to point to your database.
4. Run the database migrations to create the necessary tables.
5. Build and run the application.

## Additional Notes
- Ensure that you have the necessary dependencies installed before running the application.
- Customize the styling and functionality as needed for your specific requirements.

## Contributors
- [Your Name]

## License
This project is licensed under [License Name]. See the LICENSE file for more details.

---

Feel free to customize this documentation template further based on additional features or specific details of your project.
