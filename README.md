📚 Student Registration API

A RESTful backend application built using Spring Boot and MongoDB to manage student registration data with full CRUD functionality.

🚀 Features

Create new student records

Retrieve all students

Get student by ID

Update student details

Delete student record

MongoDB integration

Layered architecture (Controller → Service → Repository)

🛠 Tech Stack

Java

Spring Boot

Spring Data MongoDB

Maven

MongoDB

Postman (for API testing)

📂 Project Structure
src/main/java
 ├── controller
 ├── service
 ├── repository
 └── model

 ⚙️ Setup & Installation
1.Clone the repository
git clone https://github.com/your-username/student-registration-api.git

2.Configure MongoDB in application.properties
spring.data.mongodb.uri=mongodb://localhost:27017/studentdb

3.Run the project
mvn spring-boot:run

📬 API Endpoints
Method	Endpoint	Description
POST	/students	Add new student
GET	/students	Get all students
GET	/students/{id}	Get student by ID
PUT	/students/{id}	Update student
DELETE	/students/{id}	Delete student
🎯 Learning Outcomes

Understanding of REST API development

Integration of Spring Boot with MongoDB

Implementation of layered architecture

Hands-on CRUD operations

👨‍💻 Author

Vishal Vishwakarma
