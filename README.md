# mlops-docker

# dockerfile
vim Dockerfile
информацию в файле посмотреть удалось

# docker build -t nginx-php-fpm:php80 . # PHP8
изначально была ошибка, пришлось устроить танцы с бубном и почитать стаковерфлов

# образ не получилось создать (пусто)
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES

# запустить также не удалось, пока не знаю почему:
(base) MacBook-Pro-ivan:docker ivan$ docker run -d -p 80:80 nginx-php-fpm:php80
Unable to find image 'nginx-php-fpm:php80' locally
docker: Error response from daemon: pull access denied for nginx-php-fpm, repository does not exist or may require 'docker login': denied: requested access to the resource is denied.
See 'docker run --help'.

# далее
после перебора нескольких команд из стаковерфлов, докер файл вроде как собрался, но очень отлично от того, что в видео (лог командной строки приложил в репозиторий)

# (base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE                 COMMAND       CREATED          STATUS          PORTS                NAMES
858aafec5d18   nginx-php-fpm:php80   "/start.sh"   28 seconds ago   Up 26 seconds   0.0.0.0:80->80/tcp   quirky_noyce

# netstat -ntlp
не показал ничего, также по порту http://192.168.56.103/ тоже ничего нет
Но зато по порту 0.0.0.0:80 вылезает заплатка:

Congratulations!
You have successfully deployed a docker container running our NGINX with PHP-FPM 8.x image

NGINX: v1.19.10-1~buster
PHP-FPM: v8.0.30
LOADED CONFIG: /etc/php/8.0/fpm/php.ini
WEB ROOT: /usr/share/nginx/html
HOSTNAME: 858aafec5d18

Thank you for using wyveo.com

# ИТОГ
Но я все равно не понимаю как выполнять домашнее задание!

Необходимо сделать dockerfile для получения рабочего контейнера.
1. В качестве основы, берём образ continuumio/miniconda3:latest
2. Добавляем и делаем рабочей папкой /app
3. Создаём простой sh файл с названием 1.sh, который должен выдавать надпись “Hello Netology”.
4. Надо скопировать этот файл внутрь контейнера и выдать ему права на исполнение.
5. Запустить установку пакетов python mlflow boto3 pymysql.
6. В конце запустить на вывод файл 1.sh.
7. После чего собрать через docker build контейнер с тегом netology-ml:netology-ml
