---
title: Ubuntu 18.04命令行更改密码
date: 2020-09-14 09:52:01
tags:
  - 运维
  - 命令行
categories:
  - Ubuntu
---

## Ubuntu版本
18.04
## 要求
必须有root权限或者可以执行sudo命令
<!--more-->
## 修改当前登录用户密码
直接输入下面命令
```dos
$ passwd
``` 
命令行窗口提示输入原始密码，随后输入新密码已经确认新密码
## 修改指定用户密码
假设需要修改密码的登录用户名为john，输入下面命令
```dos
$ sudo passwd john
``` 
剩余步骤与修改当前登录用户相同