
## Learning Spring Boot

Study project

## Hints

* **Build project:** mvn clean package
* **Run app:** java -jar target/learning-spring-0.0.1-SNAPSHOT.jar
* **Check in browser:** localhost:8080
* **Use postgresql docker instance:**
    * install postgresql
    * add it to environment variable: PATH
    * login to postgres: psql -U postgres
    * create database: CREATE DATABASE dev;
    * exit
    * run shell script in bin directory: ./start_postgres.sh
* **Test REST endpoint for adding new guests:** curl -X POST http://localhost:8080/api/guests -H 'Content-Type: application/json' -d '{"lastName":"Ztest", "firstName":"Test"}'


