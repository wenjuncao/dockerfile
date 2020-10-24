redis：http://download.redis.io/releases/redis-5.0.8.tar.gz

登录： docker login

拉取： docker pull hesens/redis:latest

启动命令：docker run --name redis -d -p 6379:6379 hesens/redis:latest
