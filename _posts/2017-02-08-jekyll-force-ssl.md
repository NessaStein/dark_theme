---
layout: post
title: "Code snippets"
date: 2016-10-01 16:25:06
tags: code jekyll
description: force enable ssl(solved cannot mixed load problem)
---

## Introduction

put this code in your _config.yml

YAML:
{% highlight yaml %}
url: https://username.github.io
enforce_ssl: username.github.io
{% endhighlight yaml %}