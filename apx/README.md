# COMANDOS APX

- __apx init du-onlien -u="*UUAA*" -n="*Nombre*" -d= "*descripción*"__ : Inicia el proyecto.
- __apx add dto -c="*Nombre*" --domain="*Dominio*" -d="*Descripción*"__ : Crea un DTO
- __apx add lib -c="*nombre*" -d="*Descripción*"__: Crea una libreria.
- __apx add class --subpackage="" --class-name="*classname*" -y__: Crea un DTO real

## PARA ASIGNAR ALGO TENGO QUE ESTAR EN LA CARPETA DEL COMPONENTE AL CUAL SE LO ASIGNO

## DEPENDENCIAS

- __apx add dep -a=*Nombre del DTO* -g=*"com.bbva.uuaa.dto.dominio"* -v=*"versión del dto"*__: Crea una dependencia a un DTO.
- __apx add dep -a=*"Nombre"* -v=*"Versión de la libreria"*__: Crearle al componente una dependencia con una libreria.
- __apx show dep__: Me muestra las depencencias que tengo en mi proyecto.

## UTILIDADES

### Lista de utilidades

### Se le agrega a la implementación

- __*jdbc*__: Oracle DB
- __*intapiconnector*__: Servicios ASO internos
- __*extapiconnector*__: Servicios externos
- __*mongo*__: Mongo DB
- __*drools*__: Motor de reglas
- __*cics*__: Uso transacciones Host - 3270 (Cobol)

## Comandos

- __apx add util -n __*nombre de la utilidad*__ -y__: Le asigno la utilidad a la libreria.
- __apx del util -n __*nombre de la utilidad*__ -y__: Borro una utilidad de la libreria.

## TRANSACCIONES/JOBS

### Se ejecuta sobre la unidad de despliegue

- __apx add trx/job -c=*"Nombre"* --trx-version="01" --trx-country="CO" -d=*"Descripción"*__: Crear una transacción o un job

### Agregar entradas/salidas

- __apx add in__
- __apx add out__

Se le agregan estas diferentes etiquetas
-__--root__ : La ubicación dentro del mensaje de entrada
-__--tag__ : Tipo de variable a agregar (dto, parameter – variable suelta)
-__-n__ : Nombre de la variable de entrada (Criterio del desarrollador)
-__-a__ : nombre completo del componente APX DTO
-__-p__ : nombre completo clase paquete + . + nombre clase
-__-m__ : ¿Es obligatorio?
-__-t__ : Tipo de variable

## Despliegue

__Se ejecuta desde la carpeta *artifact* y se debe crear del más pesado al más libiano y  en orden de importancia__

__apx deploy local --project-path=*./carpeta/nombre_del_componente* --runtime=online --country=COL -y__

__Para levantar el servicio conocamos:__

### apx start online
