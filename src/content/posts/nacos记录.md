---
title: Nacos记录
published: 2025-05-22

# Optional
description: ''
updated: ''
tags:
  - DevTools

# Advanced
draft: false
pin: 0
toc: true
lang: 'zh'
abbrlink: ''
---

## 文档中启动命令丢失
命令为`bash startup.sh -m standalone` 不只是Ubuntu，Debian也一样要用`bash`

![image.webp](https://r2.cipheror.com/u8eioCZ1.webp)

## gRPC问题
`如果你进行了端口转发，记得同时转发gRPC端口！！！`

Nacos有两个端口，一个http端口，一个gRPC端口，gRPC端口是根据http端口进行推算的，计算方式为http端口加1000，比如http端口为8848，则gRPC端口为9848

## 认证问题
如果你打开了鉴权，在访问Nacos时，不仅`spring.cloud.nacos.discovery`需要配置`username`和`password`，`spring.cloud.nacos.config`同样需要配置！！！

## namespace不生效问题
`namespace` 不是填name是填ID！ID！ID！

```
spring:
  application:
    name: xxx
  cloud:
    nacos:
      server-addr: xxxxx
      config:
        namespace: dev  // 不是填name是填ID！ID！ID！
```
