---
title: Git Code
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
lang: 'en'
abbrlink: ''
---
## Rollback code
```bash
Local rollback
git reset --hard HEAD^ //Roll back to the previous version
git reset --hard HEAD~n //Roll back to n commits ago. If n=3, you can roll back to 3 commits ago.
git reset --hard commit_sha //Roll back to the specified commit's SHA code. This method is recommended.

Remote push
git push origin HEAD --force
```
