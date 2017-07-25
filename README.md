# flyway
test flyway

```
$ docker run --name my-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -e MYSQL_USER=test -e MYSQL_PASSWORD=testpw -e MYSQL_DATABASE=app -p 3306:3306 -d mysql
```

```
$ flyway -configFile=flyway.conf migrate
````
