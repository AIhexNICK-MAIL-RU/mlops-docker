# mlops-docker

# dockerfile
vim Dockerfile
информацию в файле посмотреть удалось

# docker build -t nginx-php-fpm:php80 . # PHP8


# образ не получлось создать (пусто)
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES

# запустить также не удалось, пока не знаю почему:
(base) MacBook-Pro-ivan:docker ivan$ docker run -d -p 80:80 nginx-php-fpm:php80
Unable to find image 'nginx-php-fpm:php80' locally
docker: Error response from daemon: pull access denied for nginx-php-fpm, repository does not exist or may require 'docker login': denied: requested access to the resource is denied.
See 'docker run --help'.

