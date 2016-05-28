# laravel-clase1

## Recursos
- styde.net

## Instalacion de laravel 

composer create-project laravel/laravel your-project-name

## Carpetas de laravel

- public: aqui van los recursos estaticos. img, js, css.
- resources/views: las vistas de la aplicacion.
- app: aqui van los modelos.
- app/http: los controladores.

## recursos de laravel

- packalyst.com

## Migraciones

- `php artisa migrate:install` 	-> instala las migraciones.
- `php artisa migrate` 			-> realiza las migraciones.
- `php artisa migrate:rollback` -> regresa a la migracion anterior.
- `php artisa migrate:refresh` 	-> hace un rollback y realiza las migraciones.

Al hacer un cambio de uno de los campos (cambiar tipo de dato o nombre), hacer lo siguiente:
```bash
composer dump-autoload
php artisan migrate:refresh
```