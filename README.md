# Products System - Backend

This repository contains the backend service for a Product Management prototype, designed as the architectural
foundation for the Legal System platform.

## 🛠 Tech Stack

* **Language:** Java
* **Database:** PostgreSQL (with `pgvector` extension)
* **Framework:** Spring Boot

## 🚀 Getting Started

Follow these instructions to set up the project locally for development.

### Prerequisites

* Docker & Docker Compose
* Java JDK (Version 17 or higher recommended)
* IntelliJ IDEA (Recommended)

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Cristian5c26l/ProductSystem-API
   ```
2. **Open the project:**
   Open the folder in your preferred IDE (IntelliJ IDEA is recommended).

3. **Prepare the environment:**
   Ensure that ports **8080** (Web) and **5432** (Database) are free on your machine.

4. **Start the Database:**
   Run the following command to start the PostgreSQL container with semantic search support (`pgvector`):
   ```bash
   docker compose up -d
   ```
5. **Run the application:**
   You can start the server using the Maven wrapper in your terminal:
   ```bash
   ./mvnw spring-boot:run
   ```

### 🧪 Running Tests

To execute the unit tests and verify the system logic, run:

```bash
./mvnw test
```