#URL Shortener - Full Stack Application
Overview
This is a full-stack URL shortener application built using Spring Boot and MySQL for the backend, and React with Tailwind CSS for the frontend. The application also uses JWT (JSON Web Tokens) for authentication and authorization. Additionally, Chart.js is integrated into the frontend for visualizing analytics data, such as the number of clicks on shortened URLs.

Features
Backend (Spring Boot)
URL Shortening: Generate short URLs from long URLs.

JWT Authentication: Secure endpoints using JWT for user authentication and authorization.

MySQL Database: Store user data, URLs, and analytics.

RESTful API: Expose endpoints for URL shortening, redirection, and analytics.

Analytics: Track the number of clicks on each shortened URL.

Frontend (React + Tailwind CSS)
User Authentication: Login and registration pages.

URL Shortening Form: Input long URLs and generate short URLs.

Dashboard: View and manage shortened URLs.

Analytics Visualization: Use Chart.js to display click analytics for each URL.

Responsive Design: Built with Tailwind CSS for a modern and responsive UI.

Additional Tools
Axios: For making HTTP requests from the frontend to the backend.

Chart.js: For visualizing analytics data in the form of charts.

Prerequisites
Before running the application, ensure you have the following installed:

Java Development Kit (JDK) 17 or higher

Node.js (v16 or higher)

MySQL Server

Maven (for backend)

npm (for frontend)

Setup Instructions
Backend (Spring Boot)
Clone the repository:

bash
Copy
https://github.com/Sachin0fficial/URL-Shortner-FullStack.git
cd url-shortener/backend
Configure MySQL:

Create a MySQL database named url_shortener.

Update the application.properties file in the src/main/resources directory with your MySQL credentials:

properties
Copy
spring.datasource.url=jdbc:mysql://localhost:3306/url_shortener
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update
Run the backend:

bash
Copy
mvn spring-boot:run
The backend will start on http://localhost:8080.

Frontend (React)
Navigate to the frontend directory:

bash
Copy
cd ../frontend
Install dependencies:

bash
Copy
npm install
Start the frontend:

bash
Copy
npm start
The frontend will start on http://localhost:3000.

Technologies Used
Backend
Spring Boot: Framework for building the backend.

MySQL: Database for storing user data and URLs.

JWT: For secure authentication and authorization.

Frontend
React: JavaScript library for building the user interface.

Tailwind CSS: Utility-first CSS framework for styling.

Axios: For making HTTP requests to the backend.

Chart.js: For visualizing analytics data.


