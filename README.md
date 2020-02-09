# This is a dummy nodejs helloworld container 

## 1. Starting nodejs container

### 1.1 via docker cli

```
docker run -it -p 8080:8080 emedeiros/nodejs-helloworld-docker
```

### 1.2 via docker-compose

```
docker-compose up -d
```

## 2. How to access the deployment

* URL: http://your.ip:8080
