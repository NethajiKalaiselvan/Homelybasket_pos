# Homely Basket

A web-based business management system that helps you manage products, customers, billing, and generate reports for your business.

## Features

- User Authentication System
- Dashboard Overview
- Product Management
- Customer Management
- Billing and Invoice Generation
- Reports Generation
- Settings Configuration

## Prerequisites

- PHP 7.0 or higher
- MySQL/MariaDB
- XAMPP/WAMP/LAMP server
- Web Browser (Chrome, Firefox, Safari, etc.)

## Installation

1. Clone this repository to your XAMPP's htdocs folder:
   ```
   C:\xampp\htdocs\homelybasket
   ```

2. Import the database:
   - Start your XAMPP Apache and MySQL services
   - Navigate to phpMyAdmin
   - Create a new database
   - Use the `setup_database.php` script to set up your database structure

3. Configure your database connection:
   - Open `config/database.php`
   - Update the database credentials if necessary

## Usage

1. Start your XAMPP Apache and MySQL services
2. Open your web browser and navigate to:
   ```
   http://localhost/homelybasket
   ```
3. Log in using your credentials
4. You can now access all features through the navigation menu:
   - Manage your products
   - Add and manage customers
   - Create invoices
   - Generate reports
   - Configure system settings

## File Structure

```
├── assets/
│   └── css/
│       └── style.css
├── config/
│   └── database.php
├── includes/
│   ├── functions.php
│   ├── navbar.php
│   └── session.php
├── billing.php
├── customers.php
├── dashboard.php
├── index.php
├── invoice.php
├── login.php
├── logout.php
├── products.php
├── reports.php
├── settings.php
└── setup_database.php
```

## Security

- User authentication system implemented
- Session management for secure access
- Database connection credentials protected

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository or contact the system administrator.
