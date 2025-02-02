# User Management API with Spring Boot

This is a **Spring Boot** application that provides a **REST API** for managing users. It integrates **PostgreSQL** as the database and uses **Spring Data JPA** for seamless database interactions.

## 🚀 Features
- CRUD operations for user management.
- PostgreSQL database integration.
- Spring Boot with Spring Data JPA.
- Lombok for reducing boilerplate code.
- Logback for efficient logging.

## 📦 Installation
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Configure the database** in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/yourdbname
   spring.datasource.username=yourusername
   spring.datasource.password=yourpassword
   ```

3. **Build and run the project**:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

## 📖 API Endpoints
| Method | Endpoint     | Description              |
|--------|-------------|--------------------------|
| GET    | `/users`    | Fetch all users          |
| POST   | `/users`    | Create a new user        |
| GET    | `/users/{id}` | Get user by ID         |
| PUT    | `/users/{id}` | Update user by ID      |
| DELETE | `/users/{id}` | Delete user by ID      |

## 🛠 Technologies Used
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL**
- **Lombok**
- **Maven**
- **Logback**

## 👨‍💻 Contributing
Pull requests are welcome! Open an issue for discussions.

## 📜 License
This project is licensed under the **MIT License**.
