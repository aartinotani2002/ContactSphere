# 📇 ContactSphere

ContactSphere is a **Smart Contact Management System** built using Spring Boot.
It allows users to securely manage their contacts with features like authentication, CRUD operations, search, pagination, and cloud image upload.

---

## 🚀 Features

* 🔐 User Authentication (Login/Signup)
* 🌐 OAuth Login (Google & GitHub)
* 📊 Dashboard for managing contacts
* ➕ Add, Update, Delete Contacts
* 🔍 Search Contacts with Pagination
* 🖼️ Upload Contact Images (Cloud Storage)
* ✅ Form Validation using Bean Validation
* 🎨 Responsive UI with Tailwind CSS
* 🌙 Dark/Light Theme Toggle
* ⚡ AJAX-based interactions
* 🔒 Secure routes using Spring Security

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Frontend:** Thymeleaf, Tailwind CSS
* **Database:** MySQL
* **Security:** Spring Security, OAuth2
* **Build Tool:** Maven

---

## 📂 Project Structure

* `src/main/java` → Controllers, Services, Models
* `src/main/resources` → Templates, Static files, Config
* `pom.xml` → Dependencies and build config

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aartinotani2002/ContactSphere.git
cd ContactSphere
```

### 2. Configure Database

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 3. Run the application

```bash
mvn spring-boot:run
```

### 4. Open in browser

```
http://localhost:8080
```

---
## 📚 Learning Highlights

This project covers:

* Spring Boot Project Setup
* MVC Architecture
* Thymeleaf Templating & Fragments
* Tailwind CSS Integration
* Spring Security Configuration
* OAuth Login (Google & GitHub)
* Form Handling & Validation
* Pagination & Search Implementation
* AJAX & Dynamic UI Updates
* File Upload & Cloud Integration

---

## 📌 Author

**Aarti Notani**
GitHub: https://github.com/aartinotani2002
