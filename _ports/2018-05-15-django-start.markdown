---
layout:     post
title:      "Hello Django"
subtitle:   " \"Hello First,Hello Django\""
date:       2018-05-15 18:30:00
author:     "R47"
header-img: "img/avatar.jpg"
catalog: true
tags:
    - Django
---

> “Django 第一步. ”

### 1、启动django项目(默认只允许本地访问，端口8000)：
`# python manage.py runserver`
### 2、修改访问端口
`# python manage.py runserver 8080`
### 3、修改允许外部访问
`# python manage.py runserver 0.0.0.0:8000`
### 4、外部访问不报错需要修改`ALLOWED_HOSTS`参数允许
```
# vim settings.py
ALLOWED_HOSTS = [ '*' ]
// *号为允许所有，也可以设置具体的允许访问地址
ALLOWED_HOSTS = [ 'ss.t47.top', '127.0.0.1', ' localhost' ]
```

