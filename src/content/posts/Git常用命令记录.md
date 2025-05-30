---
title: Git常用命令记录
published: 2025-04-15 13:21:44

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

## 回滚代码
```bash
本地回滚
git reset --hard HEAD^ //回退到上个版本
git reset --hard HEAD~n //回退到前n次提交之前，若n=3，则可以回退到3次提交之前
git reset --hard commit_sha //回滚到指定commit的sha码，推荐使用这种方式

远程推送
git push origin HEAD --force
```
