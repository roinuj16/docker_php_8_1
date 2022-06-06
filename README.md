# .docker
Here has all docker configurations like images, docker-compose and entrypoint used for some containers like MySQL and Redis.
Also, has a file .env-example with initial setting, fell free to update that file with your settings.

# .make
Into the folder .make has all makefiles used to run commands inside the containers.

#Makefile
This file is the entrypoint of all makes configurations


# remember
Para testar o container do redis
```
docker exec -it docker_redis_1 redis-cli -a 'secret_redis_password'

> ping
```
