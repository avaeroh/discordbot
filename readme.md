**Requirements**
- Maven (3.8.5+)
- Java 17
- Docker
- Docker Compose

**Usage**

`./mvnw spring-boot:run`
This will run maven (no maven install is required as this uses the spring maven wrapper).


`mvn spring-boot:build-image` will build the Docker image without the need for a dockerfile.