Запускается через Docker

В консоле выполнить команду docker-compose up

Перейти по адресу - http://localhost/ 

Для вывода названия и описания для трейлеров 
Зайти в консоль fpm в папку с преоктм /var/www/app
И выполнить следующие команды:
php bin/console  orm:schema-tool:create
php bin/console  orm:schema-tool:update
php bin/console fetch:trailers
