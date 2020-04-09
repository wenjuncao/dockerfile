redis：http://download.redis.io/releases/redis-5.0.8.tar.gz

## redis.conf必须放在根目录，否则copy时，会找不到该文件

登录： docker login

拉取： docker push hesens/redis:latest

启动命令：docker run --name redis -d -p 6379:6379 hesens/redis:latest
