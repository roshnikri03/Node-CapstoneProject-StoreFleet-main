# StoreFleet Project Readme

Welcome to the StoreFleet project! This document serves as a guide to understanding the project's structure, features, and how to contribute to its development.

## Project Overview

StoreFleet is an instant product delivery service aimed at providing fast and efficient delivery for various products, including food, groceries, smartphones, and more. The project focuses on enhancing user experience, ensuring security, and improving functionality across different aspects of the platform.

## Features

### 1. Code Analysis and Debugging

Thoroughly analyze the project's source code, identify existing issues and errors, and debug them to ensure stability and reliability.

### 2. Implement Welcome E-mail Feature with Nodemailer

Automatically send welcome e-mails to users upon successful registration, including the company's brand logo and HTML content for a warm welcome.

### 3. Handle Duplicate Key Error in MongoDB

Ensure each user's email address is unique, and handle duplicate key errors gracefully by providing clear error messages.

### 4. Use Mongoose Middleware for Password Hashing

Automatically hash user passwords using bcrypt via Mongoose Middleware before saving user documents to enhance security.

### 5. Implement Forget Password and Reset Feature

Allow users to reset their passwords using a token-based approach with a time limit, utilizing Nodemailer to send reset tokens to the user's email address.

### 6. Fix Bug in Securing Admin Routes

Ensure that only users with 'admin' roles can access secured routes, fixing an existing issue in the authentication middleware.

### 7. Implement Route and Controller for Updating User Roles by Admin

Create routes and controllers to enable administrators to update the roles of other users easily.

### 8. Execute Product Filtering, Search Capabilities, and Pagination

Implement search, filtration, and pagination functionalities for efficient data retrieval and enhanced user experience, especially within the product listing.

### 9. Fix Review Delete Feature and Rating Update

Restrict users to deleting only their reviews and ensure accurate updating of product ratings when reviews are deleted.

### 10. Implement Controller and Repository for Placing Orders

Create controllers and repository functions to handle the order placement process seamlessly.

## Evaluation Criteria

The project will be evaluated based on various criteria, including code analysis and debugging, implementation of specific features, handling of errors, security enhancements, and overall functionality improvements.

## Contribution Guidelines

Contributions to the StoreFleet project are welcome! Here are some guidelines for contributing:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and ensure they adhere to the project's coding standards.
4. Test your changes thoroughly to avoid introducing new issues.
5. Commit your changes with clear and descriptive messages.
6. Push your changes to your fork and submit a pull request to the main repository.
7. Ensure your pull request includes relevant information about the changes made and why they are necessary.

## Conclusion

StoreFleet aims to provide a seamless and efficient delivery experience for users across various product categories. With your contributions and improvements, we can continue to enhance the platform's functionality, security, and user satisfaction.

Thank you for your interest in the StoreFleet project!
