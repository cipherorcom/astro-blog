---
title: Nacos
published: 2025-05-30

# Optional
description: ''
updated: ''
tags:
  - DevTools

# Advanced
draft: false
pin: 0
toc: true
lang: 'en'
abbrlink: ''
---

## Missing startup command in the documentation
The command is `bash startup.sh -m standalone`. Not only Ubuntu, but Debian also requires `bash`.

![image.webp](https://r2.cipheror.com/u8eioCZ1.webp)

## gRPC
`If you have forwarded ports, remember to forward the gRPC port as well!!!`

Nacos has two ports: an HTTP port and a gRPC port. The gRPC port is calculated based on the HTTP port, with the formula being the HTTP port plus 1000. For example, if the HTTP port is 8848, then the gRPC port is 9848.
