# Simple PHP Login Form with Nginx, MySQL, and PHP

## Description
This project demonstrates the setup of a simple PHP login form hosted on an Nginx server, using a MySQL database for storing user credentials. The setup instructions include all necessary steps to install the required software, configure the server, and create the database and tables for the login functionality.

## Files Included
- **index.html**: This file contains the HTML form for user login, styled with basic CSS.
- **index.php**: This file handles the form submission, connects to the MySQL database, and verifies the user's credentials.
- **commands.txt**: This file provides detailed, step-by-step instructions to set up the server environment, including installation of Nginx, MySQL, and PHP, as well as configuration settings.

## Setup Instructions
Follow the steps outlined in `commands.txt` to set up your server environment.

1. **Install Nginx**: Instructions to install and configure Nginx, and ensure it is running correctly.
2. **Install MySQL**: Steps to install MySQL, secure the installation, and set up user and database.
3. **Install PHP**: Guide to install PHP and configure it to work with Nginx.
4. **Configure Nginx**: Detailed instructions to configure Nginx to serve PHP files.
5. **Test PHP Setup**: Steps to verify PHP is correctly set up and running with Nginx.
6. **Database Setup**: Commands to create the required database and table, and insert sample data.
7. **Update `index.php`**: Instructions to configure the PHP file to connect to the MySQL database.

## Usage
- Open `index.html` in a web browser to see the login form.
- Enter the username and password.
- The form submits to `index.php`, which processes the login and verifies credentials against the MySQL database.

## Project Goals
- Demonstrate a basic understanding of setting up a web server with Nginx, MySQL, and PHP.
- Provide a functional example of a PHP login system.
- Serve as a template for more complex web applications requiring user authentication.

## License
This project is open-source and free to use under the MIT License.

For detailed setup instructions, please refer to the `commands.txt` file included in this project.