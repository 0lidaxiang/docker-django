# docker-django
Create an docker ENV with django and mysql


## How Run
docker-compose -f mysql-docker-compose.yml start

docker-compose -f django-docker-compose.yml up



## docker-compose 常用命令
指定yml文件和项目名称
docker-compose -f docker-compose.yml -p dongodng up -d

复制代码#进行所需的服务镜像构建
docker-compose build

复制代码#停掉服务，删除容器，不删除镜像
docker-compose down

复制代码#打印出详细的config文件
docker-compose config

复制代码#创建容器但是不运行
docker-compose create


接受服务之间的互动事件，如进行健康检查等
docker-compose events

查看服务状态
docker-compose ps

重启服务

docker-compose restart/start/stop [服务名称]