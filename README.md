# Apache 2.2 Docker

[![](https://images.microbadger.com/badges/version/cytopia/apache-2.2.svg)](https://microbadger.com/images/cytopia/apache-2.2 "apache-2.2") [![](https://images.microbadger.com/badges/image/cytopia/apache-2.2.svg)](https://microbadger.com/images/cytopia/apache-2.2 "apache-2.2") [![](https://images.microbadger.com/badges/license/cytopia/apache-2.2.svg)](https://microbadger.com/images/cytopia/apache-2.2 "apache-2.2")

[![cytopia/apache-2.2](http://dockeri.co/image/cytopia/apache-2.2)](https://hub.docker.com/r/cytopia/apache-2.2/)

**Apache 2.2 | [Apache 2.4](https://github.com/cytopia/docker-apache-2.4)**

----

Apache 2.2 Docker on CentOS 6

This docker image is part of the **[devilbox](https://github.com/cytopia/devilbox)**

----

## Usage

```shell
$ docker run -i -t cytopia/apache-2.2
```

## Options


### Environmental variables

#### Required environmental variables

- None

#### Optional environmental variables

| Variable | Type | Description |
|----------|------|-------------|
| DEBUG_COMPOSE_ENTRYPOINT | bool | Show shell commands executed during start.<br/>Value: `0` or `1` |
| TIMEZONE | string | Set docker OS timezone.<br/>(Example: `Europe/Berlin`) |
| CUSTOM_HTTPD_CONF_DIR | string | Specify a directory inside the docker where Apache should look for additional config files (`*.conf`).<br/><br/>Make sure to mount this directory from your host into the docker. |


### Default mount points

| Docker | Description |
|--------|-------------|
| /var/log/httpd | Apache log dir |


### Default ports

| Docker | Description |
|--------|-------------|
| 80     | Apache listening Port |
