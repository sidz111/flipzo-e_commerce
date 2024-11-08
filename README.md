# Flipzo - E-commerce Platform

Flipzo is a Spring Boot-based e-commerce web application that enables users to browse products, add them to a cart, place orders, and manage profiles. The application supports essential e-commerce functionalities and integrates with Spring Security for user authentication. Built with a layered architecture, it offers an organized code structure that makes it easy to scale and maintain.

## Project Structure

- **Frontend**: Thymeleaf templates for dynamic HTML rendering with modern, user-friendly UI.
- **Backend**: Spring Boot-based RESTful services with Spring MVC, Spring Data JPA, and Spring Security.
- **Database**: MySQL for persistent data storage.

## Features

### 1. User Management
   - **Registration and Login**: Users can sign up with email verification and log in securely.
   - **Profile Management**: Users can update their profile, change passwords, and upload profile images.
   - **Authentication & Authorization**: Spring Security is implemented for secure authentication and role-based access.

### 2. Product Browsing and Categories
   - **Product Catalog**: Users can browse a wide range of products organized by categories.
   - **Category Management**: Admin can manage categories, ensuring that only active categories are shown to users.
   - **Product Details**: Each product page displays detailed information about the product, including images, description, and price.

### 3. Shopping Cart
   - **Add to Cart**: Users can add products to their cart.
   - **Update Cart Quantity**: Modify product quantities directly from the cart page.
   - **Cart Summary**: Displays a summary of items, including total price, and allows for easy adjustments.

### 4. Order Management
   - **Place Orders**: Users can place orders based on their cart contents, with real-time calculations of total costs.
   - **Order History**: Users can view their past orders with details.
   - **Order Status Tracking**: Admins can update order statuses (e.g., shipped, delivered), with users receiving notifications of changes.
   
### 5. Admin Dashboard (Optional)
   - **Order Management**: Admin can manage all orders, update statuses, and view order history.
   - **User Management**: Admin has access to manage user details and roles.

![Screenshot (270)](https://github.com/user-attachments/assets/f2999af2-725a-49e2-b943-63e8e105092e)
![Screenshot (271)](https://github.com/user-attachments/assets/1ce6195c-084f-4f70-835f-ef62e2e1414a)
![Screenshot (272)](https://github.com/user-attachments/assets/aa773523-fe1a-4385-994d-1813c2b36985)
![Screenshot (266)](https://github.com/user-attachments/assets/c59ddadc-80a8-4d83-bedc-0655d31129de)
![Screenshot (267)](https://github.com/user-attachments/assets/8ef68d26-b0f5-416d-8f19-f1cd78f27697)
![Screenshot (268)](https://github.com/user-attachments/assets/dd9343e6-550e-48ad-bd88-3de3c67db887)
![Screenshot (269)](https://github.com/user-attachments/assets/cb52aa41-fd45-4d8c-b744-40b212b027e0)


     

## Technologies Used

- **Backend**: Spring Boot, Spring MVC, Spring Security, Spring Data JPA
- **Frontend**: Thymeleaf, HTML, CSS, JavaScript
- **Database**: MySQL
- **Tools**: Maven, Git
- **Others**: Jakarta Servlet API, Java Mail API for sending notifications

