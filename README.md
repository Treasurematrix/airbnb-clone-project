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
