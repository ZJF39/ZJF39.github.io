---
layout: post
title: "超市管理系统 云原生微服务 项目展示"
date:   2024-6-18
tags: [project]
comments: true
author: Dio
---

<!-- more -->
## 超市管理系统 云原生微服务 项目介绍
###### 项目仓库地址：https://github.com/ZJF39/HIT-2024Spr-Cloud-Native
超市管理系统是一个云原生微服务实践项目，业务功能实现并不多，主要是为了进行Spring Cloud 微服务和云原生环境搭建的学习。
* 前端开发：采用 Vue2 进行前端开发，实现简单的页面展示。
* 后端框架：采用 Spring Cloud 整合 Spring Boot，实现微服务架构。
* 服务注册：使用Eureka 实现服务注册与发现，并使用 Gateway 网关，实现统一接口的服务调用。
* 数据库：使用 MySQL 实现数据库连接，并使用 iBatis 实现简单的数据库操作。
* 负载均衡：使用 OpenFeign 默认的轮询策略实现负载均衡机制，Hystrix实现服务熔断。
* 云原生环境搭建：利用三台虚拟机模拟云原生环境，使用 Kubernetes 实现容器编排。使用 Containerd 实现镜像管理并推送至阿里云远端仓库。
* CI/CD：使用 Jenkins 和 Gitee 实现自动化项目构建与部署。
## 项目结构

项目整体结构  
![项目整体结构](https://zjf39.github.io/images/market/struct.png)  

Java 后端结构  
![后端项目结构](https://zjf39.github.io/images/market/backfront.png)  

Linux 部署结构  
- 容器
![容器](https://zjf39.github.io/images/market/pod.png) 
- 镜像仓库
![镜像仓库](https://zjf39.github.io/images/market/AliImage.png) 
- Eureka注册中心
![Eureka注册中心](https://zjf39.github.io/images/market/Eureka.png) 
- K8s可视化管理 Dashboard
![K8s可视化管理Dashboard](https://zjf39.github.io/images/market/Dashboard.png)
- Jenkins CI/CD流水线
![Jenkins CI/CD流水线](https://zjf39.github.io/images/market/Jenkins.png)

## 简易前端展示
  
![前端1](https://zjf39.github.io/images/market/1.png)
![前端2](https://zjf39.github.io/images/market/2.png)
![前端3](https://zjf39.github.io/images/market/3.png)
