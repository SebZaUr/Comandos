## Docker

- [x] **docker build -t nombredelcontenedor**: Construye una imagen docker a partir del directorio actual y le asigna el nombre
- [x] **docker image tag "nombre imagen"  "usuario/imagen": Versión**: Asigna etiqueta y nombre al contenedor docker.
- [x] **docker push "nombre imagen"** : Sube la imagen docker al registro.
- [x] **docker run -d -p "puerto_deseado":"puerto_defecto" --name="container_name" "imagen_id"** : Corre una instancia de la imagen como contenedor y le asigna la imagen ademas que le cambia el puerto por el cual corre.
- [x] **docker-compose up -d** Ejecuta el archivo docker-compose.yml