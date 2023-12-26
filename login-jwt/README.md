
#JWT(Json Web Token) Authentication 

## after run install :

- go get github.com/gin-gonic/gin
- go get github.com/dgrijalva/jwt-go


## run command : 

- go run cmd/main.go

## test app curl request : 
### login:
    - curl --location 'http://127.0.0.1:8080/public/login' --header 'Content-Type: application/json' --data '{"username": "user","password": "password"}'
### register: 
    - curl --location 'http://127.0.0.1:8080/public/register' --header 'Content-Type: application/json' --data '{"username": "user","password": "password"}'