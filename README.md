## Containers

Apache Container: PHP 8.1.0, Latest MySQL and latest phpMyAdmin\
Ngix Container: PHP 7.4.30, MySQL 5.7 and latest phpMyAdmin\
WordPress Container: PHP 7.4.30, MySQL 5.7, latest phpMyAdmin and latest WordPress\
GRAV Container: https://github.com/getgrav/docker-grav/

## Useful Command

### Start, stop, pause, unpause, up and down a container
```bash
docker-compose start -d
docker-compose stop -d

docker-compose pause -d
docker-compose unpause -d

docker-compose up -d
docker-compose down -d
```

### Show running containers
Official Docs: https://docs.docker.com/engine/reference/commandline/ps/
```bash
docker ps
```

### SSH into a container
Official Docs: https://docs.docker.com/engine/reference/commandline/exec/
```bash
docker exec -it <container name> /bin/sh
```

### Restart a container
Official Docs: https://docs.docker.com/engine/reference/commandline/restart/
```bash
docker restart <container name>
```

### Restart a container
Official Docs: https://docs.docker.com/engine/reference/commandline/stats/
```bash
docker stats
```

### Display information about disk space being used by your containers
Official Docs: https://docs.docker.com/engine/reference/commandline/system_df/
```bash
docker system df
```

### Remove all unused images (dangling and unreferenced), containers, networks, and volumes.
Official Docs: https://docs.docker.com/engine/reference/commandline/system_prune/
```bash
docker system df
```

## The Ultimate Docker Cheat Sheet
https://dockerlabs.collabnix.com/docker/cheatsheet/
