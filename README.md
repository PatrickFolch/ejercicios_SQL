# ejercicios_SQL

>1.Crea una base de datos denominada vuelos. Con las siguientes características:
* Character set = Latin1
* Collate = latin1_spanish_ci

CREATE DATABASE vuelos
CHARACTER SET = Latin1
COLLATE = latin1_spanish_ci; 

>2.Renombra la base de datos a viajes.

>3.Crea una tabla denominada clientes que contendrá los siguientes campos:
* id 
  * Integer
  * autoincremental 
  * not_null 
  * primary_key
* nombre
  * varchar(50)
* apellidos
  * varchar(50)
* direccion
  * varchar(150)

  CREATE TABLE clientes(
      id integer auto_increment not null primary key,
      nombre varchar(50),
      apellidos varchar(50),
      direccion varchar(150)
  );
  