# Guia De Comandos

## Git

- [ ] **git init**: Inicializa un repositorio git en el director
- [x] **git add .**: Agrega todos los archivos del directorio actual
- [ ] **git commit -m "Mensaje de la confirmación"**: Confirma los cambios agregados con un mensaje descriptivo.
- [] **git pull "nombre_remoto" "rama"**: Fusiona la rama especificada con la que se encuentra localmente
- []  **git push "nombre_remoto" "rama"**: Añade y sube al repositorio remoto una nueva rama llamada "rama". Si ya existe, fusiona
- [] **git branch "nombre de la rama"**: Crea una nueva rama a partir de la rama activa
- [x] **git checkout -b "nombre de la rama"  "id_de_la_rama_o_commit"**: Crea y cambia a una rama basado en una rama
- [] **git checkout "nombre de la rama"** : Cambia a la rama indicada

## Docker
- [x] **docker build -t nombredelcontenedor .**: Construye una imagen docker a partir del directorio actual y le asigna el nombre
- [] **docker image tag "nombre imagen"  "usuario/imagen": Versión**: Asigna etiqueta y nombre al contenedor docker.
- [] **docker push "nombre imagen"** : Sube la imagen docker al registro.
- [] **docker run -d --name="container_name" "imagen_id"** : Corre una instancia de la imagen como contenedor y le asigna la imagen.