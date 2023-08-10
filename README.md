# Sales Admin Dashboard
[![JavaScript](https://img.shields.io/badge/javascript-%2320232a.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PHP](https://img.shields.io/badge/php-%2320232a.svg?style=for-the-badge&logo=php&logoColor=%23777BB4)](https://www.php.net/)
[![Blade](https://img.shields.io/badge/blade-%2320232a.svg?style=for-the-badge&logo=laravel&logoColor=%23FF2D20)](https://laravel.com/docs/blade)
[![CSS](https://img.shields.io/badge/css-%2320232a.svg?style=for-the-badge&logo=css3&logoColor=%231572B6)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![SCSS](https://img.shields.io/badge/scss-%2320232a.svg?style=for-the-badge&logo=sass&logoColor=%23CC6699)](https://sass-lang.com/)

This project is a Sales Admin Dashboard built using the Laravel framework. The dashboard provides a user-friendly interface for managing sales-related data and generating reports. This README file provides an overview of the project, installation instructions, and other relevant information.

## Features

- **User Authentication**: The dashboard includes a robust user authentication system, allowing only registered users to access the admin functionalities.
- **Dashboard Overview**: The dashboard provides an overview of key sales metrics, such as total revenue, number of orders, and top-selling products.
- **Order Management**: Users can manage orders by viewing, editing, and deleting them. They can also search for specific orders based on various criteria.
- **Product Management**: The dashboard allows users to add, edit, and delete products. They can also categorize products and view detailed information about each product.
- **Reports**: The dashboard offers various reports, such as sales trends, top-selling products, and revenue by category. These reports provide valuable insights for decision-making.
- **User Management**: Administrators can manage user accounts by creating new users, updating user details, and assigning roles and permissions.
- **Settings**: The dashboard includes a settings section where administrators can configure system settings, such as currency, tax rates, and payment gateways.

## Prerequisites

To run this project, make sure you have the following prerequisites:

- PHP (7.4 or higher)
- Composer
- MySQL
- Web server (Apache or Nginx)

## Installation

Follow these steps to install and set up the Sales Admin Dashboard:

1. Clone the repository to your local machine or download the source code as a ZIP file.
2. Navigate to the project's root directory using the terminal or command prompt.
3. Run the following command to install the project dependencies:
   ```
   composer install
   ```
4. Create a new database in MySQL for the project.
5. Rename the `.env.example` file to `.env` and update the necessary database connection details in the `.env` file.
6. Generate an application key by running the following command:
   ```
   php artisan key:generate
   ```
7. Run the database migrations to create the necessary tables:
   ```
   php artisan migrate
   ```
8. (Optional) If you want to seed the database with sample data, run the following command:
   ```
   php artisan db:seed
   ```
9. Start the development server by running the following command:
   ```
   php artisan serve
   ```
10. Access the dashboard by opening the specified URL in your web browser.

## Configuration

The project configuration can be modified in the `.env` file. Here are some important configuration options:

- `APP_URL`: The URL of the application.
- `DB_CONNECTION`: The database connection (e.g., mysql).
- `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`: Database connection details.
- `MAIL_MAILER`, `MAIL_HOST`, `MAIL_PORT`, `MAIL_USERNAME`, `MAIL_PASSWORD`, `MAIL_ENCRYPTION`, `MAIL_FROM_ADDRESS`: Email configuration for notifications.
- `CURRENCY_SYMBOL`: The currency symbol to be used in the dashboard.

Make sure to run `php artisan config:cache` after modifying the `.env` file for the changes to take effect.

## License

This project is open source and released under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please submit an issue or create a pull request.

## Support

If you encounter any problems or have any questions, please contact the project maintainer at [email protected]

## Acknowledgements

We would like to thank the Laravel community for their excellent framework and documentation, which which greatly facilitated the development of this project.

## Screenshot
<img src="https://github.com/IPH-Technologies-Pvt-Ltd/Sales-Admin-Dashboard-Laravel/assets/94104772/46e4602d-89a3-4ed5-870b-00647a250bda" 
     width="800" 
     height="450"/>

