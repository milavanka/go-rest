# go-rest
simple golang rest api

### start the code

```go run main.go```
 
### send get request for list users

```curl http://localhost:8081/users/1```

### send post request for create new users

```curl POST -H "Content-Type: application/json" http://localhost:8081/users/3 -d '{"id":"3", "firstname":"ivanka", "lastname":"milakova"}'```

### send delete request for delete users

```curl -X DELETE http://localhost:8081/users/3```
