---
title: Gitコマンド
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
lang: 'ja'
abbrlink: ''
---
## コードのロールバック
```bash
ローカルでのロールバック
git reset --hard HEAD^ //1つ前のバージョンに戻す
git reset --hard HEAD~n //n回前のコミットに戻す（n=3の場合、3回前のコミットに戻す）
git reset --hard commit_sha //指定したコミットのSHAコードに戻す（推奨）

リモートへのプッシュ
git push origin HEAD --force
```
