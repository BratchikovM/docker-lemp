# docker-lemp

Для сборки нужно выполнять команду docker-compose up -d.

### В файле docker-compose.yml описанно откуда экспортируется и куда импортируется.

## Значения папок.

### Hosts
Предназначенна для конфигурационных файлов nginx
### Logs
Сюда пишутся все логи
### Mysql
Тут файлы самой бд
### www
Эта папка предназначенна для проектов, они импортируются в /var/www
