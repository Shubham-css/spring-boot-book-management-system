# 📚 Spring Boot Book Management System

A professional **Spring Boot CRUD application** for managing books using a clean layered architecture.  
This project demonstrates the implementation of:

- REST APIs
- Spring Boot
- Controller-Service-Repository Pattern
- CRUD Operations
- Gradle Build System
- Layered Architecture

---

# 🚀 Features

✅ Add New Books  
✅ View All Books  
✅ Update Existing Books  
✅ Delete Books  
✅ RESTful API Architecture  
✅ Layered Spring Boot Design  
✅ Clean Project Structure  
✅ Gradle-Based Project  
✅ Easy API Testing

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Java | Core Programming |
| Spring Boot | Backend Framework |
| Spring MVC | Web Layer |
| Gradle | Build Tool |
| REST API | Communication |
| IntelliJ IDEA | Development |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```bash
src
 └── main
      ├── java
      │    └── com.example.demo
      │          ├── controller
      │          │      ├── BookController.java
      │          │      └── HomeController.java
      │          │
      │          ├── service
      │          │      └── BookService.java
      │          │
      │          ├── repository
      │          │
      │          ├── entity
      │          │
      │          └── MyBookAppApplication.java
      │
      └── resources
             └── application.properties
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/spring-boot-book-management-system.git
```

---

## 2️⃣ Open Project

Open the project using:

- IntelliJ IDEA
- VS Code

---

## 3️⃣ Build Project

Using Gradle:

```bash
./gradlew build
```

---

## 4️⃣ Run Application

```bash
./gradlew bootRun
```

OR run:

```bash
MyBookAppApplication.java
```

---

# 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | / | Home Page |
| GET | /books | Get All Books |
| POST | /books | Add New Book |
| PUT | /books/{id} | Update Book |
| DELETE | /books/{id} | Delete Book |

---

# 🧠 Architecture Used

This project follows a **Layered Architecture**:

## Controller Layer
Handles incoming HTTP requests and API endpoints.

## Service Layer
Contains business logic and processing.

## Repository Layer
Handles database operations and data access.

## Entity Layer
Represents the application data model.

---

# 📸 Project Preview

```text
Spring Boot Application
├── Controllers
├── Services
├── Repository
├── Entity
└── REST APIs
```

---

# 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

- Spring Boot Basics
- REST API Development
- Dependency Injection
- MVC Architecture
- CRUD Operations
- Gradle Configuration
- Layered Backend Design
- GitHub Project Management

---

# 🔥 Future Enhancements

- Database Integration (MySQL/PostgreSQL)
- Spring Data JPA
- Hibernate ORM
- Swagger API Documentation
- JWT Authentication
- Frontend Integration
- Docker Deployment
- Cloud Deployment

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Shubham**

Developed as a Spring Boot backend practice project for learning REST APIs and layered application architecture.

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the repository  
📢 Share with others

---