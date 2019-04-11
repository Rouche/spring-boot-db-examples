# Spring Boot Postgress Example

You can learn more about my courses [here](http://courses.springframework.guru/courses/) on my site.

#Posgres Docker

docker run --name postgres -p 5432:5432 -e POSTGRES_PASSWORD=postgres@rouche -d postgres

--shell into posgres
docker exec -it postgres bash
su postgres -
/usr/lib/postgresql/10/bin/createdb springbootdb