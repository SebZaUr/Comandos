# Guia De Comandos

## Git

- [x] **git init**: Inicializa un repositorio git en el director
- [x] **git add .**: Agrega todos los archivos del directorio actual
- [x] **git commit -m "Mensaje de la confirmación"**: Confirma los cambios agregados con un mensaje descriptivo.
- [x] **git pull "nombre_remoto" "rama"**: Fusiona la rama especificada con la que se encuentra localmente
- [x]  **git push "nombre_remoto" "rama"**: Añade y sube al repositorio remoto una nueva rama llamada "rama". Si ya existe, fusiona
- [x] **git branch "nombre de la rama"**: Crea una nueva rama a partir de la rama activa
- [x] **git checkout -b "nombre de la rama"  "id_de_la_rama_o_commit"**: Crea y cambia a una rama basado en una rama
- [x] **git checkout "nombre de la rama"** : Cambia a la rama indicada
- [x] **git diff**: muestra las diferencias de archivos que aún no se han preparado.
- [x] **git status**: Muestra el estado de tu directorio de trabajo.
- [x] **git log**: Muestra el historial de commits.
- [x] **git checkout**: -b branch_name: Crea y cambia a una nueva rama
- [x] **git merge "nombre de la rama"**: Fusiona la rama indicada con la main.
- [x] **git stash**: Me guarda los cambios en el local sin fusionarlos con el repositorio.
- [x] **git stash** pop: Aplica y elimina los cambios ocultos.
- [x] **git show "commit_id"**: Muestra detalles sobre una confirmación.
- [x] **git reset HEAD~1**: Deshacer la última confirmación, conservando los cambios localmente.
- [x] **git format-patch -1 "commit_id"**: Crea un archivo de parche para una confirmación específica.
- [x] **git apply patch_"file_name"** : Aplica los cambios de un archivo de parche.
- [x] **git branch -D "branch_name"**: Elimina una rama a la fuerza.
- [x] **git reset**: Deshacer confirmaciones moviendo la referencia de la rama.
- [x] **git revert**: Deshacer confirmaciones mediante la creación de una nueva confirmación.
- [x] **git cherry-pick "commit_id"**: Aplica los cambios de una confirmación específica.
- [x] **git branch**: Enumera las ramas.
- [x] **git reset --hard**: Restablece todo a una confirmación anterior, borrando todos los cambios no confirmados.
- [x] **git reset --hard "id_de_la_rama_o_commit"**: Mueve la punta de la rama actual al commit especificado (o rama) y actualiza tanto el índice (staging area) como el directorio de trabajo para que coincidan con ese commit.

## Docker

- [x] **docker build -t nombredelcontenedor**: Construye una imagen docker a partir del directorio actual y le asigna el nombre
- [x] **docker image tag "nombre imagen"  "usuario/imagen": Versión**: Asigna etiqueta y nombre al contenedor docker.
- [x] **docker push "nombre imagen"** : Sube la imagen docker al registro.
- [x] **docker run -d --name="container_name" "imagen_id"** : Corre una instancia de la imagen como contenedor y le asigna la imagen.

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
