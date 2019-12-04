#### PULL镜像
docker pull mycongrats/hadoop2.7
#### 启动容器
docker run --name node1 -dt mycongrats/hadoop2.7 /usr/sbin/init
#### 登录容器
docker exec -ti node1 bash
#### 退出容器
exit
