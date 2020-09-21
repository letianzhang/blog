---
title: Docker常用命令
date: 2020-09-18 17:16:55
tags:
  - 运维
  - 命令行
categories:
  - Docker
---

## 前提条件

### Ubuntu版本
```dos
$ 18.04
```

### Docker版本
```dos
$ Docker version 19.03.12, build 48a66213fe
```

## 重启Docker

### 输入下面命令
```dos
$ systemlctl restart docker
```

### 提示命令不存在，执行下面命令，根据情况添加sudo
```dos
$ apt-get install systemd
```