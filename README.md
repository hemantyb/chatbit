# ChatBit

ChatBit is a simple real-time chat application built with Java and Spring Boot.

## Technologies Used

*   **Backend:**
    *   Java 21
    *   Spring Boot 3.5.4
    *   Spring Web
    *   Spring WebSocket
    *   Maven

*   **Frontend:**
    *   HTML5
    *   Thymeleaf
    *   Bootstrap 5
    *   JavaScript
    *   SockJS
    *   Stomp.js

## Setup and Run

### Prerequisites

*   JDK 21
*   Maven

### Steps

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd chatbit
    ```

2.  **Build the project:**
    ```bash
    ./mvnw clean install
    ```

3.  **Run the application:**
    ```bash
    ./mvnw spring-boot:run
    ```
    Alternatively, you can run the packaged JAR file:
    ```bash
    java -jar target/chatbit-0.0.1-SNAPSHOT.jar
    ```

4.  **Access the application:**
    Open your web browser and navigate to [http://localhost:8080/chat](http://localhost:8080/chat)

---

**Note:** This project is for educational purposes only. I do not hold any rights to this project.
