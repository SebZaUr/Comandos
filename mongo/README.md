## Mongo DB

- [x] **use "nombre_base"**: Me crea una nueva base de datos o cambia a la base con ese nombre.
- [x] **show dbs**: Muesta las bases y sus tamaños.
- [x] **show collections**: Muestra las colleciones de una base.
- [x] **db.stats**: Muesta las caracteristicas de la base.
- [x] **db.createCollection("collection_name")**: Crea una colección dentro de la base.
- [x] **db."collection_name".insertOne({"datos"})**: Insertar datos a una colección.
- [x] **db."collection_name".find()**: Lista todos los objetos de la colección.
- [x] **db."collection_name".find("atributo" : "$filtro")**: Me permite filtrar los objetos de la colección.
- [x] **db."collection_name".updateOne({"objeto"}, {$set:{"atributo_actualizar"}})**: Me actualiza el primer objeto que encuentre con el valor dado.
- [x] **db."collection_name".deleteOne("atrinbuto")**: Me borra el primer objeto que encuentre con ese atributo.
- [x] **db."collection_name".insertMany(["Lista_objetos"])**: Agrega varios objetos dentro de una colección.
- [x] **db."collection_name".updateMany({"objeto"}, {$set:{"atributo_actualizar"}})**: Me actualiza varios registro que cumplan el valor dado.