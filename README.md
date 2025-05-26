This project is a full-stack food delivery web application named Xwiggy. It is built using Angular 8 for the frontend and Spring Boot for the backend. The backend follows the MVC (Model-View-Controller) design pattern and uses JPA (Java Persistence API) for interacting with a MySQL database.The application allows users to register, browse restaurants and menus, place orders, and track their deliveries. It also includes an admin panel for managing restaurants, menu items, and orders. The project demonstrates a complete integration between a modern frontend framework and a robust Java backend with database connectivity.

🚀 How to Run the Project
1. Prerequisites
Node.js and Angular CLI installed
Java JDK 8 or above
MySQL Server
Maven installed

2. Set Up MySQL Database
Create a database in MySQL (e.g., xwiggy_db)
Configure the database connection in application.properties (found in the Spring Boot project):

   spring.datasource.url=jdbc:mysql://localhost:3306/xwiggy_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password

3. Run the Backend (Spring Boot)
     1. Open the Spring Boot project in your IDE (e.g., IntelliJ, Eclipse)
     2.Build the project using Maven
     3.Run the application (e.g., XwiggyApplication.java)
     4.Spring Boot will start at http://localhost:8080
4. Run the Frontend (Angular 8)
    1.Navigate to the Angular project directory in the terminal
    2.Install dependencies:
     npm install
    3.Start the Angular server:
     ng serve
   4.Visit the frontend in your browser at http://localhost:4200
   
✅ Now you can:
Sign up or log in as a user
Browse restaurants and menus
Place and track orders
Manage data through the admin interface
