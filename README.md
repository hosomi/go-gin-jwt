# Go lang & Gin Web Framework & JWT 

## setup

```powershell
go mod init go-gin-jwt
go get -u github.com/gin-gonic/gin
go get github.com/dgrijalva/jwt-go
```

## run

```powershell
go run main.go
```

## test token

```powershell
curl --location --request POST "http://localhost:3000/login" --form "email=user@example.com" --form "password=userpassword"
{"token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoidXNlckBleGFtcGxlLmNvbSIsInVzZXIiOnRydWUsImV4cCI6MTYwMDkyOTA3MSwiaWF0IjoxNjAwNzU2MjcxLCJpc3MiOiJwZW5kaW5nLi4uIn0.NH5bJ6lg5t_8TOAd9cJ0NBfUti0pKZwF3k7ndVWXzt0"}
```

Token: ``eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoidXNlckBleGFtcGxlLmNvbSIsInVzZXIiOnRydWUsImV4cCI6MTYwMDkyOTA3MSwiaWF0IjoxNjAwNzU2MjcxLCJpc3MiOiJwZW5kaW5nLi4uIn0.NH5bJ6lg5t_8TOAd9cJ0NBfUti0pKZwF3k7ndVWXzt0``

↓ 

:link: [JSON Web Tokens - jwt.io](https://jwt.io/)   

![jwt.io](jwt.io.png)  

