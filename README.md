# 🗓️ Appointment Booking Application

A professional full-stack web application for booking, editing, and canceling appointments using **Spring Boot 3**, **REST API**, and **PostgreSQL** as the backend database. The frontend is built with **HTML, CSS, and JavaScript**.

---

## 🚀 Features

- Book an appointment with:
  - Full Name
  - Email Address
  - Phone Number
  - Service Type
  - Appointment Date & Time
- View all upcoming appointments
- Edit or update existing appointments
- Cancel appointments
- REST API integration
- Responsive and modern user interface

---

## 🛠 Technologies Used

| Layer       | Technology           |
|-------------|----------------------|
| Backend     | Java 17, Spring Boot 3.5.4 |
| Frontend    | HTML, CSS, JavaScript |
| Database    | PostgreSQL 15+        |
| ORM         | Spring Data JPA       |
| Build Tool  | Maven                 |

---

## 📁 Project Structure

```
Appointment-Booking-Application/
├── src/
│ └── main/
│ ├── java/com/example/appointmentcrud/
│ │ |
│ │ │ └── AppointmentController.java
│ │ |
│ │ │ └── AppointmentService.java
│ │ |
│ │ │ └── AppointmentRepository.java
│ │ │ 
│ │ | └── AppointmentCrudApplication.java
│ └── resources/
│ ├── application.properties
│ └── static/index.html
├── pom.xml
└── README.md

```

---

## 🧩 REST API Endpoints

| Method | Endpoint                | Description             |
|--------|-------------------------|-------------------------|
| GET    | `/api/appointments`     | Get all appointments    |
| GET    | `/api/appointments/{id}`| Get appointment by ID   |
| POST   | `/api/appointments`     | Create new appointment  |
| PUT    | `/api/appointments/{id}`| Update appointment      |
| DELETE | `/api/appointments/{id}`| Delete appointment      |

---

## 🛠️ Configure PostgreSQL

- Create a PostgreSQL database: `appointmentdb`
- Update `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/appointmentdb
spring.datasource.username=postgres
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

server.port=8082
```
---
##⚙️ Build and Run

**🧪 Backend (Spring Boot)**
-run the backend using run application as spring boot pp

**🌐 Frontend**
  - use python server to run frontend app
    python -m http.server 5500

---

##📸 Sample UI
<img width="631" height="247" alt="image" src="output.png" />


---

##📅 Sample Database Output



---
## 👩‍💻 Contact
**Name:** Prerana Anand Nalawade  
**Email:** prerananalawade5@gmail.com  
**GitHub:** https://github.com/PreranaNalawade  
