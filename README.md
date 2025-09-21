# 🛍️ E-Commerce Project (Spring Boot)

A simple **E-Commerce web application** built with **Spring Boot**, **Hibernate**, and **MySQL**.  
This project demonstrates the basics of building a web application with user registration, product management, and admin control.

---

## ✨ Features
- 🗂️ **Product Management** – Add, edit, and delete products.  
- 👤 **User Registration & Login** – Users can sign up, log in, and browse products.  
- 🛒 **Cart Logic (Work in Progress)** – Add products to cart (coming soon).  
- 🔄 **Hibernate Configuration** – Database tables are created automatically.  
- ⚡ Works in both **IntelliJ IDEA** and **Eclipse**.  

---

## 🚀 Getting Started

Follow these steps to run the project on your local machine:

### 1️⃣ Prerequisites
- **Java 11+**
- **MySQL** or **MariaDB**
- **Maven** (comes with IntelliJ IDEA)

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/jaygajera17/E-commerce-project-springBoot.git
cd E-commerce-project-springBoot/JtProject
```

### 3️⃣ Configure Database
Open `src/main/resources/application.properties` and update:
```properties
db.url=jdbc:mysql://localhost:3306/ecommjava?createDatabaseIfNotExist=true
db.username=your_username
db.password=your_password
```

### 4️⃣ Run the Project
Run the `main` method in **JtSpringProjectApplication.java**  
OR use:
```bash
mvn spring-boot:run
```

### 5️⃣ Open in Browser
Visit: [http://localhost:8080/](http://localhost:8080/)

---

## 🔑 Default Logins
After running the [`basedata.sql`](./JtProject/basedata.sql) script, you can log in with:

| Role   | Username | Password |
|--------|----------|---------|
| Admin  | admin    | 123     |
| User   | lisa     | 765     |

---

## 📂 Project Structure
```
src/main/java/com/example/ecommerce
│
├─ controller   → Handles web requests
├─ service      → Business logic (reusable services)
├─ dao          → Database interaction
├─ model        → Entity classes
└─ webapp/views → JSP pages (frontend)
```

---

## 🖼️ Screenshots
| Login Page | Product Dashboard |
|------------|--------------------|
| ![login](https://github.com/jaygajera17/E-commerce-project-springBoot/assets/81226571/02a04d3c-1fc9-418c-b231-639f6525d07e) | ![dashboard](https://github.com/jaygajera17/E-commerce-project-springBoot/assets/81226571/24c4451b-43a6-4c23-a78a-786eab4303b0) |

---

## 🧩 Tech Stack
- **Backend:** Spring Boot, Hibernate, Spring MVC  
- **Database:** MySQL / MariaDB  
- **Frontend:** JSP, HTML, CSS  
- **Build Tool:** Maven  
