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
lang: 'ja'
abbrlink: ''
---

## ドキュメント内の起動コマンドが欠落しています
コマンドは`bash startup.sh -m standalone`です。Ubuntuだけでなく、Debianでも`bash`を使用する必要があります。

![image.webp](https://r2.cipheror.com/u8eioCZ1.webp)

## gRPC
`ポート転送を行った場合、gRPCポートも同時に転送する必要があります！！！`

Nacosには2つのポートがあります。1つはHTTPポート、もう1つはgRPCポートです。gRPCポートはHTTPポートに基づいて計算されます。計算方法はHTTPポートに1000を加えるもので、例えばHTTPポートが8848の場合、gRPCポートは9848になります。
