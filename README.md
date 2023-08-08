CHATOP API

## Setup the backend

Create a file named application.properties in the /backend/src/main/resources folder.
Fill it with the variables existing on the application.example.properties and your custom values.
Please note that by default the frontend will call the backend at port 3001 and use /api as context path.
If developping on localhost, your server.host will be "http://localhost:"

With maven, compile and run the project : `mvn compile` and `mvn spring-boot:run`

A message is displayed at the end of the loading time: "App started with success"

## Setup the frontend

From the frontend folder, execute `npm install` in the terminal, once finished start the project with `ng serve`.

## Swagger UI

Once Spring Boot is running, you can access Swagger UI documentation at the following address: http://localhost:{port}/{contextPath}/swagger-ui/index.html#/
