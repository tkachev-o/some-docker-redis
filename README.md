# some-docker-redis
A someone docker-compose example for redis.

```
> docker-compose up -d

Creating network "some-docker-redis_default" with the default driver
Creating some-docker-redis_redis_1 ... done
```
Connect to redis-cli 
```
> docker -it some-docker-redis_redis_1 redis-cli
```

Using the SET ...
```
127.0.0.1:6379> SET hello world!
OK
```
and GET commands:
```
127.0.0.1:6379> GET hello
world!
```
