# Containers

Ngix Container: PHP 7.4.30, MySQL 5.7 and latest phpMyAdmin\
WordPress Container: PHP 7.4.30, MySQL 5.7, latest phpMyAdmin and latest WordPress\
GRAV Container: https://github.com/getgrav/docker-grav\

# Useful Command

```
docker-compose start
docker-compose stop

docker-compose pause
docker-compose unpause

docker-compose up
docker-compose down
```
Description: Start, stop, pause, unpause, up and down a container.

```
docker ps
```
Description: Show running containers.\
Official Docs: https://docs.docker.com/engine/reference/commandline/ps/

```
docker exec -it <container name> /bin/sh
```
Description: SSH into a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/exec/

```
docker restart <container name>
```
Description: Restart a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/restart/

```
docker stats
```
Description: Restart a container.\
Official Docs: https://docs.docker.com/engine/reference/commandline/stats/

```
docker system df
```
Description: Display information about disk space being used by your containers.\
Official Docs: https://docs.docker.com/engine/reference/commandline/system_df/

```
docker system df
```
Description: Remove all unused images (dangling and unreferenced), containers, networks, and volumes.\
Official Docs: https://docs.docker.com/engine/reference/commandline/system_prune/

# The Ultimate Docker Cheat Sheet

https://dockerlabs.collabnix.com/docker/cheatsheet/
