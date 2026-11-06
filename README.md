# Gestor ADSO
Proyecto integrador SENA - ADSO. Aplicación web con PHP y Laravel (ABP).

## Versiones utilizadas (reales del equipo)
- PHP: ____          (php -v)
- Composer: ____     (composer -V)
- Laravel: ____      (php artisan --version)
- Git: ____          (git --version)
- MariaDB/MySQL: XAMPP, versión ____
- Sistema operativo: Windows ____

## Requisitos
XAMPP (Apache, MariaDB, PHP, phpMyAdmin), Composer, Git, VS Code.
PHP en PATH (C:\xampp\php). Extensiones: openssl, pdo_mysql,
mbstring, fileinfo, zip.

## Instalación
git clone <url-del-repositorio> gestor-adso
cd gestor-adso
composer install
copy .env.example .env
php artisan key:generate

## Variables de .env (sin valores sensibles)
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=gestor_adso
DB_USERNAME=<usuario-local>
DB_PASSWORD=<contrasena-local>

## Base de datos y migraciones
1. Iniciar MySQL en XAMPP.
2. Crear la base: gestor_adso (utf8mb4_unicode_ci).
3. php artisan config:clear
4. php artisan migrate

## Ejecutar el proyecto
php artisan serve
Abrir la URL que muestre la terminal (normalmente http://127.0.0.1:8000).

## Evidencias Semana 1
Ver documento de entrega individual (E1 a E14).
