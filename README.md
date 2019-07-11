## About this project ##


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
