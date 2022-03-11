# spring-centralized-configuration
Config Server and build a client that consumes the configuration on startup and then refreshes the configuration without restarting the client.

## GET http://localhost:8080/message

get properties message

## POST http://localhost:8080/actuator/refresh

refresh properties
