# Hello World with Quarkus

This is a simple Hello World project using Quarkus, a Java framework for microservices.

## Endpoints

The project creates a simple REST endpoint:

- **GET** `/users`: Returns the message "Hello World!"

## Technologies Used

- **Quarkus**: Java framework for microservices
- **JAX-RS**: API for creating RESTful services
- **Jakarta EE**: Java component API
- **JSON**: Data format used for the endpoint response

## How to Run the Project

1. Clone the repository:

    ```bash
    git clone https://github.com/<your-username>/<repository-name>.git
    cd <repository-name>
    ```

2. Build and run the project using Maven:

    ```bash
    ./mvnw compile quarkus:dev
    ```

3. Access the endpoint in the browser or Postman:

    ```bash
    http://localhost:8080/users
    ```

    The response will be:

    ```json
    "Hello World!"
    ```

## Contributions

Feel free to contribute improvements or suggestions to the project.

## License

This project is licensed under the MIT License.
