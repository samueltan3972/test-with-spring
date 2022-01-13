### Run

Clone the project and open with cmd
`mvnw spring-boot:run`

### Docker

`mvnw package`

`docker build -t seanhao1233/test-with-spring .`

`docker run -p 8080:8080 seanhao1233/test-with-spring`

### View Result

view the result at http://localhost:8080
it comes with 3 api end point
- /hello : return a simple hello world message
- /database : perform all database CRUD operation
- /fibonacci : compute and return first 5,000 fibonacci numbers
