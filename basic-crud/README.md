Para ejecutar el proyecto solo requiere de tener docker instalado

desde la ruta del proyecto en terminal o cmd ejecutar los siguientes comandos en secuencia

docker-compose build

docker-compose up -d

docker-compose exec php php /var/www/artisan migrate

docker-compose exec php php /var/www/artisan route:cache

Y acceder a traves de la url: "http://localhost:8000/users"