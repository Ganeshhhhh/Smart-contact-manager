# Smart Contact Manager

## Overview
**Smart Contact Manager** is a powerful web application designed to manage contacts effectively. It allows users to securely store and manage contact information, including names, emails, images, and descriptions. The application also provides features for user authentication, password recovery via OTP, and more.

## Features
- **Contact Management**: Add, update, and delete contacts with details like name, email, image, and description.
- **User Authentication**: Secure sign-up and login functionality with validation.
- **Password Recovery**: Reset passwords with an OTP sent to the registered email address.
- **Validation**: All forms are validated to ensure proper data input.
- **Responsive Design**: Intuitive and user-friendly interface built using Thymeleaf, CSS, and JavaScript.

## Technology Stack
- **Backend**: Spring Boot, Hibernate
- **Frontend**: Spring MVC, Thymeleaf, CSS, JavaScript
- **Database**: MySQL

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Ganeshhhhh/smart-contact-manager.git
    cd smart_contact_manager
    ```

2. **Configure the database**:
   Update the `application.properties` file with your MySQL database credentials:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/contact_manager
    spring.datasource.username=your_username
    spring.datasource.password=your_password
    spring.jpa.hibernate.ddl-auto=update
    ```

3. **Run the application**:
    - Build and run the project using your favorite IDE (e.g., IntelliJ IDEA, Eclipse) or from the terminal.

## Usage

- **Sign Up**: Register for a new user account.
- **Login**: Log in with your credentials to access your account.
- **Add Contact**: Navigate to the "Add Contact" section to create a new contact with details like name, email, and image.
- **Update/Delete Contact**: Edit or delete contacts as needed.
- **Password Recovery**: Use the "Forgot Password" feature to reset your password via OTP.

## Contributing
Contributions are welcome to enhance **Smart Contact Manager**. To contribute:
- Fork the repository.
- Create a feature branch.
- Submit a pull request with a detailed explanation of the changes.

## Screenshots

