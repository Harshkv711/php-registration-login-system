# PHP Login System

This project implements a simple PHP-based login system with registration functionality. Users can register, log in, and log out securely.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- User registration with username and password
- Passwords stored securely using bcrypt hashing
- Login authentication
- Simple Bootstrap-based front-end for registration and login forms

## Prerequisites
- [XAMPP](https://www.apachefriends.org/index.html) or similar web server with PHP and MySQL

## Installation
1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/php-login-system.git
    ```

2. Create a MySQL database and update the `config.php` file with your database details:

    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'your-username');
    define('DB_PASSWORD', 'your-password');
    define('DB_NAME', 'your-database-name');
    ```

3. Import the SQL file `database.sql` into your MySQL database to create the necessary tables.

4. Start your web server (e.g., XAMPP).

5. Open the project in your web browser (e.g., `http://localhost/php-login-system`).

## Usage
1. Navigate to the registration page (`register.php`) and create a new account.

2. After registration, log in using your credentials on the login page (`login.php`).

3. Explore the simple PHP login system and customize it as needed for your project.

## Contributing
Contributions are welcome! Follow these steps to contribute to the project:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
