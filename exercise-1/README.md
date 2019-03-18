# Exercise-1

```
docker run -d --name redis redis
docker build -t isen/nodeapp .
docker run -d --name nodeapp --link redis:redis -p 80:8080 isen/nodeapp
```

Requesting `http://<address>:80` shows the count.