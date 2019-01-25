
# Spring Boot + Spring Security + JWT + MySQL + React Full Stack Polling App
- https://www.callicoder.com/series/spring-security-react/


```
$ docker run --name mysql -e MYSQL_ROOT_PASSWORD=callicoder -d -p 3306:3306 mysql
$ mysql -u root -h 127.0.0.1 -P3306 -p
# create database polling_app
```

```
$ mvn spring-boot:run
```
access locahost:5000
```
> use polling_app;
> INSERT INTO roles(name) VALUES('ROLE_USER');
> INSERT INTO roles(name) VALUES('ROLE_ADMIN');
```
