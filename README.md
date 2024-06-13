## Project (Nginx - Wordpress (php) - MySQL

This project run containers with nginx, wordpress(php) and mysql through the above below

### Commands to run

> Up container(s) docker

```bash
sudo docker-compose up -d
```

> Remove container(s) docker

```bash
sudo docker-compose down
```

> Prune volume container(s) docker (if necessary to remove volume to re-install the mysql)

```bash
sudo docker volume rm CONTAINERNAME-data
```
