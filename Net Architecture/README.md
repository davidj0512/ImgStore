## 一	互联网并发编程	
#### 并发编程初级篇	
			1、线程安全基础知识、解决线程安全的手段和措施。
			2、Synchronized关键字与Volatile关键字，JDK原子类的使用与实际应用。
			3、线程之间通信与控制 wait、notify、ThreadLocal 、单例和多线程如何结合。
			4、模拟多线程与队列的访问。
			5、同步类容器，并发类容器介绍和概念、底层实现讲解。
			6、多线程如何进行控制、协作的讲解、模拟队列实现。
#### 并发编程中级篇	
			1、并发类容器Concurrent与CopyOnWrite思想设计。
			2、ConcurrentMap系列容器讲解使用与底层实现机制。
			3、CopyOnWrite系列类容器讲解使用与底层实现机制。
			4、ConcurrentLinkedQueue、ArrayBlockingQueue、LinkedBlockingQueue操作与使用。
			5、PriorityBlockingQueue实际场景操作与使用。
			6、DelayQueue实际场景操作与使用。
			7、SynchronousQueue、LinkedBlockingDeque 讲解与使用。
			8、在真实场景中队列容器的切换与使用讲解分析。
			9、多线程与设计模式相结合实际使用场景（一）。
			10、多线程与设计模式相结合模拟实际使用场景（二）。
			11、多线程与设计模式相结合模拟实际使用场景（三）。
#### 并发编程高级篇	
			1、JDK多任务执行框架的使用详解与真实场景分析。
			2、Concurrent.util下常用多线程工具类使用，了解互联网多线程场景，如何为我们系统减压，提高性能。
			3、容量评估、高水位、系统阀值、峰值、QPS、RT等互联网专业术语解释与信号量Semaphore控制流量详解。
			4、JAVA锁的机制与使用（重入锁、读写锁、Condition）。
			5、JAVA锁优化技术总结与归纳。
#### 并发编程框架篇	
			1、并发编程无锁计算框架学习
			2、框架核心底层原理讲解
			3、框架核心API讲解
			4、框架核心流程API操作讲解
			5、并行计算、分布式事务理念、实现讲解

## 二	互联网网络通信编程	
#### Socket/IO发展历程	
			1、学习基本概念、传统的同步阻塞式I/O编程。
			2、伪异步模式的探究，了解其弊端。
			3、 NIO编程，了解其NIO的核心概念和设计思想。学习Buffer、Channel、Selector等核心概念。
			4、实现NIO交互，了解NIO的弊端。
			5、 AIO编程，了解核心思想和AIO编程核心要点，去分析看似完美的AIO编程弊端。
#### Netty框架核心学习	
			1、 Netty时代，我们去深入学习Netty，了解其架构和核心思想。
			2、 学习初步通信（客户端服务器端通信机制）
			3、 Netty核心API讲解。
			4、 使用多个端口进行网络通信；
			5、 Netty对TCP数据流的处理方式讲解；
			6、 Netty编解码技术讲解；
			7、 序列化技术和手段
			8、使用通信压缩文件等技术手段。
			9、 Netty对UDP的支持讲解。
			10、 Netty与WebSocket的结合实现讲解。
#### Netty框架高级深入	
			1、Netty实现文件服务器
			2、真实案例中，如何去做数据通信、自定义自己的私有协议。
			3、实现服务器集群的心跳检测，监控服务器的各方面性能。
			4、Mina入门，我们通过学习Netty，也需要了解Mina框架如何去使用

## 三	JAVA虚拟机	
#### JVM组成		
			1、 了解java的JVM基础知识、认识虚拟机。
			2、 讲解虚拟各个组成部分用途。
			3、 深入剖析java堆（新生代、老年代的概念和实际场景的分配比例）。
			4、 了解java栈和方法区的使用。
			5、 虚拟机参数的配置，能看懂虚拟机信息，知其所以然，实际应用。（Xms、Xmx、Xss、Xmn等参数配置）
#### 垃圾收集器		
			1、 垃圾收集算法和概念深入讲解（引用计数法、标记清除法、复制算法、标记压缩法）
			2、 GC停顿的概念分析。
			3、如何让对象进入老年代配置。
			4、线程TLAB区域的深入剖析。
			5、 JAVA实例化对象的流程深入分析。
			6、垃圾收集器的应用（串行、并行、CMS、G1 等垃圾收集器的使用与配置）
