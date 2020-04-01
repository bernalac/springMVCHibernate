# Tarea 
1DAW IES Polígono Sur

# springMVCHibernate
Es un proyecto maven, web.
Este proyecto realiza inserts, edits y deletes sobre MySQL y SQLite3.

## Getting Started
Haciendo fork, teníamos la funcionalidad de interaccionar con la base de datos MySQL. A partir de ello, he realizado una segunda funcionalidad que es la de interaccionar con la base de datos SQLite3.
He relizado la moficiación de los parámetros del fichero database.properties y he añadido dos drivers al pom.xml.

### Prerequisites

Qué cosas necesitamos antes de empezar:
Instalaciones:
```
mysql-server
sqlite3 
```

Las librerías necesarias a partir de este fork son:
```
sqlite3
hibernate sqlite3
```
Se pueden obtener mediante estas urls:
https://mvnrepository.com/artifact/org.xerial/sqlite-jdbc/3.28.0
https://mvnrepository.com/artifact/com.zsoltfabok/sqlite-dialect/1.0

## Creación
Neesitamos tener creada una database en cada servidor y una tabla en cada una con sus columnas.
Los ficheros de creación de base de datos están dentro de project/sql/ y se llaman:
```
MySQL: script.sql
SQLite3: paises.db
```

## Execute

Para ejecutar, nos vamos al raíz del proyecto maven y ejecutamos el comando:
```
$ mvn package jetty:run
```

## Authors

* **Paulino Huerta** - *Initial work* 
* **Javier Bernal** - *Final work* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
