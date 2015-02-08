# Dockerfile for Reverse Proxy Server with Nginx

## Usage

BUILD

```Shell
$ docker build -t susieyy/nginx-reverse-proxy
```

RUN

```Shell
$ docker run -d --name nginx-reverse-proxy --link unicorn:app -p 80:80 susieyy/nginx-reverse-proxy
```
