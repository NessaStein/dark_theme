---
layout: post
title: "docker command tips"
date: <2017-02-16 14:25:40>
tags: docker
description: docker
share: 
---

{% highlight bash %}
docker run -i -t ubuntu /bin/bash

docker ps

docker ps -a

docker ps -l

docker attatch
{% endhighlight bash %}

{% highlight bash %}
docker run -d --name dc1 -i -t ubuntu /bin/bash

docker exec web nginx

docker logs

docker run -p 80 --name web -i -t ubuntu /bin/bash
{% endhighlight bash %}


{% highlight bash %}
docker images

docker images --no-trunc

docker images -q

docker inspect

docker rmi

{% endhighlight bash %}

{% highlight bash %}
docker search

docker pull

docker push
{% endhighlight bash %}

----------------------------------------------------------------------------------------------------

docker commit

docker build

----------------------------------------------------------------------------------------------------

dockerfile: 1

FROM

MAINTAINER

RUN

EXPOSE

dockerfile: 2

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
