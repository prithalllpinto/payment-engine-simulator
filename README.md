# Payment Engine Simulator 💳

A robust backend payment processing engine built with **Java** and **Spring Boot**, featuring secure transaction execution, dynamic status management, and idempotency protection against duplicate charges.

## 🚀 Key Features
- **Idempotency Protection:** Prevents accidental double-charging and race conditions during concurrent network retries.
- **RESTful API Endpoints:** Clean endpoints for processing payments, retrieving transaction histories, and updating status states.
- **Robust Validation & Exception Handling:** Strict data validation layers with global exception handling for standardized error responses.
- **Live Frontend Simulator:** Responsive user interface built with Bootstrap to test live payment workflows and track transaction statuses.
- **Persistent Data Storage:** Structured relational database modeling powered by PostgreSQL and Spring Data JPA.
- **Automated Testing Suite:** High code reliability backed by unit and service layer tests.

## 🛠️ Tech Stack
- **Backend:** Java 17+, Spring Boot, Spring Data JPA
- **Database:** PostgreSQL
- **Frontend:** HTML5, CSS3, Bootstrap
- **Testing & Build:** JUnit 5, Mockito, Maven

## 🔌 API Endpoints (Quick Overview)
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/v1/payments` | Process a new payment transaction |
| `GET` | `/api/v1/payments/{id}` | Retrieve transaction details by ID |
| `GET` | `/api/v1/payments` | List payment transaction history |