#### 实战JVM与Tomcat	
			1、 实战TOMCAT调优（在真实项目中操作并配置JVM调优，对系统各项指标的影响、吞吐量、内存分配、阀值评估等）
			2、 内存监控工具、压力测试工具、性能监控工具的讲解。

## 四	Linux	
#### Linux		
			1、 Linux初步与环境安装。
			2、 常用命令介绍与使用。
			3、 vi/vim文本编辑器介绍。
			4、 用户管理。
			5、进程管理。
			6、系统文件构成。
			7、软件包管理。
			8、 Shell编程。

## 五	数据库设计与优化	
#### 关系型数据库Oracle	
			1、 SQL基础篇，帮你复习面试和实际使用的细节问题，SQL优化手段。
			2、 SQL进阶篇，Oracle 引以为豪的分析系列函数的使用、Merge、递归分层函数等。
			3、（DBA方向）用户访问控制
			4、（DBA方向）事物、锁、索引详细分析与优化。
			5、 物化视图的实际应用与设计。
			6、同义词、DBLINK 的实际场景应用。
			7、 PL/SQL编程（包、存储过程、触发器、函数、动态语句、定时任务等知识点）
			8、表空间、DBCA的详细使用。
			9、 Oracle表类型、各种表分区、分区索引（oracle大数据处理手段 无非就是建立索引、物化视图、表分区、并行查询）
			10、设计数据库表结构（提升你自己的数据库设计水平，powerdesigner熟练使用）
			11、简单备份和恢复（偏向初级DBA运维方向，我们学习了解一定是为了为你日后成为应用架构师打下坚实的基础，扩展知识面）
#### 非关系型数据库Redis	
			1、 NOSQL（Redis）简介、Redis安装与部署。
			2、 Redis 基础数据类型详解。
			3、 Redis 高级命令
			4、 Redis 安全性、一致性
			5、 Redis主从复制、哨兵机制（高可用机制）
			6、 Redis持久化机制等技术
			7、 Redis 发布订阅模式、虚拟内存等技术点的讲解和使用
			8、 Redis集群（3.0）、运维详细讲解
			9、 Redis与java的使用
			10、Redis集群与spring框架进行整合
			11、Redis与Tomcat实现Session共享
			12、Redis与Lua语言开发
			13、ssdb缓存数据库入门与使用

## 六	互联网中间件架构设计	
#### ActiveMQ	
			1、 JMS概念（要做消息中间件，你一定要了解一下JMS概念，有一个认知）
			2、 ActiveMQ初步（我们在windows进行部署MQ服务器，然后做一个小程序，了解下如何使用MQ）
			3、 ActiveMQ详细使用 (深入学习MQ的使用)
			4、 高级主题（一），深入学习经典MQ模式，P2P模式讲解。
			5、 高级主题（一），深入学习经典MQ模式，发布与订阅模式讲解。
			6、 了解内容（与spring框架进行整合、broker配置）
#### RocketMQ	
			1、RocketMQ简介及其应用
			2、RocketMQ集群环境搭建与使用
			3、RocketMQ之初步讲解
			4、RocketMQ之架构设计讲解
			5、RocketMQ之NameSrv讲解
			6、RocketMQ之数据监控平台console使用
			7、RocketMQ之API详解（消息推送）
			8、RocketMQ之API详解（消息拉取）
			9、RocketMQ之顺序消费特性讲解
			10、RocketMQ之事务提交阶段讲解
			11、RocketMQ 之配置文件讲解
#### RocketMQ实战应用	
			1 真实项目分布式应用案例，让你知道如何去面对分布式消息中间件，提供解决方案。做一个真正的项目案例（SpringMVC+Mybatis+Spring + MySQL）,并且对RocketMQ真实进行封装，某大型互联网公司封装代码设计"
			2 集群监控与运维（admin指令详解）

