# docker-commands

- Clean files

```
docker rm -vf $(docker ps -aq)
docker rmi -f $(docker images -aq)
docker volume prune -f
```


- Location of docker files on Mac

~/Library/Containers/com.docker.docker/Data

## ECR

aws ecr get-login-password --region region | docker login --username AWS --password-stdin aws_account_id.dkr.ecr.region.amazonaws.com

https://docs.aws.amazon.com/AmazonECR/latest/userguide/getting-started-cli.html

## Docker Windows

& 'C:\Program Files\Docker\Docker\DockerCli.exe' -SwitchDaemon

