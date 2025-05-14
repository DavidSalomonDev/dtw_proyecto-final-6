<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>
<hr />


# Proyecto Final- DTW135 | 06. Registro de Libros
## Integrantes del grupo de trabajo

- David Salomón Martínez Valladares - MV12013
- Luis Eduardo Guiroa Linares - GL12016
- Erick Giovanni Monroy López - ML22048
- Román Edgardo Mendoza Arias - MA22054
- David Alfredo Parada Mendoza - PM13119

## Descripción
Esta aplicación, desarrollada con Laravel 12, permite gestionar un registro de libros mediante operaciones CRUD (Crear, Leer, Actualizar, Eliminar). La aplicación permite mantener un inventario detallado de libros, incluyendo información relevante como título, autor, género, año de publicación y estado (disponible o prestado).

## Funcionalidades

- Crear: Permite añadir nuevos libros al registro, especificando todos los detalles necesarios.
- Leer: Permite visualizar la información detallada de cada libro registrado.
- Actualizar: Permite modificar la información de los libros existentes.
- Eliminar: Permite eliminar libros del registro.
- Listado y filtrado: Permite visualizar todos los libros registrados y filtrarlos por diferentes criterios (por ejemplo, género, autor o estado).

## Instrucciones de instalación

A continuación se detallan los pasos para instalar y ejecutar el proyecto desde cero en tu entorno local:

1. Clonar el repositorio

```bash
git clone https://github.com/DavidSalomonDev/dtw_proyecto-final-6.git
cd dtw_proyecto-final-6
```


2. Instalar dependencias de PHP con Composer

Asegúrate de tener Composer instalado. Luego ejecuta:

```bash
composer install
```

3. Instalar dependencias de JavaScript con npm

Asegúrate de tener Node.js y npm instalados. Luego ejecuta:

```bash
npm install
```

4. Configurar el archivo de entorno
   
Luego, abre el archivo `.env` y ajusta los valores de la base de datos y otras variables necesarias.

5. Configuración de la base de datos (XAMPP y MySQL)

Este proyecto utiliza XAMPP y MySQL para la gestión de la base de datos. Por defecto, se utilizan los siguientes valores en el archivo .env:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=libreria
DB_USERNAME=root
DB_PASSWORD=
```

Por lo tanto, debes crear una base de datos llamada laravel en tu servidor MySQL local (puedes hacerlo desde phpMyAdmin o la consola de MySQL). No es necesario establecer contraseña para el usuario root si usas la configuración por defecto de XAMPP.

6. Generar la clave de la aplicación

Ejecuta el siguiente comando:

```bash
php artisan key:generate
```

7. Ejecutar migraciones

Para crear las tablas necesarias en la base de datos, ejecuta:

```bash
php artisan migrate
```

8. Cargar datos de ejemplo

El repositorio incluye seeders para poblar la base de datos con usuarios de ejemplo. Ejecuta

```bash
php artisan db:seed
```
   

9. Levantar el servidor de desarrollo

Finalmente, inicia el servidor local de Laravel:

```bash
php artisan serve
```

El proyecto estará disponible en http://localhost:8000.

## Uso de la aplicación

1. Ingresa con las credenciales de admin
```
usuario: admin
contraseña: 1234
```
