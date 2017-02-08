---
layout: post
title: "Forcing ssl in jekyll _config.yml"
date: 2017-02-08 16:25:06
tags: jekyll
description: force enable ssl(solved cannot mixed load problem)
---

## 

put this code in your _config.yml

YAML:
{% highlight yaml %}
url: https://username.github.io
enforce_ssl: username.github.io
{% endhighlight yaml %}
