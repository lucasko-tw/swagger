# Swagger Docker

Import Local swagger File
```console
docker run -p 8081:8080 -e SWAGGER_JSON=/mnt/swagger.json -v $PWD:/mnt swaggerapi/swagger-ui
```
