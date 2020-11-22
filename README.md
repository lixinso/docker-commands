# docker-commands

- Clean files

```
docker rm -vf $(docker ps -aq)
docker rmi -f $(docker images -aq)
docker volume prune -f
```


- Location of docker files on Mac

~/Library/Containers/com.docker.docker/Data
