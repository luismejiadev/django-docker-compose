## About this project ##

This project use Docker-compose to start 4 containers:

* Django-App
* Postgresql
* RabbitMQ
* Redis 

## Start Containers ##

```
sudo docker-compose up

```

## Setup database ##

```
sh ./reset_db.sh
```

## Watch RabbitMQ Queues ##

```
sudo docker exec -it app-rabbitmq sh /var/lib/rabbitmq/watch-rabbitmq.sh
```
