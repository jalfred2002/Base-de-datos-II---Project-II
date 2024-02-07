# Informe del Proyecto de Sistemas de Bases de Datos II - MONGODB

## Resumen

Este informe detalla el trabajo realizado para el proyecto de la asignatura Sistemas de Bases de Datos II en la Universidad Nacional Experimental de Guayana. El objetivo del proyecto fue trabajar con MongoDB para crear una base de datos de currículums vitae y realizar diversas operaciones con los documentos.

## Instalación de MongoDB

MongoDB es una base de datos basada en documentos que proporciona alto rendimiento, alta disponibilidad y fácil escalabilidad. MongoDB trabaja con documentos y colecciones en lugar de tablas y filas, lo que permite una gran flexibilidad y escalabilidad. Para este proyecto, MongoDB fue instalado en el sistema para poder trabajar con bases de datos basadas en documentos. La instalación se realizó siguiendo las instrucciones oficiales de MongoDB y se verificó su correcto funcionamiento antes de comenzar con el proyecto.

## Creación de la Base de Datos y la Colección

Una vez instalado MongoDB, se definió una base de datos y una colección para almacenar los documentos. La base de datos actúa como un contenedor para las colecciones, y cada colección actúa como un contenedor para los documentos. Cada documento corresponde a un currículum vitae y tiene un formato JSON. Se eligió este formato por su flexibilidad y facilidad de uso, así como por su compatibilidad nativa con MongoDB.

## Creación de los Currículums Vitae

Se elaboraron 10 currículums de diferentes personas en formato JSON. Cada currículum cuenta con los campos especificados en las instrucciones del proyecto, incluyendo un resumen, datos personales, educación, experiencia laboral, conocimientos técnicos e intereses personales. Se prestó especial atención a la estructura y coherencia de los datos para garantizar que cada currículum fuera único y representativo.

## Pasos Realizados

1. Definir una base de datos y una colección: Se creó una base de datos en MongoDB y dentro de ella, se realizó una colección donde se almacenaron los documentos (currículums).
2. Crear currículums en formato JSON: Cada grupo elaboró al menos 10 currículums de diferentes personas en formato JSON. Estos currículums formaron el total de documentos a importar en la base de datos.
3. Importar los currículums a MongoDB: Una vez que se crearon los currículums, se importaron a la colección que se había creado en MongoDB. Se utilizó la función de importación de MongoDB y se verificó que todos los documentos se importaran correctamente.

## Operaciones con los Documentos

Se realizaron varias operaciones con los documentos en la base de datos. Estas operaciones incluyen la creación de nuevos documentos, la eliminación de documentos existentes, la actualización de documentos y la búsqueda de documentos. Cada operación se realizó utilizando las funciones proporcionadas por MongoDB y se verificó su correcto funcionamiento. Además, se exploraron diferentes formas de realizar búsquedas y se experimentó con consultas complejas para demostrar la potencia y flexibilidad de MongoDB.
