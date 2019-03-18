# Exercise 5

To start the service with only one worker:

```
docker-compose up -d
```

To start the service with 4 services:

```
docker-compose up -d --scale worker=4
```