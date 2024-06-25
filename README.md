# MicroserviceApplication using spring boot 

## Testing
curl -X GET http://localhost:8080/api/users/

curl -X POST http://localhost:8080/api/users -H "Content-Type: application/json" -d "{\"name\":\"aung Ko ko\", \"email\":\"testing@gmail.com\"}"

curl -X PUT http://localhost:8080/api/users/1 -H "Content-Type: application/json" -d "{\"name\":\"aung Ko min\", \"email\":\"testing@gmail.com\"}"

curl -X DELETE http://localhost:8080/api/users/1
