# Prueba, desarrollo de una tienda minimalista

### Pre-requisitos 📋

- PHP >= 7.4 
- sqlite 3
- Composer versión 2. 
- Extensión pdo_sqlite habilitada.
- Extensión soap habilitada.
- node >= 14.15
- npm

### Instalación 🔧

1. Clonar el repositorio en el directorio del servidor web

2. Instalar paquetes de composer ejecutando `composer install`.

3. Instalar paquetes de node `npm install && npm run prod`

4. Copiar el archivo `.env.example` incluido en uno de nombre `.env` y completar variables de pasarela de pagos

5. crear un archivo vacio en la ruta database `database/database.sqlite` 

6. ejecutar comando `php artisan migrate:fresh --seed` 

7. Ejecutar pruebas `php artisan test`

8. Añadir al crontab: `* * * * * php /raiz-del-proyecto/artisan schedule:run >> /dev/null 2>&1`

9. Acceder al sitio.

## Credeniales del dueño de la tienda. 🔑

Email|Password|
 ------ | ------ |
admin@gmail.com|password

------------------------
