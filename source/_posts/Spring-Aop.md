---
title: Spring AOP
comments: true
date: 2018-05-20 22:08:00
updated: 2018-05-20 22:08:00
tags: 
- Spring AOP
categories:
- Spring

---
# 关键词
- AOP：面向切面编程
- Advice（通知）：定义连接点做什么，为切面增强提供织入接口
- Pointcut（切点）：决定Advice通知应该作用于哪个连接点
- Advisor（通知器）：用于关联Advice和Pointcut，定义某个通知应该作用于哪个切点
- 实现：动态代理（JDK Proxy或CGLIB）、IOC