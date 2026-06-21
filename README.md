<div align="center">

# Proyecto CRUD De Clientes + Elaborado Por: Alejandro De Mendoza

</div>

---

Este proyecto es una implementación de un sistema CRUD (Crear, Leer, Actualizar, Eliminar) de clientes utilizando PHP y MySQL, con una interfaz web sencilla en HTML y CSS. Los datos de los clientes son almacenados en una base de datos MySQL y pueden ser gestionados mediante una API REST.

## Tecnologías utilizadas

- **PHP**: Para manejar la lógica del backend.
- **MySQL**: Para la gestión de la base de datos.
- **HTML/CSS**: Para la interfaz web.
- **Postman**: Para probar las APIs.

## Requisitos previos

- **XAMPP** o un servidor local con PHP y MySQL.
- **Postman** para probar las APIs.

## Instalación

1. **Clona este repositorio en tu máquina local**:
   
   Si no lo has hecho ya, puedes clonar el repositorio usando Git:

   ```En el terminal o en gitbash
   git clone https://github.com/TuUsuario/ProjectAlejandroDeMendoza.git
   
2. Mueve el proyecto a la carpeta htdocs de XAMPP:

- Coloca el proyecto dentro de la carpeta htdocs de tu instalación de XAMPP: C:\xampp\htdocs\"La ubicacion donde efectuaste la clonación del proyecto"

* Ejemplo:
C:\xampp\htdocs\api_backend_dev\API-REST\API.REST.PHP\api-rest

3. Inicia los servicios de XAMPP:

- Abre el panel de control de XAMPP.
- Inicia Apache y MySQL.

4. Configura la base de datos:

- Abre phpMyAdmin en tu navegador (http://localhost/phpmyadmin).
- Descarga la base de datos llamada code_pills.
- Importa las tablas o la estructura necesarias en .sql.
  
5. Accede al proyecto en el navegador:
- Abre tu navegador y accede a la dirección: http://localhost/"La ubicacion donde efectuaste la clonación del proyecto"/ProjectAlejandroDeMendoza

* Ejemplo: http://localhost/api_backend_dev/API-REST/API.REST.PHP/api-rest/

- La imagen en tu navegador se muestra de la siguiente manera:

![Imagen Web 1](https://github.com/AxentDev/API-REST-ProjectAlejandroDeMendoza/blob/master/API-REST/API.REST.PHP/api-rest/ImagenWeb1.png)
![Imagen Web 2](https://github.com/AxentDev/API-REST-ProjectAlejandroDeMendoza/blob/master/API-REST/API.REST.PHP/api-rest/ImagenWeb2.png)

## Uso

Interfaz web

1. La interfaz permite añadir, editar, ver y eliminar clientes.
2. Los campos requeridos son: Correo electrónico, Nombre, Ciudad y Teléfono.
3. Puedes ver todos los clientes haciendo clic en el botón "Mostrar Clientes".
4. Los clientes pueden ser eliminados o editados directamente desde la lista.

## API REST

- POST /create_client.php: Crea un nuevo cliente.
- GET /get_all_client.php: Obtiene todos los clientes.
- PUT /update_client.php?id={id}: Actualiza un cliente existente.
- DELETE /delete_client.php?id={id}: Elimina un cliente.

## Contribución: 

- Si deseas contribuir a este proyecto, haz un fork del repositorio, crea una nueva rama y envía tus cambios con un pull request.

---

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
