# JWT-Auth_Golang
JSON Web Token Authentication using Golang
Prequels for JWT Authentication in GoLang


DATABASE CONNECTION:
Used Elephant SQL as the database

We need:
1) Gorm Library
	* go get -u gorm.io/gorm
2) Gin Web Framework
	* go get github.com/gin-gonic/gin
3) bcrypt package from go 
	* go get -u golang.org/x/crypto/bcrypt
4) jwt-go package from go
	* go get -u github.com/golang-jwt/jwt/v4
5) Enviroment package from JOHO
	* go get github.com/joho/godotenv
6) CompileDaemon for Go
	* go get github.com/githubnemo/CompileDaemon
7) We would be using the PostGreSQL as database
	* go get -u gorm.io/driver/postgres
  
Please create a enviroment file, with PORT number and Connection URL of PostGreSQL.