## 七	互联网框架应用	
#### zookeeper	
			1、 zookeeper简介说明、zookeeper的特性、zookeeper生态圈角色等讲解。
			2、 zookeeper应用场景讲解（一）配置管理
			3、 zookeeper应用场景讲解（二）集群管理
			4、 zookeeper应用场景讲解（三）发布与订阅
			5、 zookeeper应用场景讲解（四）数据库切换
			6、 zookeeper应用场景讲解（五）分布式日志的收集
			7、 zookeeper应用场景讲解（六）分布式锁、队列管理、分布式场景业务实现等等
			8、搭建zookeeper集群环境、shell操作zookeeper。
			9、 zookeeper配置文件详解
			10、 原生java操作zookeeper（实现节点变更、同步等操作）
			11、 java操作zookeeper客户端进行Watcher观察、事件类型、ACL安全等讲解
			12、 java扩展操作zookeeper（实现便捷的敏捷化开发）
			13、 使用java分布式框架API对zookeeper操作，实现真实场景案例。
#### Dubbo、DubboX	
			1、 SOA与Dubbo。
			2、 Dubbo架构讲解。
			3、 Dubbo学习与应用、项目配置。
			4、 DubboX介绍与新特性。
			5、 使用Restful与Dubbox的完美结合。
			6、 使用kyro序列化框架与Dubbox结合。
			7、 其他内容（tomcat配置、监控等）
#### Solr	
			1、搜索引擎技术概述与Solr概述
			2、 Solr环境搭建 搭建自己的搜索服务器
			3、 Java操作Solr服务器（复杂查询功能等）
			4、 Solr详细使用、分片、高亮显示等
			5、 Solr配置文件讲解
			6、 管理员运维命令与Solr集群搭建，处理海量数据搜索服务
			7、 Solr实战项目（SpringMVC+Mybatis+Spring + MySQL）,电商搜索功能实现。
#### Nginx	
			1、 Nginx基础简介。
			2、 Nginx网络环境搭建。
			3、 Tomcat与Nginx整合实现负载均衡
			4、 Nginx配置文件学习。
			5、 keepalived环境搭建
			6、 Nginx与keepalived实现高可用
#### 分布式文件系统	
			1、 FastDFS分布式文件系统简介
			2、 FastDFS分布式文件系统安装
			3、 FastDFS分布式文件系统使用
			4、 FastDFS分布式文件系统集群环境搭建
			5、 FastDFS分布式文件系统实战应用
#### 海量数据处理框架	
			1、 海量处理数据讲解
			2、 并行计算框架讲解

## 八	互联网分布式综合项目实战	
#### 环境与技术	
			数据交换平台（系统）
			平台选择：Windows、Linux
			软件环境：JDK1.7、Tomcat7、Maven+私服：搭建项目
			开发工具：Eclipse等
			技术使用：
			传统框架：SpringMVC、 Mybatis（JDBCTemplate）、Spring
			数据库：Redis、Oracle
			互联网技术：Http、Thread（多线程知识）、RocketMQ、 Zookeeper、Dubbox、Netty、Rest、Solr、Nginx等技术。
			前端技术：ExtJS4.X 、HTML5等
#### 项目概述、环境搭建、分析、规范、设计等	
			1、平台概述（对平台的背景说明）
			2、需求分析（对平台的需求分析说明）
			3、平台搭建（进行环境搭建准备工作）
			4、规划规范（进行模块化、子项目级别的规划与整合）
			5、平台设计（平台设计与实施）
#### 单点登录	
			1、 CAS单点登录（单点技术讲解）
			2、单点登录技术与分布式系统完美整合（实现分布式）
#### 基础信息	
			1、 基础信息设计（学习如何设计数据库表结构）
			2、 ExtJS讲解（ExtJS宗师级别高手带你学ExtJS）
			3、 ExtJS组件化封装
			4、 ExtJS与Java结合开发
#### 缓存维护	
			1、使用Redis进行缓存设计（一 简单数据类型）
			2、使用Redis进行缓存设计（二 复杂数据类型）
			3、存储过程、定时任务、与Oracle数据库进行同步
#### 消息服务		
			1、zookeeper协调消息中间件（MQ）
			2、对MQ进行封装
			3、对zookeeper进行封装
			4、实现发布订阅消息机制
#### 数据交换	
			1、真实场景描述，使用Netty如何自定义协议、认证工作。
			2、 真实案例，多个项目不同数据库间进行数据交换。
#### 统计分析	
			1、 索引的设计
			2、 数据表的设计
			3、 缓冲表的设计
			4、 定时任务设计（模块化实现）
			5、 后台统计分析
#### Rest服务接口设计	
			1、 实现内部通信（处理分布式存储、ESB总线调用）
			2、 实现外部接口通信（对外提供可靠性服务）
