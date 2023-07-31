# CRUD-Node.js y MySQL

La aplicación es un CRUD con su interface de Usuario, para ingresar información de Clientes donde se puede crear, listar, editar y borrar.


# Instalación del Proyecto Node.js

En este archivo README, proporcionaré instrucciones para instalar y ejecutar el proyecto Node.js. Asegúrate de tener Node.js instalado en tu máquina antes de seguir estas instrucciones.

## Requisitos previos
Asegúrate de tener instalados los siguientes requisitos previos en tu sistema:

Node.js: Asegúrate de tener Node.js instalado en tu máquina.

## Pasos para instalar y ejecutar el proyecto

1. Clonar el repositorio:

`git clone https://github.com/MentorSoftwareDev/crud-nodejs-mysql`

`cd crud-nodejs-mysql`

2. Instalar las dependencias del proyecto:

`npm install` 

Este comando instalará todas las dependencias necesarias para el proyecto Node.js definidas en el archivo package.json.

3. La aplicación tiene como Base de Datos MySQL, si lo tiene instalado en su computador inicie sesión y abra su cliente MySQL en caso de que utilice PHPMyAdmin ingrese a la pagina (En mi caso yo no tengo clave para el usuario root). **En caso de no tener instalado MySQL pasar al punto 4**

> Crear la base de datos como se especifica en la carpeta database -> archivo db.sql.

![Screenshot_2](https://github.com/MentorSoftwareDev/crud-nodejs-mysql/assets/140032849/a747973f-eeab-4e88-8fea-ca2da10bf0b0)

4. Ejecutar la aplicación:

`npm run dev` 

**En caso de NO tener instalado MySQL** al ejecutar el comando `npm run dev` en su editor de codigo debe aparecer como se indica en la imagen lo que significa que su aplicación fue bien instalada y se está ejecutando correctamente pero no le deja ver la pagina web hasta no tener MySQL en su computador. 

![Screenshot_3](https://github.com/MentorSoftwareDev/crud-nodejs-mysql/assets/140032849/ae169c39-f20d-414d-a7c9-ec971180646d)

Si abre localhost:3000 sale el siguiente error:

![Captura de pantalla 2023-07-30 221927](https://github.com/MentorSoftwareDev/crud-nodejs-mysql/assets/140032849/f176f356-443c-4376-8c04-54d9ce1a1ef2)

En el editor de codigo sale el siguiente error que significa no tiene conexión a la base de datos.


![Captura de pantalla 2023-07-30 221832](https://github.com/MentorSoftwareDev/crud-nodejs-mysql/assets/140032849/48be52c7-e630-497d-a596-3f9f85d3f18e)


> **Esto lo veremos en la clase de Docker Compose instalación de MySQL en un contenedor** si desea continuar se puede remitir a Coding Rooms lección 04. Conceptos avanzados de Docker: Docker Hub y Docker Compose y seguir el paso a paso del Ejercicio práctico de Docker Compose para Node.js



**En caso de SI tener instalado MySQL y haber seguido los pasos del punto 3** Con este comando, se iniciará la aplicación Node.js y estará disponible en http://localhost:3000. Puedes acceder a la aplicación desde su navegador web e interactuar con la aplicación.

![Captura de pantalla 2023-07-30 215152](https://github.com/MentorSoftwareDev/crud-nodejs-mysql/assets/140032849/063ab009-6ae1-45f1-bfd0-16ac4a99ad0c)


> **Si desea continuar con Docker Compose** se puede remitir a Coding Rooms lección 04. Conceptos avanzados de Docker: Docker Hub y Docker Compose y seguir el paso a paso del Ejercicio práctico de Docker Compose para Node.js


## Contribuciones
Si encuentras algún problema o quieres mejorar este proyecto, no dudes en hacer una solicitud de pull para que podamos revisar tus cambios y mejorar juntos este proyecto.

Espero que estas instrucciones te ayuden a instalar y ejecutar el proyecto Node.js Express. Si tienes alguna pregunta o problema, no dudes en contactarnos.

¡Gracias por utilizar este proyecto!
