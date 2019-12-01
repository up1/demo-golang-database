# Code Example

01. Global variable
02. Dependency Injection
03. Interface
04. Context

## Start database with docker
```
$docker container run -d \
 -e POSTGRES_USER=user \
 -e POSTGRES_PASSWORD=pass \
 -e POSTGRES_DB=bookstore \
 -p 5432:5432 \
 postgres:12
```

Code example from [Practical Persistence in Go: Organising Database Access](https://www.alexedwards.net/blog/organising-database-access)
