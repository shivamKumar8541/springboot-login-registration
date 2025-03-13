# springboot-login-registration


A **User Registration & Login System** built with **Spring Boot, Spring-Data JPA, and Thymeleaf**.

## 📌 Features
- ✅ **User Registration** with Email & Password  
- ✅ **User Login** Authentication  
- ✅ **Database Integration** using MySQL/PostgreSQL  
- ✅ **Thymeleaf-Based UI**  

## 🚀 Technologies Used
- **Java 17+**
- **Spring Boot 3+**
- **Spring Data JPA**
- **Thymeleaf**
- **MySQL / PostgreSQL/Oracle /**
- **Maven**

## ⚙️ Setup & Installation

2️⃣ Configure Database
Open application.properties or application.yml 
Update database credentials:
spring.application.name=Web_mvc_01
spring.datasource.driver-class-name=oracle.jdbc.driver.OracleDriver
spring.datasource.url=jdbc:oracle:thin:@localhost:1521:ORCLV
spring.datasource.username=system
spring.datasource.password=shivam
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

User-Authentication-System/   # Root Directory (Repository Name)
│── src/                      # Source Code
│   ├── main/
│   │   ├── java/com/shivam/  # Java Package
│   │   │   ├── controller/   # Controllers (e.g., MyController.java)
│   │   │   ├── entity/       # Entity Classes (e.g., User.java)
│   │   │   ├── repository/   # Repositories (e.g., UserRepository.java)
│   │   │   ├── service/      # Service Layer (e.g., UserService.java, UserServiceImpl.java)
│   │   │   ├── Application.java  # Main Spring Boot Application
│   │   ├── resources/        # Resources Folder
│   │   │   ├── static/       # Static Files (CSS, JS, Images)
│   │   │   ├── templates/    # Thymeleaf Templates (HTML Pages)
│   │   │   ├── application.properties  # Spring Boot Configurations
│── pom.xml                   # Maven Configuration (for dependencies)
│── README.md                 # Project Documentation
│── .gitignore                # Git Ignore File
│── mvnw, mvnw.cmd            # Maven Wrapper Scripts
│── target/                    # Compiled Output (Generated after build)


Open browser and visit: http://localhost:8080/
📄 API Endpoints
Method	Endpoint	Description
GET	/	Home Page
GET	/regPage	User Registration Form
POST	/login	User Login

📜 License
This project is open-source and available under the MIT License.

💡 Author: Shivam Kumar
📧 Contact: shivamkumarsingh8541@gmail.com









