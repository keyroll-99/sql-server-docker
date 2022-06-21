# sql-server-docker

It's docker-compose files for run database on localhost

example run command

`docker-compose -f ./mssql-compose.yaml -p mmsql up -d` -> to run mssql server, it's should run on 1433 port

`docker-compose -f ./mysql-compose.yaml -p mysql up -d` -> to run mysql server, it's should run on 3306 port

`docker-compose -f ./postgres -p postgres up -d` -> to run postgres server, is should run on 5432 port, additionat if you want run pgAdmin, you have to uncomment commented block, pgAdmin should run on "http://localhost:5050" url
