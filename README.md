# Warehouse-Microservice

Warehouse-Microservice is a microservice for managing warehouses. It handles the creation, updating, and deletion of warehouses, and integrates with other microservices in a distributed system.

## Features

- Manage warehouse information: creation, updating, and deletion.
- Built with Spring Boot and Spring Cloud.
- Uses MariaDB for database management.
- Eureka client for service discovery.

## Technologies

- **Java 17**
- **Spring Boot 3.3.3**
  - Spring Boot Starter Data JPA
  - Spring Boot Starter Security
  - Spring Boot Starter Web
- **Spring Cloud 2023.0.3**
  - Netflix Eureka Client
- **MariaDB** (Database)
- **Lombok** (Optional)
- **JUnit & Spring Security Test** (For testing)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/warehouse-microservice.git
    cd warehouse-microservice
    ```

2. **Build the project:**

    Make sure you have Maven installed. You can build the project using the following command:

    ```bash
    mvn clean install
    ```

3. **Configure the Database:**

    This microservice uses MariaDB as its database. Ensure that MariaDB is installed and running on your system. You may need to set up a database for this service.

    Update the `application.properties` or `application.yml` with your database configuration.

4. **Run the Microservice:**

    Currently, the Docker setup is not configured. However, you can run the service directly using Maven:

    ```bash
    mvn spring-boot:run
    ```

    Once Docker support is added, instructions will be provided here.

## Usage

Details on how to use the service, including the available endpoints, request/response formats, and examples, will be added soon.

## Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request.

## License

This project is currently not under any license.
