# Registration Form Laravel

This repository contains a registration form application implemented using the Laravel framework. The form allows users to register by providing their personal information, such as name, email address, and password. The application leverages the features and functionality provided by Laravel to handle user registration and authentication.

## Features

- User registration: Users can sign up by providing their name, email address, and password.
- User authentication: Registered users can log in using their email address and password.
- Input validation: The application validates user inputs to ensure the correctness and completeness of the provided information.
- Error handling: User-friendly error messages are displayed for invalid or missing inputs.
- Database integration: User information is stored in a database for future reference and authentication.

## Prerequisites

Before running the registration form application, make sure you have the following prerequisites installed:

- [PHP](https://www.php.net/manual/en/install.php)
- [Composer](https://getcomposer.org/download/)
- [Laravel](https://laravel.com/docs/8.x/installation)

## Installation

To run the registration form application locally, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/AsmaaOmarr/Registration-Form-Laravel.git
   ```

2. Navigate to the project directory:
   ```
   cd Registration-Form-Laravel
   ```

3. Install the project dependencies using Composer:
   ```
   composer install
   ```

4. Create a copy of the `.env.example` file and rename it to `.env`:
   ```
   cp .env.example .env
   ```

5. Generate an application key:
   ```
   php artisan key:generate
   ```

6. Set up your database credentials in the `.env` file.

7. Run the database migrations to create the necessary tables:
   ```
   php artisan migrate
   ```

8. Start the development server:
   ```
   php artisan serve
   ```

9. Access the application in your browser at `http://localhost:8000`.

## Usage

1. Visit the registration page in your browser.

2. Fill in the required fields in the registration form, including name, email address, and password.

3. Ensure that the input provided is valid and complete.

4. Click the "Register" button to create a new user account.

## Acknowledgments

- The registration form application is built using Laravel, an excellent PHP framework for web development.
