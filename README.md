# spring-rest-demo
Run `spring init --dependencies=data-jpa,h2,lombok --build=maven spring-demo`

Run `./mvnw spring-boot:run`

Run `curl -X POST -H "Content-Type: application/json" -d '{"name": "klinskoe", "abv": 7.5}' http://localhost:8080/beers`

Run `curl http://localhost:8080/beers/3`
