---
layout: post
title: "Violet SNS论坛 项目展示"
date:   2024-8-2
tags: [project]
comments: true
author: Dio
---

<!-- more -->
## Violet SNS论坛 项目介绍
###### 项目仓库地址：https://github.com/ZJF39/HIT-2024Sum-violetsns
###### （项目正在完善当中，当前正在添加的功能：搜索中台、网络聊天室）
Violet SNS 是一个基于 Spring Boot 搭建的前后端分离的论坛项目。
用户可以利用论坛浏览帖子、参与活动、发布资源、参加内推等。
管理员可以对论坛中发布的内容进行管理、发布公告、并可视化地查看论坛运营数据。
前端分为两部分进行编写，分别是普通用户端和管理员用户端，后端通过鉴权限制用户访问。
* 前端开发：采用 Vue3 进行前端开发，提供动态、响应式的用户界面。
* 后端框架：采用 Spring Boot 框架进行后端开发，项目整体为SSM架构。
* 数据持久化：项目主体数据库为 MySQL，利用Mybatis进行数据库管理，针对频繁使用的 token、用户信息、验证码等，使用 Redis 进行缓存，提高系统的响应速度和处理能力。
* 用户校验：使用SpringSecurity 实现用户登录与鉴权，使用 JWT 进行 token 验证，并添加了验证码模块完善登录逻辑。
* 文件上传：使用阿里云OSS 进行文件上传，实现文件存储与访问。
* 接口文档：使用 Swagger、knife4j 生成接口文档，便于团队开发交流和接口调试。
## 项目结构
  
Java 后端结构  
![后端项目结构](https://zjf39.github.io/images/violetsns/backfront.png)  
  
数据库结构

![数据库结构](https://zjf39.github.io/images/violetsns/datebaseStruct.png)

Linux 部署结构  
  
![Linux部署结构](https://zjf39.github.io/images/violetsns/linuxDocker.png)  


## 前端展示
  
主页 
![主页](https://zjf39.github.io/images/violetsns/indexPage.png)  

登录页面  
![登录页面](https://zjf39.github.io/images/violetsns/loginPage.png)  
  
个人中心  
![个人中心](https://zjf39.github.io/images/violetsns/myPage.png)  
  
编辑帖子（富文本编辑器）
![发送文章](https://zjf39.github.io/images/violetsns/post.png)  
  
文章详情  
![文章详情](https://zjf39.github.io/images/violetsns/postPage.png)  
  
管理员中台  
![管理员中台 ](https://zjf39.github.io/images/violetsns/adminIndex.png)  
