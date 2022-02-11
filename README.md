# API de películas

## Objetivo:

Utilizar una base de datos relacional, para crear una API de películas.

Se crea endpoints GET, POST y DELETE.

## Tecnologías usadas

<p align="left">
 <!–– JAVASCRIPT ––>
<a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" data-bs-toggle="tooltip" title="JavaScript"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javaScript"/> </a>
<!-- MYSQL -->
<a href="https://www.mysql.com/" alt="Express Js" ><img src= "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /></a>
  </p>

### Instalación de la base de datos relacional *movies-db.sql*:

- Debe tener instalado un gestor de base de datos, por ejemplo: MYSQL Workbench (https://www.mysql.com/products/workbench/) o Heidi db (https://www.heidisql.com/).

- Desde su gestor de base de datos, correr el script que se encuentra en:

   `Creacion-api-movies/src/database/script/movies-db.sql`

- Levantar el servidor para la base de datos desde su gestor de base de datos.

### ¿Cómo instalar el proyecto?

#### Desde la terminal:

- Clonar el proyecto:
````
git clone https://github.com/LorenaCoheneBaez/Creacion-api-movies.git
````

### Endpoints de la Api:
***
*Películas (GET):*
- Listado "http://localhost:3001/api/movies"

- Detalle de película "http://localhost:3001/api/detail/:id"

*Películas (POST):*
- Agregar película "http://localhost:3001/api/create"

*Películas (DELETE):*
- Eliminar película "http://localhost:3001/api/delete/:id"

***
*Géneros (GET):*

- Listado de géneros "http://localhost:3001/api/genres"

- Detalle de géneros "http://localhost:3001/api/genres/detail/:id"


***
*Actores (GET)*

- Listado de actores "http://localhost:3001/api/actors"

- Detalle de actores "http://localhost:3001/api/actors/detail/:id"


### ¿Cómo instalar el proyecto?

#### Desde la terminal:

- Clonar el proyecto:

````
git clone https://github.com/LorenaCoheneBaez/Creacion-api-movies.git
````

- Ingresar a la carpeta del proyecto:

````
 cd Creacion-api-movies
````

- Para instalar las dependencias correr: 

````
 npm install
````

### Levantar el servidor del proyecto: 

````
 npm test
````
