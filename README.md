# 🏦 UDAY Bank - Digital Passbook

Welcome to UDAY Bank, a full-stack web application that functions as a digital passbook and account management system. This project is built from the ground up using Java and the Spring Boot framework, demonstrating a complete and secure web application architecture.

## ✨ Features

* **Secure Authentication:** User registration and login system powered by **Spring Security**, featuring password encryption (BCrypt) and session management.
* **Account Dashboard:** A central dashboard for users to view their current account balance and details at a glance.
* **Transaction Management:** Users can perform credit (deposit) and debit (withdrawal) transactions, which update the account balance in real-time.
* **Digital Passbook:** A detailed, chronological view of all transactions associated with the account, just like a physical passbook.
* **User-Friendly Interface:**
    * A clean user interface built with **Thymeleaf**, HTML, and CSS.
    * Client-side features like a "Show/Hide Password" toggle.
    * Clear error messages on the login page for invalid credentials.

## 🛠️ Technology Stack

This project utilizes a modern and robust set of technologies:

* **Backend:**
    * **Java 17**
    * **Spring Boot 3**
    * **Spring Security:** For handling authentication and authorization.
    * **Spring Data JPA:** For database interaction and object-relational mapping (ORM).
    * **H2 In-Memory Database:** For easy setup and development.
    * **Maven:** For project build and dependency management.

* **Frontend:**
    * **Thymeleaf:** A server-side Java template engine for dynamic HTML.
    * **HTML5**
    * **CSS3**
    * **JavaScript**

## 🚀 How to Run the Project

To run this project on your local machine, you'll need:
* JDK 17 (or higher)
* Apache Maven

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd your-repository-name
    ```
3.  **Run the application using Maven:**
    ```bash
    mvn spring-boot:run
    ```
The application will start on `http://localhost:8080`.

## 🔒 Test Credentials

You can log in and test the application using the default user created on startup:

* **Username:** `uday`
* **Password:** `password123`
