# Crud-Compose

API REST desarrollada en PHP para gestionar una agenda de contactos.  
Permite crear, consultar, actualizar y eliminar contactos de forma sencilla mediante peticiones HTTP.

---

## Funcionalidades

- Crear contactos
- Listar contactos
- Actualizar información de un contacto
- Eliminar contactos
- API documentada con ejemplos de uso

---

## Requisitos previos

Antes de instalar el proyecto debes tener instalado:

- PHP >= 8.0  
- Composer  
- MySQL o MariaDB  
- Servidor web Apache o Nginx  
- Git  

---

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/proyecto.git
```

2. Acceder al directorio del proyecto:

```bash
cd proyecto
```

3. Instalar las dependencias del proyecto:

```bash
composer install
```

---

## Uso

### Ejemplo de petición GET
```bash
curl http://localhost:8000/api/contactos
```

---

## Estructura del proyecto

```text
/Crud-Compose
├── Caddyfile
├── README.md
├── docker-compose.yml
├── php
│   └── Dockerfile
└── src
    ├── bd
    │   ├── bd.php
    │   └── clientes.php
    ├── classes
    │   ├── BD.html
    │   └── ClientesBD.html
    ├── clientes
    │   ├── borrar.php
    │   ├── editar.php
    │   ├── nuevo.php
    │   └── seleccionar.php
    ├── config.php
    ├── css
    │   ├── base.css
    │   ├── normalize.css
    │   └── template.css
    ├── files
    │   ├── bd-bd.html
    │   ├── bd-clientes.html
    │   ├── clientes-borrar.html
    │   ├── clientes-editar.html
    │   ├── clientes-nuevo.html
    │   ├── clientes-seleccionar.html
    │   ├── config.html
    │   └── index.html
    ├── graphs
    │   └── classes.html
    ├── index.html
    ├── index.php
    ├── indices
    │   └── files.html
    ├── js
    │   ├── search.js
    │   ├── searchIndex.js
    │   └── template.js
    ├── namespaces
    │   └── default.html
    ├── packages
    │   ├── Application.html
    │   ├── ProyectoDemo.html
    │   └── default.html
    └── reports
        ├── deprecated.html
        ├── errors.html
        └── markers.html
```

## Acceso y Credenciales
 
Para acceder al proyecto, configurar las variables de entorno en el archivo `docker-compose.yml`: 

```yml 
MYSQL_ROOT_PASSWORD: dwes
MYSQL_DATABASE: demo
MYSQL_USER: dwes
MYSQL_PASSWORD: dwes
```
## Contribución

1. Hacer un fork del repositorio.

2. Crear una nueva rama para la funcionalidad o corrección:

```bash
git checkout -b nueva-funcionalidad
```

3. Realizar los cambios necesarios.

4. Hacer commit de los cambios:

```bash
git commit -m "Añadida nueva funcionalidad"
```

5. Subir la rama al repositorio y crear un Pull Request.

## Menciones

@David Sabater 
@IgFormacion/2ºDAW 
