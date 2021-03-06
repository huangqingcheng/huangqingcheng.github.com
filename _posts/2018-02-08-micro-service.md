---
layout: post
title: 微服务架构杂谈
comments: true
categories:
 - 微服务
---

微服务架构需要关注的技术点
* 基础设施自动化
* 服务注册与服务发现
* 服务路由
* 服务熔断
* 集中配置
* 统一日志收集
* 服务监控

至少应包含以下功能
* 服务注册与服务发现
* 负载均衡
* 消息总线，轻量级的MQ或HTTP
* 日志审计，主要是日志的汇总、分类和查询
* 监控和告警，主要是监控每个服务的状态，必要时生产告警
* 部署和升级
* 事件调度机制
* 资源管理，如底层的虚拟机、物理机和网络管理

另外一些可选的功能
* 微服务统一代码框架，支持多种编程语言
* 统一服务构建和打包
* 统一服务测试
* 微服务CI/CD流水线
* 服务依赖关系管理
* 统一问题追踪调试框架（调用链）
* 灰度分布
* 蓝绿部署
