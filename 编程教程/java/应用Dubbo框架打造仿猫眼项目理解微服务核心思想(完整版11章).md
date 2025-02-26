# 应用Dubbo框架打造仿猫眼项目理解微服务核心思想(完整版11章)

## 联系方式

客服微信号：itziyuan_xiaozhi

<img src="https://ziyuanyun.oss-cn-guangzhou.aliyuncs.com/common/20240614073449/666b82192834a.jpg" width="200" height="200" alt="二维码">

## 课程简介

下载链接：https://it.bcwex.shop/posts?id=3973

<img src="https://ziyuanyun.oss-cn-guangzhou.aliyuncs.com/yun/20240515185534/664494a646cac.jpg" width="500" alt="">

  课程介绍〗:

 Dubbo作为主流的微服务框架之一，为开发人员带来非常多的便利。本门课程结合“仿猫眼”项目，分别针对Dubbo中的重要特性、微服务中核心内容以及面试中的常见问题，进行归纳整理，强化讲解，为你提供从零到面试的一条龙服务。

 应用Dubbo框架打造仿猫眼项目理解微服务核心思想(完整版11章)



 〖课程目录〗:

 第1章 微服务入门

  本章中将概要介绍微服务与传统应用之间的差异与实现优势，以便于帮助同学们更加清晰微服务在项目开发中的定位。

  1-1 学前必读（助你平稳踩坑，畅学无忧）

  1-2 课程导学

  1-3 传统应用带来的问题

  1-4 微服务概述

  第2章 演示环境构建

  本章中将通过一系列的基本演示，让同学们可以对Dubbo有一个快速直观的认识。当前项目中构建了目前Dubbo的两种主流兼容框架Spring和Springboot，并且都进行了Dubbo集成，以便于适应多种需求下的应对使用。

  2-1 基础环境构建介绍

  2-2 Spring基础环境构建

  2-3 Spring的直连提供者

  2-4 SpringBoot基础环境构建

  2-5 SpringBoot直连提供者演示

  2-6 注册中心概述

  2-7 Zookeeper-windows安装

  2-8 Spring集成注册中心

  2-9 Springboot集成注册中心

  第3章 业务基础环境构建

  经过上一章节的演示，让大家了解到Dubbo与Spring、Springboot集成和基本使用，本章中会将Dubbo与Guns进行集成，构建一个业务系统的基本环境，同时针对API网关进行了一个简单的描述和引入，为后续章节打下铺垫。

  3-1 API网关介绍

  3-2 Guns环境构建

  3-3 API网关模块构建测试

  3-4 API网关集成Dubbo

  3-5 抽离业务API

  3-6 理解Dubbo的调用流程与Dubbo多协议解析

  第4章 Dubbo基本特性：用户模块开发

  本章中将基于Springboot和Dubbo的结合，进行用户模块业务开发，并且会学习注册发现、负载均衡、路由策略等多项Dubbo核心特性。除此以外，会进一步了解API网关与业务模块的结合和开发。

  4-1 用户模块概要介绍

  4-2 接口文档和sql语句见面会

  4-3 用户服务与网关交互

  4-4 基于Springboot配置忽略列表

  4-5 基于用户业务的API修改

  4-6 修改JWT申请的返回报文

  4-7 Threadlocal保存用户信息

  4-8 JWT修改测试和总结

  4-9 用户模块-DAO层代码生成

  4-10 用户模块-注册业务实现

  4-11 用户模块-登陆和用户名验证实现

  4-12 用户模块-查询用户信息

  4-13 用户模块-修改用户信息实现

  4-14 网关模块-注册功能实现

  4-15 网关模块-用户名检查和退出功能实现

  4-16 网关模块-用户信息相关功能实现

  4-17 用户名验证接口测试

  4-18 用户注册接口测试

  4-19 用户信息查询接口测试

  4-20 用户信息修改接口测试

  4-21 Dubbo特性-启动检查

  4-22 Dubbo特性-负载均衡

  4-23 Dubbo特性-多协议支持

  4-24 章节总结归纳

  第5章 Dubbo服务开发：影片模块开发

  本章中将结合影片模块的开发，帮助同学们进一步了解Gateway的功能聚合的开发、异步调用等Dubbo特性；同时，会引入Lombok框架，并将详细讲解Dubbo的通信、线程模型等特性，以及相应的业务实现。

  5-1 影片模块介绍

  5-2 影片模块创建

  5-3 初识API网关特性 &#8211; 功能聚合

  5-4 Lombok框架引入和使用介绍

  5-5 首页实现 &#8211; VO对象创建

  5-6 首页实现 &#8211; Api接口定义

  5-7 电影模块-数据层生成

  5-8 首页实现 &#8211; Banner数据层

  5-9 首页实现 &#8211; 影片查询

  5-10 首页实现 &#8211; 其他查询

  5-11 首页实现 &#8211; 数据层补充及API整合

  5-12 首页实现 &#8211; 测试及ResponseVO调整

  5-13 条件列表实现 &#8211; 表现层及交互实体实现

  5-14 条件列表实现 &#8211; 结构建立

  5-15 条件列表实现 &#8211; 数据层实现 (1)

  5-16 条件列表实现 &#8211; 数据层实现(2)

  5-17 条件列表实现 &#8211; 表现层业务讲解

  5-18 条件列表实现 &#8211; 表现层业务实现(1)

  5-19 条件列表实现 &#8211; 表现层业务实现(2)

  5-20 条件列表实现 &#8211; 表现层业务实现(3)

  5-21 影片查询功能实现 &#8211; 思路介绍

  5-22 影片查询功能实现 &#8211; Service层实现

  5-23 影片查询功能实现 &#8211; 数据层实现(1)

  5-24 影片查询功能实现 &#8211; 数据层实现(2)

  5-25 影片查询功能实现 &#8211; 数据层实现(3)

  5-26 影片查询功能实现 &#8211; 网关实现

  5-27 影片查询功能实现 &#8211; 单元测试

  5-28 影片详情查询 &#8211; 业务介绍

  5-29 影片详情查询第一部分 &#8211; API定义

  5-30 影片详情查询第一部分 &#8211; 自定义SQL实现(1)

  5-31 影片详情查询第一部分 &#8211; 自定义SQL实现(2)

  5-32 影片详情查询第一部分 &#8211; 自定义SQL实现(3)

  5-33 影片详情查询第一部分 &#8211; 网关实现

  5-34 影片详情查询第二部分 &#8211; API定义

  5-35 影片详情查询第二部分 -数据层实现(1)

  5-36 影片详情查询第二部分 &#8211; 数据层实现(2)

  5-37 影片详情查询 &#8211; 网关实现

  5-38 业务结果测试

  5-39 Dubbo特性之异步调用讲解

  5-40 Spring版Dubbo异步调用演示

  5-41 业务系统集成Dubbo异步调用(1)

  5-42 业务系统集成Dubbo异步调用实现(2)

  5-43 影片模块总结

  第6章 Dubbo服务开发：影院模块开发

  本章中将完成影院模块开发，保证整个业务的连贯性，同时将详细讲解包括并发控制、连接控制、事件通知和结果缓存等Dubbo特性，并结合相应的业务进行实现。

  6-1 章节导读和表结构介绍

  6-2 影院模块构建

  6-3 影院模块服务网关结构构建

  6-4 接口文档与界面之间的对应关系

  6-5 分析服务网关的数据需求

  6-6 API实体对象创建

  6-7 分析API所需接口

  6-8 设计API接口

  6-9 Cinema模块数据层生成以及逻辑层构建

  6-10 Cinema模块实现 &#8211; 影院列表查询实现

  6-11 Cinema模块实现 &#8211; 查询条件列表实现

  6-12 Cinema模块实现 &#8211; 根据编号查询影院信息实现

  6-13 Cinema模块实现 &#8211; 查询某影院下所有电影和场次

  6-14 Cinema模块实现 &#8211; 查询特定场次相关信息

  6-15 Cinema模块实现 &#8211; 查询特定场次的影片信息

  6-16 Cinema网关实现 &#8211; 获取影院列表

  6-17 cinema网关实现 &#8211; 获取影院查询条件

  6-18 Cinema网关实现 &#8211; 获取所有上映场次信息

  6-19 Cinema网关实现 &#8211; 获取特定场次信息

  6-20 Cinema模块测试以及全局异常处理

  6-21 Dubbo特性之结果缓存

  6-22 Dubbo特性之并发与连接控制

  6-23 Spring环境演示

  6-24 Springboot环境演示

  第7章 Dubbo服务开发：订单模块开发

  本章中将会讲解订单模块，作为本系统中的重中之重，这个模块的讲解中也会涉及到几个在微服务领域中比较重要的点，包括分布式事务、服务熔断降级、分表分库以后的应对思路和限流的实现等等相关内容。在业务实现讲解的同时，本章会涉及到的Dubbo知识点主要包括：服务分组、版本控制、访问日志等。&#8230;

  7-1 订单模块介绍

  7-2 window ftp服务器构建

  7-3 订单模块环境构建

  7-4 订单模块服务网关构建

  7-5 订单模块接口分析

  7-6 订单模块API定义

  7-7 订单模块 &#8211; 数据层生成

  7-8 订单模块 &#8211; 获取座位地址实现

  7-9 订单模块 &#8211; FTP工具实现

  7-10 Springboot配置以及Springboot测试讲解

  7-11 订单模块 &#8211; 判断ID传入是否正确实现

  7-12 订单模块 &#8211; 判断是否已售座位

  7-13 订单模块 &#8211; 创建新订单

  7-14 订单信息查询SQL开发

  7-15 订单信息查询 &#8211; 业务层实现

  7-16 订单模块 &#8211; 获取所有已售座位业务实现

  7-17 订单模块 &#8211; 影院模块获取已售座位业务实现及调试

  7-18 订单模块 &#8211; 购票API网关实现

  7-19 订单模块 &#8211; 获取当前用户订单信息

  7-20 订单模块 &#8211; 购票业务测试以及相关内容修改

  7-21 订单模块 &#8211; 获取订单信息接口测试

  7-22 订单业务之后的问题总结

  7-23 分库分表业务介绍

  7-24 Dubbo特性之分组

  7-25 Dubbo特性之分组聚合

  7-26 Dubbo特性之版本控制

  7-27 业务改造 &#8211; 分组合并

  7-28 分组合并结果测试

  7-29 限流算法介绍

  7-30 限流算法集成业务系统

  7-31 熔断器Hystrix流程介绍

  7-32 熔断器效果演示

  7-33 解决熔断器下用户无法获取问题

  7-34 订单模块总结

  第8章 Dubbo服务开发：支付模块开发

  本章将带领大家实现对接支付宝的SDK，并且使用其沙箱环境完成整套支付动作。同时我们会引入一些与支付业务相关的几个Dubbo特性，比如隐式参数、参数验证和本地伪装，为支付业务保驾护航

  8-1 支付业务介绍

  8-2 当面付实例工程构建

  8-3 当面付功能演示

  8-4 支付模块构建

  8-5 支付模块网关与API设计

  8-6 订单模块适配改造

  8-7 支付模块实现 &#8211; 获取二维码地址

  8-8 支付模块实现 &#8211; 查询订单支付状态

  8-9 支付模块 &#8211; 服务网关实现

  8-10 支付模块 &#8211; 全流程测试

  8-11 二维码上传FTP实现

  8-12 Dubbo特性之本地存根介绍

  8-13 本地存根演示和使用场景介绍

  8-14 Dubbo特性之本地伪装介绍

  8-15 本地伪装演示

  8-16 本地伪装结合业务实现以及注意事项

  8-17 隐式参数传递讲解与实现

  8-18 课程总结

  第9章 分布式事务

  微服务的幂等性是微服务的核心之一，本章中将主要讲解分布式事务的产生原因、解决方案；同时会引入柔性补偿性事务和传统事务的解决方案。最后，我们会引入两种业务场景，分别讲解补偿式事务与两段式事务提交之间的优劣势和选择的前提。&#8230;

  9-1 章节介绍

  9-2 事务简介

  9-3 分布式事务介绍

  9-4 分布式事务实现思路介绍

  9-5 两段式和三段式事务介绍

  9-6 基于XA的分布式事务介绍

  9-7 基于消息的最终一致性方案介绍

  9-8 TCC柔性补偿式事务

  9-9 两种分布式事务优劣势比较

  9-10 主流分布式事务框架介绍

  9-11 TCC-Transaction环境构建

  9-12 HTTP案例部署展示

  9-13 Dubbo案例部署展示

  9-14 子事务红包模块解读

  9-15 主事务订单模块解读

  9-16 StringBoot环境准备

  9-17 基础环境配置详解

  9-18 流程演示以及jar包调整

  9-19 订单业务模拟分布式事务

  9-20 订单业务结果展示

  9-21 TCC框架现象带来的一些思考

  9-22 TCC框架事务存储器解析

  9-23 Compensable拦截器讲解（上）

  9-24 Compensable拦截器讲解（下）

  9-25 Resource拦截器讲解

  9-26 事务job讲解

  9-27 分布式事务章节总结

  第10章 服务监控

  Dubbo的服务链路监控是服务架构里比较重要的地方之一，同时也是面试里经常会被问到的点，在这里将会引入zipkin+brave的形式解决全链路监控的问题

  10-1 章节导读

  10-2 Dubbo Monitor介绍

  10-3 Dubbo-Monitor演示

  10-4 Dubbo-admin介绍

  10-5 Dubbo-admin安装部署

  10-6 Dubbo-admin演示01

  10-7 Dubbo-admin演示02

  10-8 Dubbo-admin演示03

  10-9 Dubbo-admin演示04

  10-10 链路监控介绍

  10-11 Dubbo特性之Filter介绍

  10-12 Spring环境演示Filter

  10-13 Springboot环境演示Filter

  10-14 Zipkin Spring环境演示

  10-15 业务系统集成Zipkin 01

  10-16 业务系统集成Zipkin02

  10-17 运行环境介绍

  10-18 本地虚拟机安装

  10-19 阿里云申请ECS服务器

  10-20 阿里云域名注册

  10-21 虚拟机初始化以及MySQL安装01

  10-22 MySQL安装02

  10-23 远程命令行工具安装与使用

  10-24 VSFtp安装部署

  10-25 JDK和Zookeeper安装

  10-26 数据初始化与工程打包

  10-27 微服务独立运行

  10-28 Openresty安装部署

  10-29 Openresty反向代理配置

  10-30 NodeJS安装

  10-31 整体效果演示

  第11章 微服务面试总结

  讲师本人使用微服务已经很多年，在本章会总结和梳理市面上经常会遇到的Dubbo相关的微服务问题，尤其是架构设计层面上的问题，为大家的顺利求职保驾护航。

  11-1 章节介绍

  11-2 Dubbo结构图和常识讲解

  11-3 服务治理讲解

  11-4 服务网关讲解

  11-5 分布式事务

  11-6 服务幂等性

  11-7 限流方案介绍

  11-8 自动化运维部署介绍

  11-9 总结

  