# Tarea 
1DAW IES Polígono Sur

# springMVCHibernate
Es un proyecto maven, web.
Este proyecto realiza inserts, edits y deletes sobre MySQL y SQLite3.

## Getting Started
Haciendo fork, teníamos la funcionalidad de interaccionar con la base de datos MySQL. A partir de ello, he realizado una segunda funcionalidad que es la de interaccionar con la base de datos SQLite3.
He relizado la moficiación de los parámetros del fichero database.properties y he añadido dos drivers al pom.xml.


## Execute

Para ejecutar, nos vamos al raíz del proyecto maven y ejecutamos el comando:
```
$ mvn package jetty:run
```


### Prerequisites

Qué cosas necesitamos antes de empezar:
Instalaciones:
```
mysql-server
sqlite3 
```

Las librerías necesarias son:
```
mysql
sqlite3
```
Se pueden obtener mediante estas urls:
https://mvnrepository.com/artifact/org.xerial/sqlite-jdbc/3.28.0
https://mvnrepository.com/artifact/com.zsoltfabok/sqlite-dialect/1.0
https://mvnrepository.com/artifact/mysql/mysql-connector-java/8.0.18

## Authors

* **Paulino Huerta** - *Initial work* 
* **Javier Bernal** - *Final work* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
