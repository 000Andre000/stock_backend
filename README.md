# Backend README

## Steps to Run the Backend Locally

### Prerequisites
- Java Development Kit (JDK) installed
- MySQL server installed and running
- Maven installed (optional, if not included in your IDE)

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <backend-repository-url>
   cd <backend-repository-folder>
   ```

2. **Set Up the MySQL Database**
   - Create a MySQL database and note down the credentials (username, password, database name).
   - Import the provided database schema or data (if available).

3. **Configure the Application**
   - Update the `application.properties` file (located in `src/main/resources`) with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/<your-database-name>
     spring.datasource.username=<your-username>
     spring.datasource.password=<your-password>
     ```

4. **Run the Spring Boot Application**
   - Use Maven to build and run the application:
     ```bash
     ./mvnw spring-boot:run
     ```
   - If using *VS CODE* run the application using Run Java on the Drop Down
    
     

5. **Access the Backend**
   - The backend API should now be accessible at `http://localhost:8080`.

## Assumptions or Limitations

- The backend assumes a local MySQL instance is running.
- No authentication or authorization mechanisms are implemented (unless explicitly specified).
- Tested only in development environments.

## Links

- **Deployed Backend Application:** [Backend Application URL](<insert-backend-deployment-url>)
- **Live API Documentation:** [API Documentation URL](<insert-api-documentation-url>)

