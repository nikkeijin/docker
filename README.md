# Containers

Ngix Container: PHP 7.4.30, MySQL 5.7 and latest phpMyAdmin\
WordPress Container: PHP 7.4.30, MySQL 5.7, latest phpMyAdmin and latest WordPress\
GRAV Container: https://github.com/getgrav/docker-grav/

# Useful Command


> Start, stop, pause, unpause, up and down a container.
```
docker-compose start -d
docker-compose stop -d

docker-compose pause -d
docker-compose unpause -d

docker-compose up -d
docker-compose down -d
```


> Show running containers.\
Official Docs: https://docs.docker.com/engine/reference/commandline/ps/
```
docker ps
```


> SSH into a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/exec/
```
docker exec -it <container name> /bin/sh
```


> Restart a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/restart/
```
docker restart <container name>
```


> Restart a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/stats/
```
docker stats
```


> Display information about disk space being used by your containers.\
Official Docs: https://docs.docker.com/engine/reference/commandline/system_df/
```
docker system df
```


> Remove all unused images (dangling and unreferenced), containers, networks, and volumes.\
Official Docs: https://docs.docker.com/engine/reference/commandline/system_prune/
```
docker system df
```


# The Ultimate Docker Cheat Sheet
https://dockerlabs.collabnix.com/docker/cheatsheet/
