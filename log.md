# Mac

## Redis

__Config file:__

/opt/homebrew/etc/redis.conf

__start redis-server__

> brew services start redis

__stop redis-server__

> brew services stop redis

## RabbitMQ

__info__

> brew info rabbitmq

__start background__

> ```bash
> brew services start rabbitmq
> ```

__stop service__

```bash
brew services stop rabbitmq
```

Username: hang 

Password: Y

## Nacos

__Start Service:__

> cd /Users/hang/develop/nacos/nacos/bin

> sh startup.sh -m standalone

之后在浏览器访问http://localhost:8848/nacos 即可，默认的登录账号和密码都是nacos



# Docker

```shell
# 启动docker服务
systemctl start docker 

# 停止docker服务
systemctl stop docker

# 重启docker服务
systemctl restart docker
```