# docker-reverse-proxy

An example usage of nginx as reverse proxy with micro-service web server.

Tested on Docker 1.11.2-beta15 (build: 4450)

## How to run

run a command

```
docker-compose up
```

then visit micro-service sites at

* web1 `your-ip-address/web1/`
* web2 `your-ip-address/web2/`
* php 5.2 `your-ip-address/php52/`
* php 7.0 `your-ip-address/php70/`
