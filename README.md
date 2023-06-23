<!-- <p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p> -->

![Logo Innclod](public/images/logo_care_security.png)
# Diagrama Entidad Relación
![Texto alternativo](public/images/care_security_db.png)

# 1.¿Cuáles son los requisitos del servidor para activar el script?
## Respuesta: Para instalar el Script los requisitos mínimos del servidor son:

- [Php version 8.2+]
- [MySQL 10.4+-MariaDB]
- [mod_rewrite Apache]
- [BCMath PHP Extension]
- [Ctype PHP Extension].
- [Mbstring PHP Extension]
- [PDO PHP Extension]
- [Tokenizer PHP Extension]
- [Session PHP Extension]

En la mayoría de los servidores, estas extensiones están activadas por defecto, pero debe consultar a su proveedor de alojamiento.
# 2.¿Cómo instalar el script?
## Respuesta: Para instalar el script siga los siguientes pasos.

- Extraiga el archivo .zip descargado en su PC o el código directamente desde GitHub.
- Cargue el archivo .zip en el directorio public_html de su servidor o en cualquier otro directorio en el que desee ejecutar.
- Extraiga el archivo zip en ese directorio.
- Cree una nueva base de datos a partir de la base de datos MySQL de su servidor.
- Cree un usuario DB para la base de datos y vincule esa base de datos al usuario DB.
- Configure las variables de entorno a partir del archivo .env-example.
- Escribe por la consola el comando `php artisan migrate fresh --seed`.
- Escribe el comando en una nueva consola `composer install`.
- Escribe el comando en una nueva consola `npm install`.
- Escribe el comando en una nueva consola `npm run dev`.
- Pulse en la URL amigable generada por el comando `php artisan serve`.
