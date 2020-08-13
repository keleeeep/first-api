# Simple API

Simple API with CRUD feature

## Tech Stack
* Golang
* MySQL

## Prerequisites
Enter the following command to install sql driver for mysql, gin and gorm in the project.
```
go get github.com/go-sql-driver/mysql
go get github.com/gin-gonic/gin
go get github.com/jinzhu/gorm
```

## Running the REST API
```
go run main.go
```


## Database Schema
### User
*name
*email
*phone
*address

## API Endpoints
| Route         | HTTP          | Description           |
| ------------- |:-------------:| ---------------------:|
| /api/user     | GET           | Get all users         |
| /api/user:id  | GET           | Get single user       |
| /api/user     | POST          | Create a user         |
| /api/user:id  | PUT           | Update data of a user |
| /api/user:id  | DELETE        | Delete a user         |


## Reference
[Create Your First Rest API With GOLANG using GIN, GORM and MySql](https://medium.com/wesionary-team/create-your-first-rest-api-with-golang-using-gin-gorm-and-mysql-d439bcc6f987)
