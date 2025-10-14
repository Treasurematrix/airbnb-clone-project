# 🏠 Airbnb Clone Project

## 📖 Overview
The **Airbnb Clone Project** is a full-stack web application that replicates the core functionalities of the Airbnb platform.  
It serves as a **hands-on learning experience** for building scalable, secure, and production-ready applications.  
This project focuses on backend development, database design, API creation, and CI/CD automation — helping learners gain practical experience with real-world systems and collaborative workflows.



## 🎯 Project Goals
- Develop a **robust backend system** using Django and MySQL.  
- Design a **relational database** that supports user accounts, bookings, listings, and reviews.  
- Build **secure APIs** that handle authentication, authorization, and data transactions.  
- Integrate **GraphQL** for efficient data querying and interaction.  
- Implement **CI/CD pipelines** using GitHub Actions for automated builds and deployments.  
- Containerize the application using **Docker** to ensure portability and consistency.  
- Promote **team collaboration** through structured repository management and documentation.  



## 🧠 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Backend Framework** | Django |
| **Database** | MySQL |
| **API Layer** | GraphQL / REST |
| **Version Control** | Git & GitHub |
| **Containerization** | Docker |
| **CI/CD** | GitHub Actions |
| **Security** | JWT / OAuth2, HTTPS |


## ⚡ Key Features
- 🧩 User authentication and profile management  
- 🏡 Property listing and booking system  
- 💬 User reviews and ratings  
- 🔒 API security and access control  
- 🔄 CI/CD integration with automated deployment pipelines  
- 📦 Docker-based development and deployment environment

## 👥 Team Roles

Building the **Airbnb Clone Project** involves several specialized roles that work collaboratively to ensure a smooth and efficient development process.  
Each role contributes to a specific aspect of the system’s architecture, functionality, and overall success.

### 🧑‍💻 Backend Developer
Responsible for designing and implementing the core server logic, APIs, and data processing workflows using **Django** and **GraphQL**.  
They ensure that the backend is secure, scalable, and well-integrated with the database and frontend layers.

### 🗃️ Database Administrator (DBA)
Designs, manages, and optimizes the **MySQL** database schema.  
They ensure data integrity, implement indexing for performance, and handle backup and recovery strategies to maintain consistent data availability.

### 🧠 System Architect
Defines the overall **software architecture** and ensures that all components — backend, APIs, CI/CD, and database — integrate seamlessly.  
They make decisions about system structure, scalability, and security strategies.

### ⚙️ DevOps Engineer
Oversees deployment automation and CI/CD pipeline setup using **Docker** and **GitHub Actions**.  
They manage version control workflows, environment configuration, and continuous delivery to ensure fast, reliable deployments.

### 🧪 QA Engineer
Tests application features, APIs, and workflows to ensure they meet functional and non-functional requirements.  
They identify bugs, document issues, and verify fixes before release, ensuring high-quality output.

### 🎨 UI/UX Designer
Designs user-friendly interfaces and smooth navigation flows that align with the **Airbnb-style** experience.  
They focus on aesthetics, responsiveness, and usability to deliver an intuitive customer journey.

### 📋 Project Manager / Scrum Master
Coordinates the development process, sets deadlines, and ensures effective team collaboration.  
They manage sprints, monitor progress, and keep communication clear across all roles to meet project goals on schedule.

🧩 *These roles work in synergy to replicate real-world development workflows — ensuring collaboration, scalability, and high-quality project delivery.*



## 🧠 Technology Stack

The **Airbnb Clone Project** leverages a modern and scalable technology stack designed for performance, security, and reliability.  
Each technology serves a specific function in achieving the project’s objectives.

| Technology | Purpose |
|-------------|----------|
| **Django** | A high-level Python web framework used for developing the backend, building RESTful and GraphQL APIs, and managing application logic efficiently. |
| **MySQL** | A relational database system used to store and manage structured data such as users, bookings, properties, and payments with integrity and scalability. |
| **GraphQL** | A query language for APIs that allows clients to request only the data they need, improving performance and flexibility compared to traditional REST APIs. |
| **Docker** | Used to containerize the application, ensuring consistent development, testing, and production environments across all team members. |
| **Git & GitHub** | Provide version control and collaborative code management, enabling multiple developers to contribute simultaneously with proper workflow tracking. |
| **GitHub Actions** | Powers the CI/CD pipeline, automating tasks such as testing, building, and deploying the application. |
| **Nginx** | Serves as a reverse proxy and load balancer, improving performance, scalability, and security in production deployments. |
| **JWT (JSON Web Tokens)** | Manages authentication and authorization securely, allowing users to log in and perform authorized actions without exposing credentials. |
| **HTML, CSS & JavaScript** | Form the foundational technologies for structuring, styling, and adding interactivity to the frontend of the web application. |

🧩 *Together, these technologies create a cohesive ecosystem that supports a secure, efficient, and scalable booking platform similar to Airbnb.*




## 🏡 Properties
**Fields:**  
- `id`: Unique property identifier  
- `title`: Property name or title  
- `description`: Details about the property  
- `price_per_night`: Cost per booking  
- `host_id`: References the user who owns the property  

**Relationship:**  
- A property belongs to a user (host).  
- A property can have multiple bookings and reviews.
  

  ## 🧱 Database Design

The database for the **Airbnb Clone Project** is designed using a relational model to ensure data integrity, scalability, and efficient queries.  
Below are the key entities and their core attributes:

### 🧍 Users
**Fields:**  
- `id`: Unique identifier for each user  
- `name`: User’s full name  
- `email`: User’s email address (unique)  
- `password_hash`: Securely stored password  
- `role`: Defines if the user is a host or guest  

**Relationship:**  
- A user can list multiple properties.  
- A user can make multiple bookings and reviews. 
