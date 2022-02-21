---
title: nginx配置
date: 2022-02-21 13:51:47
tags:
---
## nginx开启访问文件目录功能
允许访问目录：autoindex on;
```
location / {
          root   html;
          index  index.html index.htm;
          autoindex on;
      }
```