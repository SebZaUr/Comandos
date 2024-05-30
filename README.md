# Guia De Comandos

## Git

- [] **git init**: Inicializa un repositorio git en el director
- [] **git add .**: Agrega todos los archivos del directorio actual
- [] **git commit -m "Mensaje de la confirmación"**: Confirma los cambios agregados con un mensaje descriptivo.
- [] **git pull "nombre_remoto" "rama"**: Fusiona la rama especificada con la que se encuentra localmente
- []  **git push "nombre_remoto" "rama"**: Añade y sube al repositorio remoto una nueva rama llamada "rama". Si ya existe, fusiona
- [] **git branch "nombre de la rama"**: Crea una nueva rama a partir de la rama activa
- [] **git checkout -b "nombre de la rama"  "id_de_la_rama_o_commit"**: Crea y cambia a una rama basado en una rama
- [] **git checkout "nombre de la rama"** : Cambia a la rama indicada
- [] **git diff**: muestra las diferencias de archivos que aún no se han preparado.
- [] **git status**: Muestra el estado de tu directorio de trabajo.
- [] **git log**: Muestra el historial de commits.
- [] **git checkout**: -b branch_name: Crea y cambia a una nueva rama
- [] **git merge "nombre de la rama"**: Fusiona la rama indicada con la main.
- [] **git stash**: Me guarda los cambios en el local sin fusionarlos con el repositorio.
- [] **git stash** pop: Aplica y elimina los cambios ocultos.
- [] **git show "commit_id"**: Muestra detalles sobre una confirmación.
- [] **git reset HEAD~1**: Deshacer la última confirmación, conservando los cambios localmente.
- [] **git format-patch -1 "commit_id"**: Crea un archivo de parche para una confirmación específica.
- [] **git apply patch_"file_name"** : Aplica los cambios de un archivo de parche.
- [] **git branch -D "branch_name"**: Elimina una rama a la fuerza.
- [] **git reset**: Deshacer confirmaciones moviendo la referencia de la rama.
- [] **git revert**: Deshacer confirmaciones mediante la creación de una nueva confirmación.
- [] **git cherry-pick "commit_id"**: Aplica los cambios de una confirmación específica.
- [] **git branch**: Enumera las ramas.
- [] **git reset --hard**: Restablece todo a una confirmación anterior, borrando todos los cambios no confirmados.
- [] **git reset --hard "id_de_la_rama_o_commit"**: Mueve la punta de la rama actual al commit especificado (o rama) y actualiza tanto el índice (staging area) como el directorio de trabajo para que coincidan con ese commit.

## Docker

- [x] **docker build -t nombredelcontenedor**: Construye una imagen docker a partir del directorio actual y le asigna el nombre
- [] **docker image tag "nombre imagen"  "usuario/imagen": Versión**: Asigna etiqueta y nombre al contenedor docker.
- [] **docker push "nombre imagen"** : Sube la imagen docker al registro.
- [] **docker run -d --name="container_name" "imagen_id"** : Corre una instancia de la imagen como contenedor y le asigna la imagen.
