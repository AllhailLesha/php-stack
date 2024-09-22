1. Меняем название бд в mysql.env 
2. Меняем названия контейнеров в docker-compose.yml
3. Меняем название рутовой папки в nginx.conf
4. В dockerfile php меняем название рабочей директории
5. в dockerfile composer меняем название рабочей директории
6. Для запука пишем docker compose up -d
7. Инициализируем композер командой docker-compose run --rm php composer init   
8. Чтобы поставить какой-то пакет из корневой директории проекта запускаем
   docker-compose run --rm php composer require {$имяПакета}
