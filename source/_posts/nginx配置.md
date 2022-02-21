---
title: nginx配置
date: 2022-02-21 14:43:07
tags:
---
## nginx配置可访问目录

1.允许访问目录：autoindex on;
   location / {
            root   html;
            index  index.html index.htm;
            autoindex on;
        }

## 域名指向端口
