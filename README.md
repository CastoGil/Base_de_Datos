# Base de Datos de Oradores

Este repositorio alberga una base de datos de ejemplo llamada "Oradores" junto con su estructura y datos de muestra. La base de datos "Oradores" está diseñada para almacenar información sobre oradores que participan en eventos, conferencias u otras actividades similares.

## Estructura de la Tabla

La tabla "Oradores" se define de la siguiente manera:

- **id_orador** (INT): Campo de ID autoincremental que sirve como clave primaria.
- **nombre** (VARCHAR): Nombre del orador, con una longitud máxima de 40 caracteres.
- **apellido** (VARCHAR): Apellido del orador, con una longitud máxima de 40 caracteres.
- **email** (VARCHAR): Dirección de correo electrónico del orador, con una longitud máxima de 255 caracteres.
- **tema** (VARCHAR): Tema o área de especialización del orador, con una longitud máxima de 30 caracteres.
- **fecha_alta** (TIMESTAMP): Fecha y hora en que se registró al orador, con un valor predeterminado de la fecha y hora actual.

La clave primaria se establece en el campo "id_orador."

## Datos de Muestra

Se han insertado 10 registros de muestra en la tabla "Oradores" para ilustrar su funcionamiento. Estos registros contienen información ficticia sobre oradores en diferentes áreas.

## Respaldo de la Base de Datos

También se proporciona un archivo de respaldo ("backup.rar") que contiene la estructura de la tabla y los datos de muestra. Puedes utilizar este archivo para restaurar la base de datos en tu entorno MySQL. (Se necesita descomprimir el archivo winrar)


