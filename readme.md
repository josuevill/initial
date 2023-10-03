# "Aprendiendo Go" con un proyecto

Este es un simple API utilizando go y como base de datos postgres

## Creando el projecto inicial
    Crear el archivo main.go
    En el teminal:
 
    > go mod init `<nombre de projecto>` o `<repositorio github>`
    > go build
    > go build && ./nombre de projecto

# PostgreSQL

PostgreSQL es una base de datos de código abierto lista para producción. Es una base de datos de excelente elección para muchas aplicaciones web, en mi opinión es una gran base de datos para projectos grandes ~~este projecto no sería el caso~~.

* [Instalar postgres](https://www.howtoforge.com/how-to-install-postgresql-and-pgadmin-tool-on-debian-12/)

## Creando la base de datos ~~en caso que use el terminal y no pgadmin~
    En el teminal:

    > psql -U postgres -W
    > CREATE DATABASE dbname;
    > GRANT ALL PRIVILEGES ON DATABASE <dbname> TO <username>;
    > \l 
