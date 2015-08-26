# Lista de comandos básicos de mongodb.

- Iniciar mongo indicando la ubicación de la base de datos

````
mongod --dbpath directorio_de_la_base
````

 - Abrir la consola de mongo
````
mongo
````

 - Dentro de la consola listar las bases de datos existentes

````
show dbs
````

 - Cambiar a una base de datos (si no existe se crea en el momento)

````
use base_de_datos
````

 - Mostrar las colecciones de la base de datos

````
show collections
````

 - Mostrar todos los elementos dentro de una colección

````
db.coleccion.find()
````

 - Inserta un objeto en una colección

````
db.coleccion.insert({a: "valor", b: "valor"});
````

- Consultar una colección usando un filtro

`````
db.coleccion.find({a: 'valor'});
