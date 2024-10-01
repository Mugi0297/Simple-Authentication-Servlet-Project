# Simple Authentication Project

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Version History](#version-history)
- [License](#license)

## Project Overview
This project is a simple web application for user authentication with features for user signup, login, and an admin panel to view user information. 
The application follows the Model-View-Presenter (MVP) design pattern, utilizing Java Servlets for backend processing and JSP for frontend presentation.

## Technologies Used
- **Frontend**: JSP (JavaServer Pages)
- **Backend**: Java Servlets
- **Database**: MySQL
- **Database Connectivity**: JDBC
- **Design Pattern**: MVP (Model-View-Presenter)

## Architecture
The application consists of three main components:
- **Model**: Manages data and business logic (User data and authentication logic).
- **View**: The JSP pages that provide the user interface.
- **Presenter**: The Servlet classes that handle user requests, process data, and return responses.

## Features
- User Signup: Allows new users to create an account.
- User Login: Authenticates existing users.
- Admin Panel: Admins can log in and view user information.
- Exception Handling: Manages runtime errors gracefully.
- Encapsulation: Data is secured within classes.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mugi0297/Simple-Authentication-Servlet-Project.git
   cd authentication-project

## Usage

- **User Signup**: Navigate to the signup page, enter your details, and create an account.
- **User Login**: Use the login page to authenticate.
- **Admin Login**: Use admin credentials to access the admin panel and view user information.

## Project Structure

**Simple-authentication-project/**  
- **src/**  
  - **com/**  
    - **sap/**  
      - **Bean/**  
        - `RegisterBean.java`  
      - **Interface/**  
        - `SInterface.java`
      - **Implementation/**
        - `SImplmentation.java`  
      - **Servlet/**  
        - `RegisterServlet.java`  
        - `LoginServlet.java`  
        - `AdminLoginServlet.java`  
      - **DatabaseConnection/**  
        - `DatabaseConnection.java`  
  - **web/**  
    - `index.jsp`  
    - `Register.jsp`  
    - `ViewData.jsp`  
    - `AdminLogin.jsp`
    - `Error.jsp`
    - `Success.jsp`
    - `Success1.jsp`  
- `web.xml`  
- `README.md`  

## Version History

- **v1.0**: Initial release with user signup, login, and admin panel features.

### Instructions for GitHub
1. Create a new repository on GitHub.
2. Upload the Markdown file along with your project code.
3. Adjust the `git clone` URL in the setup instructions to match your repository URL.



