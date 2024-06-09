# ecommerce_webapp
This e-commerce website is built in Java using Spring Boot and utilizes Spring Security for user authentication. The wbsite encompasses all the functionalities of a shopping/e-commerce website.

## Project Overview

The application has two main interfaces: Admin and User.

### Admin Interface:

- **Single Admin Account:**
  - There is a single admin account for accessing the admin interface, with login credentials using email and password.

- **Admin and User Roles:**
  - The admin has both admin and user roles and can access all user functionalities.

- **Category and Product Management:**
  - The admin can manage categories and products, including adding new categories, updating existing ones, and managing products under each category.

- **Shop Page Access:**
  - The admin has the ability to view the shop page and filter products based on categories, even without being logged in.

- **Security Using Spring Security:**
  - The application uses Spring Security for secure authentication and authorization.

### User Interface:

- **User Authentication:**
  - Users can sign up and log in to the shopping site, including the option to log in with their Google account.
  
- **Product Interaction:**
  - Once logged in, users can view products, add them to the cart, and view the cart.

- **Cart Management:**
  - Users can remove items from the cart and proceed to the checkout page for payment.

- **Shop Page Access:**
  - Any user, whether logged in or not, can view the shop page and filter products based on categories.

- **Security Using Spring Security:**
  - The application uses Spring Security for secure authentication and authorization.

## Prerequisites

Before getting started, ensure you have the following tools installed:

- [IntelliJ IDEA](https://www.jetbrains.com/idea/downloads/)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/)

## Getting Started

1. Clone the repository.

   ```bash
   git clone https://github.com/kansal-tushar/ecommerce_webapp.git
2. Open the project in IntelliJ IDEA.
3. Build and run the application.
4. Access the application through the specified local URL (usually http://localhost:8080).

## Usage

### Admin:

- Log in using the admin credentials with email and password.
- Manage categories and products.
- Access all user functionalities.
  
### User:

- View the shop page and filter products based on categories.
- Sign up or log in to the shopping site or Log in with Google account.
- View products, add them to the cart, and view the cart.
- Remove items from the cart and proceed to the checkout page for payment.
