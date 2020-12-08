# DelilahResto
**Proyecto Delilah Restó**

API para pedidos de comida deliciosa. Como cliente podras registrarle, ver el listado de nuestros productos y realizar una orden. Los administradores del restaurante tienen la posibilidad de recibir pedidos y actualizarlos.

## Requisitos

### Instalar NodeJS
Nodejs es un entorno JavaScript que nos permite ejecutar en el servidor, de manera asíncrona, con una arquitectura orientada a eventos y basado en el motor V8 de Google.
  - [Descargar Nodejs](https://nodejs.org/en/download/)

### Instalar XAMPP

XAMPP es una distribución de Apache completamente gratuita y fácil de instalar que contiene MariaDB, PHP y Perl. 
  - [Descargar XAMPP](https://www.apachefriends.org/es/download.html)

### Instalar Postman
Es una herramienta que principalmente nos permite crear peticiones sobre APIs de una forma muy sencilla y poder, de esta manera, probar las APIs
  - [Descargar Postman](https://www.postman.com/product/api-client/)

## Despliegue
  **1) Clonar el proyecto**

* Clonar el repositorio desde github accediendo al link: [DelilahResto](https://github.com/seba365/DelilahResto)
* Desde la consola ejecutar el comando:
```
git clone https://github.com/seba365/DelilahResto.git
```

**2) Instalar dependencias**
```
npm install
```

**3) Creando base de datos**
* Abrir XAMPP e iniciar los servicios de **Apache** y **MYSQL**
* Para abrir MYSQL presionar el botón **Admin** ó acceder a **[phpmyadmin](http://localhost/phpmyadmin/)**.
* Generar la base de datos **delilahresto**, dentro del panle de control de la base de datos ejecutar y/o importar el archivo que se encuentra en: **/scriptsDB/deliahrestoDB.sql

**4) Iniciar el servidor**

```
npm run start
```
ó
```
node ./src/index.js
```


## Documentación de la API

Abrir el archivo **spec.yml* y copiar su contenido en [Swagger](https://editor.swagger.io/) o importar el mismo desde las opciones.

A continuación, se muestra un breve resumen de todos los endpoints disponibles.

**URL: http://localhost:4001/**


## Testing
Testear los endpoints provistos desde postman para poder hacer uso de la API y base de datos generadas

## Recursos y tecnologías utilizadas

## Autor