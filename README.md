# Event-Scheduler-Application
- The Event Scheduler App built using Spring Boot 3.0 that provides RESTful APIs which can be easily integrated into any application for scheduling and managing events.

- The APIs allow users to create, update, and delete, retrieve a list of events for a specific time like Day, Week, or Month. Users can also register, update and retrieve the details by themselves. They are secured using JSON Web Tokens (JWT) to ensure that only authorized users can access the data.

- In addition to the core functionality, the APIs include Swagger UI for easy testing and documentation of the API. This allows developers to easily explore the available endpoints and see example requests and responses.

- The APIs use MySQL as their database for storing events and user information. They are designed to be scalable and can handle a large number of events and users.

- Overall, the Event Scheduler APIs are a powerful tool for developers looking to build event scheduling and management functionality into their applications. Their secure design and easy-to-use interface make them suitable for use in a wide range of environments.

# Features
- User Registration & Login
- Update & Fetch User Details
- Schedule, Update, Delete Event
- Get Event By Type [Day, Week, Month]

# Security
- The API is secured using JSON Web Tokens (JWT). To access the API, you will need to obtain a JWT by authenticating with the /login endpoint. The JWT should then be passed in the Authorize option available in the Swagger-UI.

  ### Example:
  - Authorization: <JWT>

# Technologies:
- Java 17 or above
- Spring Boot 3.0
- Spring Data JPA
- JSON Web Tokens (JWT)
- MySQL
- Swagger-UI

# API documentation
- API documentation is available via Swagger UI at http://localhost:8080/swagger-ui/index.html

# Event Scheduler Image
<img width="188" alt="Event-Scheduler-Image" src="https://user-images.githubusercontent.com/101395494/211131507-fb25a63c-c620-4d2f-8446-c97aa6316ce9.png">

# ER-Diagram
![ER_Diagram](https://user-images.githubusercontent.com/101395494/210177816-c40d34a0-ebb9-488d-b904-35ccf4ad417c.jpg)

# API Controllers
<img width="939" alt="Event App Controllers" src="https://user-images.githubusercontent.com/101395494/210179001-2b271f7a-6f13-4060-979b-e88e5a803a93.png">

# Thank You
