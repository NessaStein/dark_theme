---
layout: post
title: "docker��������"
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

docker�ͻ���/�����

 -Hѡ��
 
 DOCK_HOST��������
 
 ----------------------------------------------------------------------------------------------------
 
dockerfile:��

FROM

MAINTAINER

RUN

EXPOSE

dockerfile:��

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

