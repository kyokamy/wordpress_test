# docker command test

`docker run --name wordpress -d -p 80:80 wordpress`


```shell
docker run --name mysql -e MYSQL_ROOT_PASSWORD=kyokamy -e MYSQL_DATABASE=wordpress -p 3306:3306 -d mysql


Get ip localhost
docker container inspect -f '{{.Name}} - {{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' $(docker ps -q) # docker-ip

# Docker-compose
docker-compose up -d #lancer en background
docker-compose up -it #mode interactif
docker-compose stop
```


