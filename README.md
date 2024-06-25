# MicroserviceApplication using spring boot 

## Testing using CURL command
### GET 
```bash
  curl -X GET http://localhost:8080/api/users/
```
### POST
``` bash
curl -X POST http://localhost:8080/api/users -H "Content-Type: application/json" -d "{\"name\":\"aung Ko ko\", \"email\":\"testing@gmail.com\"}"
```
### PUT
``` bash
curl -X PUT http://localhost:8080/api/users/1 -H "Content-Type: application/json" -d "{\"name\":\"aung Ko min\", \"email\":\"testing@gmail.com\"}"
```
### DELETE
``` bash
curl -X DELETE http://localhost:8080/api/users/1
```
