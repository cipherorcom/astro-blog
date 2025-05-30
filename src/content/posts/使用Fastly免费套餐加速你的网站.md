---
title: 使用Fastly免费套餐加速你的网站
published: 2025-04-21 11:16:21

# Optional
description: ''
updated: ''
tags:
  - CDN

# Advanced
draft: false
pin: 0
toc: true
lang: ''
abbrlink: ''
---

<p>Fastly提供了免费的CDN套餐，我们可以通过免费的CDN套餐加速访问我们的网站，免费套餐一般来说也不会超量，个人使用完全够用。</p>

Fastly的免费CDN套餐如下：
![图片.webp](https://r2.notpeppa.pp.ua/KK2BYob1.webp)

## 注册账号
[点击注册](https://www.fastly.com/signup)

### 创建CDN
登录后点击`CDN`，点击`Create service`
![图片.webp](https://r2.notpeppa.pp.ua/clqSSRAt.webp)

### 开始配置
![图片.webp](https://r2.notpeppa.pp.ua/YJxuz7sD.webp)
![图片.webp](https://r2.notpeppa.pp.ua/s7uNRRmW.webp)
填入所有信息之后点击`Activate`

### 添加CNAME记录

![image.webp](https://r2.cipheror.com/a1KmaqFv.webp)

### 申请SSL证书
选择`Secure another domain`

![image.webp](https://r2.cipheror.com/zHNkhTpT.webp)

输入要申请证书的域名，点击`Add`

![image.webp](https://r2.cipheror.com/KReyRLvl.webp)

选择`Let's Encrypt` 点击`Submit`

![image.webp](https://r2.cipheror.com/r9OzRbXh.webp)

等待申请

![image.webp](https://r2.cipheror.com/6qXd63t0.webp)

申请成功

![image.webp](https://r2.cipheror.com/OHIZKtAr.webp)

### 修改SSL
点击`Clone`

![图片.webp](https://r2.notpeppa.pp.ua/26WJIbMl.webp)

找到SSL证书的地方，将其修改为1年

![图片.webp](https://r2.notpeppa.pp.ua/sjS80YRe.webp)

### 发布
![图片.webp](https://r2.notpeppa.pp.ua/D4JxySJr.webp)

## 成功解析
![image.webp](https://r2.cipheror.com/nS2vaNek.webp)
