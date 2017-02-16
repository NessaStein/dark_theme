---
layout: post
title: "docker常用命令"
date: <2017-02-16 14:25:40>
tags: docker
description: docker
share: 
---

docker run -i -t ubuntu /bin/bash

docker ps

docker ps -a

docker ps -l

docker attatch

----------------------------------------------------------------------------------------------------
docker run -d --name dc1 -i -t ubuntu /bin/bash

docker exec web nginx

docker logs

docker run -p 80 --name web -i -t ubuntu /bin/bash

----------------------------------------------------------------------------------------------------
docker images

docker images --no-trunc

docker images -q

docker inspect

docker rmi


----------------------------------------------------------------------------------------------------

docker search

docker pull

docker push

----------------------------------------------------------------------------------------------------

docker commit

docker build

----------------------------------------------------------------------------------------------------

docker客户端/服务端

 -H选项
 
 DOCK_HOST环境变量
 
 ----------------------------------------------------------------------------------------------------
 
dockerfile:上

FROM

MAINTAINER

RUN

EXPOSE

dockerfile:下

CMD

ENTERYPOINT

ADD

COPY

VOLUME

WORKDIR

ENV

ONBUILD

USER

----------------------------------------------------------------------------------------------------

