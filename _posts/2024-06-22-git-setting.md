---
title: Git设置 & 常用命令行
date: 2024-06-22 09:53:00 +0800
categories: [环境配置/命令行]
tags: [Git, 命令行]
---

## SSH密钥对生成
```
ssh-keygen -t ed25519
```

## Git常用命令行

## 提交者信息
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

### 创建仓库
使用当前目录作为Git仓库，只需要初始化
```
git init
```
这个命令会在当前目录生成一个`.git`目录

使用指定目录作为Git仓库
```
git init newrepo
```
这个命令会在`newrepo`中生成一个`.git`目录