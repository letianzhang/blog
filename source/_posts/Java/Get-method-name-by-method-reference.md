---
title: 通过方法引用获取方法名
date: 2020-09-29 09:38:58
tags:
  - Lambda
  - 方法引用
categories:
  - Java
---
## 前提条件
```dos
Java版本>=8
```
## 引入依赖
```dos
<dependency>
    <groupId>org.jodd</groupId>
    <artifactId>jodd-proxetta</artifactId>
    <version>5.2.0</version>
</dependency>
```
<!--more-->
## 使用
### 不带参数
```java
Methref.of(Str.class).name(Str::boo);
// returns String: 'boo'
```
### 带参数
```java
Methref.of(Str.class).name((str) -> str.hello(null, 0));
// returns 'hello'
```
### 注意
1. 方法并不会执行
1. 带参数的方法直接传递null即可