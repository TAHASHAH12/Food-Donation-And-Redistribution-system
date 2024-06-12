# Food Donation and Redistribution System

This project is a web-based application designed to facilitate food donation and redistribution. Built using PHP and MySQL with XAMPP as the development environment, the system allows users to donate food, and organizations to request and redistribute it to those in need. 

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Introduction

The Food Donation and Redistribution System aims to reduce food waste and fight hunger by connecting individuals and organizations with excess food to those who need it. The platform allows users to create accounts, post food donations, and request food items. Administrators can manage users, donations, and requests to ensure a smooth operation.

## Features

- **User Authentication**: Secure user login and registration.
- **Food Donation Posting**: Users can post details about available food items for donation.
- **Food Requesting**: Organizations can browse and request food items posted by donors.
- **Admin Dashboard**: Administrators can manage users, donations, and requests.
- **Notification System**: Alerts and notifications for donors and requesters.
- **Search and Filter**: Advanced search and filtering options for donations and requests.
- **Responsive Design**: User-friendly interface accessible on various devices.

## Installation

To set up the project locally, follow these steps:

1. **Download and Install XAMPP**:
   - Download XAMPP from [apachefriends.org](https://www.apachefriends.org/index.html) and install it on your local machine.

2. **Clone the Repository**:
   - Clone this repository to your local machine using:
     ```sh
     git clone https://github.com/yourusername/food-donation-system.git
     ```

3. **Setup the Database**:
   - Start the Apache and MySQL modules in XAMPP.
   - Open phpMyAdmin by navigating to `http://localhost/phpmyadmin/`.
   - Create a new database named `food_donation`.
   - Import the `database.sql` file located in the `database` directory of this project to set up the necessary tables.

4. **Configure the Project**:
   - Open the project folder and navigate to the `config` directory.
   - Rename `config.example.php` to `config.php`.
   - Update the database configuration details in `config.php`:
     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'root');
     define('DB_PASSWORD', '');
     define('DB_NAME', 'food_donation');
     ```

5. **Run the Project**:
   - Move the project folder to the `htdocs` directory in your XAMPP installation directory.
   - Open a web browser and navigate to `http://localhost/food-donation-system`.

## Usage

- **Register** as a new user to start donating or requesting food.
- **Log in** to your account to access the dashboard.
- **Post Donations** by providing details about the food items.
- **Browse and Request** available donations if you represent an organization.
- **Manage Your Account** through the user profile settings.

## Contributing

Contributions are welcome! To contribute to this project, follow these steps:

1. **Fork the Repository** on GitHub.
2. **Clone Your Fork**:
   ```sh
   git clone https://github.com/yourusername/food-donation-system.git
   ```
3. **Create a Branch**:
   ```sh
   git checkout -b feature/your-feature-name
   ```
4. **Commit Your Changes**:
   ```sh
   git commit -m 'Add some feature'
   ```
5. **Push to the Branch**:
   ```sh
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request** on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any questions or feedback, please contact:

- **Taha Shah**
- **Email**: tahashah366@gmail.com
- **GitHub**: [TAHASHAH12](https://github.com/TAHASHAH12)

Thank you for using the Food Donation and Redistribution System! Together, we can make a difference.
