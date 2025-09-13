# springboot3-practice

## Build
`clean package -DskipTests`

## Run

```
  docker compose up -d
  mvn spring-boot:run "-Dspring-boot.run.arguments=--spring.datasource.url=jdbc:mariadb://localhost:3306/<db_name> --spring.datasource.username=<user_name> --spring.datasource.password=<pwd>"
```
