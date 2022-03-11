# spring-centralized-configuration
Config Server and build a client that consumes the configuration on startup and then refreshes the configuration without restarting the client.

get properties message
### GET http://localhost:8080/message

refresh properties
## POST http://localhost:8080/actuator/refresh


### get properties message
<img width="1063" alt="image" src="https://user-images.githubusercontent.com/59139337/157869963-21cef14f-8ff7-40d7-b960-83f9e8474166.png">

### refresh properties
<img width="1062" alt="image" src="https://user-images.githubusercontent.com/59139337/157871742-801fc61e-a553-4663-9d55-d36910bc0f02.png">

### get properties message again
<img width="1064" alt="image" src="https://user-images.githubusercontent.com/59139337/157871799-548f3891-76f2-46ea-87a7-332185f911f4.png">

https://spring.io/guides/gs/centralized-configuration/

https://cloud.spring.io/spring-cloud-config/reference/html/
