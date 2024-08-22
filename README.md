<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Acerca de Este Proyecto

Este proyecto es una implementación técnica creada para mostrar habilidades en el uso de **PHP** y **Laravel**. El objetivo principal es demostrar la capacidad de crear un sistema básico de autenticación y gestión de datos con las siguientes características:

- **Sistema de Login**: Permite a los usuarios registrarse y autenticar sus credenciales.
- **CRUD de Productos**: Ofrece funcionalidades para:
  - **Crear**: Agregar nuevos productos.
  - **Leer**: Visualizar la lista de productos existentes.
  - **Actualizar**: Editar detalles de productos.
  - **Eliminar**: Eliminar productos de la base de datos.
  
El sistema está conectado a una base de datos MySQL, y el proyecto puede servir como base para desarrollar aplicaciones reales, como sistemas de gestión para el registro de personas o sistemas de partes.

## Tecnologías Utilizadas

- **PHP**: Lenguaje de programación en el backend.
- **Laravel**: Framework PHP para el desarrollo del proyecto.
- **MySQL**: Base de datos relacional utilizada para el almacenamiento de datos.
- **Composer**: Herramienta de gestión de dependencias para PHP.

## Instalación y Configuración

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/JulioBendz/login_crud_mxpeople_php_laravel.git

2. **Navega al directorio del proyecto:**

   ```bash
   cd login_crud_mxpeople_php_laravel

3. **Instala las dependencias del proyecto:**

   ```bash
   composer install

4. **Configura el archivo .env:**

    Copia el archivo de ejemplo y renómbralo:

   ```bash
   cp .env.example .env

   Luego, abre el archivo .env y configura los detalles de conexión a la base de datos y otras variables de entorno según tu entorno local.

5. **Genera la clave de aplicación de Laravel:**

   ```bash
   php artisan key:generate

6. **Ejecuta las migraciones para crear las tablas en la base de datos:**

   ```bash
   php artisan migrate

7. **Inicia el servidor de desarrollo:**

   ```bash
   php artisan serve

Puedes acceder a la aplicación en http://localhost:8000



Este README proporciona una guía clara y completa para la instalación y configuración del proyecto. Puedes ajustarlo según lo necesites. ¡Buena suerte con tu proyecto!