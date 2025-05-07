# CMS with AdminLTE

A simple Content Management System built with PHP and AdminLTE template.

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Composer (for dependencies)

## Installation

1. Clone this repository to your web server directory
2. Create a new MySQL database named `cms_db`
3. Import the `database.sql` file to create the necessary tables
4. Configure your database connection in `config/database.php`
5. Download AdminLTE template files:
   - Download AdminLTE from https://adminlte.io/
   - Extract the contents to your project directory
   - Make sure the following directories are present:
     - `dist/`
     - `plugins/`

## Default Login

- Username: admin
- Password: admin123

## Features

- User authentication
- Dashboard with statistics
- Pages management
- Posts management
- User management
- Responsive design with AdminLTE template

## Security

Please change the default admin password after first login.

## License

This project is open-sourced software licensed under the MIT license.