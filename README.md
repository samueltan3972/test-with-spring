### Run

mvnw spring-boot:run

### Docker

mvnw package

docker build -t seanhao1233/test-with-spring .

docker run -p 8080:8080 seanhao1233/test-with-spring