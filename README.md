# Awesome Technical Articles [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome technical articles.

# Content
- [Awesome Technical Articles ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-technical-articles-img-src%22httpsgithubcomsindresorhusawesome%22-alt%22awesome%22)
- [Content](#content)
  - [计算机基础](#%e8%ae%a1%e7%ae%97%e6%9c%ba%e5%9f%ba%e7%a1%80)
  - [Java](#java)
    - [并发](#%e5%b9%b6%e5%8f%91)
    - [多线程](#%e5%a4%9a%e7%ba%bf%e7%a8%8b)
    - [集合](#%e9%9b%86%e5%90%88)
    - [I/O](#io)
    - [异常](#%e5%bc%82%e5%b8%b8)
    - [单点登录](#%e5%8d%95%e7%82%b9%e7%99%bb%e5%bd%95)
    - [类加载器](#%e7%b1%bb%e5%8a%a0%e8%bd%bd%e5%99%a8)
  - [JVM](#jvm)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Lucene](#lucene)
  - [Spring](#spring)
    - [经典书籍](#%e7%bb%8f%e5%85%b8%e4%b9%a6%e7%b1%8d)
  - [Database](#database)
    - [数据库事务](#%e6%95%b0%e6%8d%ae%e5%ba%93%e4%ba%8b%e5%8a%a1)
    - [Hibernate](#hibernate)
    - [Mysql](#mysql)
    - [QueryDSL](#querydsl)
  - [Linux](#linux)
    - [Vim](#vim)
    - [Shell](#shell)
    - [Bash](#bash)
  - [Nginx](#nginx)
  - [Docker](#docker)
  - [Tomcat](#tomcat)
  - [Message queue](#message-queue)
    - [Kafka](#kafka)
  - [Netty](#netty)
  - [Ehcache](#ehcache)
  - [Redis](#redis)
  - [Continuous Integration](#continuous-integration)
    - [Jenkins](#jenkins)
  - [Front-End](#front-end)
    - [Javascript](#javascript)
    - [Jquery](#jquery)
    - [Web application](#web-application)
  - [Network Protocol](#network-protocol)
    - [WebSocket](#websocket)
  - [Regular Expression](#regular-expression)
  - [Git](#git)
  - [Data Visualization](#data-visualization)
  - [TensorFlow](#tensorflow)
  - [System Software](#system-software)
  - [云计算](#%e4%ba%91%e8%ae%a1%e7%ae%97)
    - [云原生](#%e4%ba%91%e5%8e%9f%e7%94%9f)
    - [k8s](#k8s)
  - [微服务](#%e5%be%ae%e6%9c%8d%e5%8a%a1)
  - [分布式系统](#%e5%88%86%e5%b8%83%e5%bc%8f%e7%b3%bb%e7%bb%9f)
    - [分布式事务](#%e5%88%86%e5%b8%83%e5%bc%8f%e4%ba%8b%e5%8a%a1)
  - [Web安全](#web%e5%ae%89%e5%85%a8)
  - [系统架构](#系统架构)
  - [Outside of technology](#outside-of-technology)

## 计算机基础
- [原码、反码、补码的产生、应用以及优缺点](./计算机基础/原码、反码、补码的产生、应用以及优缺点.pdf)
- [标点符号的英语名称](http://www.ruanyifeng.com/blog/2007/07/english_punctuation.html)

## Java

- [Java 开发手册](https://alitech-private.oss-cn-beijing.aliyuncs.com/1560932768000/Java%20huashan.pdf?Expires=1560958286&OSSAccessKeyId=LTAIqKGWQyF6Vd3W&Signature=mwgNXHSytBr8sCWb0CDbA73iwmw%3D&nsukey=zBH%2FMF6577nG2aFWxrQekcY1BwKsN6%2FvtrqAqXx2YaRtJ%2B22RBmR1LtqFuOhDqoovOf8%2FXtBnTTc4ZfdJkCEwhW1rbglRindiU8RKUWov%2FDV8chRqrB%2F%2F5Afb5edqm4SPaSAj4iak%2F5qhjRz7xU7x9dgI5MnwR%2FQaBaEm5zz5gSC8OBGQdrPv4WVG6NyjO4rgA14T3SKnh2c%2FZ4vNMypTg%3D%3D)[【PDF】](/Others/Java%20huashan.pdf)
- [从命名风格等方面解读阿里巴巴 Java 代码规范](https://www.ibm.com/developerworks/cn/java/deconding-code-specification-part-1/index.html)
- [从代码处理等方面解读阿里巴巴 Java 代码规范](https://www.ibm.com/developerworks/cn/java/deconding-code-specification-part-2/index.html)
- [Java 编程要点之并发（Concurrency）详解](https://waylau.com/essential-java-concurrency/#)

### 基础知识
- [字符和字符串](https://www.liaoxuefeng.com/wiki/1252599548343744/1255938912141568)

### 并发
- [Java理论与实践：正确使用Volatile变量](https://www.ibm.com/developerworks/cn/java/j-jtp06197.html)
- [Java多线程之延迟初始化](./JAVA/Concurrency/Java多线程之延迟初始化.pdf)
- [还在疑惑并发和并行？（laike9m）](https://laike9m.com/blog/huan-zai-yi-huo-bing-fa-he-bing-xing,61/)

### 多线程
- [Java多线程系列--“基础篇”01之 基本概念（wangkuiwu）](http://wangkuiwu.github.io/2012/08/01/threads-basic/)
- [Java多线程系列--“基础篇”02之 常用的实现多线程的两种方式（wangkuiwu）](http://wangkuiwu.github.io/2012/08/02/threads-basic/)
- [Java线程池实现原理及其在美团业务中的实践（美团技术团队）](https://zhuanlan.zhihu.com/p/123328822)
- [深入理解 Java 之 ThreadLocal 工作原理](https://allenwu.itscoder.com/threadlocal-source)
- [ThreadLocal造成OOM内存溢出案例演示与原理分析](https://blog.csdn.net/xlgen157387/article/details/78298840)

### 集合
- [Java 8系列之重新认识HashMap](https://zhuanlan.zhihu.com/p/21673805)

### I/O
- [Java中导入、导出Excel](https://www.cnblogs.com/jerehedu/p/4343509.html)

### 异常
- [Java异常(一) Java异常简介及其架构（wangkuiwu）](http://wangkuiwu.github.io/2012/04/14/exception/)
- [Java异常(二) 《Effective Java》中关于异常处理的几条建议（wangkuiwu）](http://wangkuiwu.github.io/2012/04/15/exception/)
- [Java异常(三) 《Java Puzzles》中关于异常的几个谜题（wangkuiwu）](http://wangkuiwu.github.io/2012/04/16/exception/)

### 单点登录
- [八幅漫画理解使用JSON Web Token设计单点登录系统（John Wu）](http://blog.leapoahead.com/2015/09/07/user-authentication-with-jwt/)
- [JSON Web Token - 在Web应用间安全地传递信息（John Wu）](http://blog.leapoahead.com/2015/09/06/understanding-jwt/)

### 类加载器
- [深入探讨 Java 类加载器](https://www.ibm.com/developerworks/cn/java/j-lo-classloader/index.html)
- [老大难的 Java ClassLoader 再不理解就老了](https://juejin.im/post/5c04892351882516e70dcc9b)

## JVM
- [Java内存区域详解](https://github.com/Snailclimb/JavaGuide/blob/master/docs/java/jvm/Java%E5%86%85%E5%AD%98%E5%8C%BA%E5%9F%9F.md)
- [JDK监控和故障处理工具总结](https://github.com/Snailclimb/JavaGuide/blob/master/docs/java/jvm/JDK%E7%9B%91%E6%8E%A7%E5%92%8C%E6%95%85%E9%9A%9C%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E6%80%BB%E7%BB%93.md)
- [怎样分析 JAVA 的 Thread Dumps](https://segmentfault.com/a/1190000000615690)
- [使用 VisualVM 进行性能分析及调优](https://www.ibm.com/developerworks/cn/java/j-lo-visualvm/)
- [如何使用jstack分析线程状态](http://www.importnew.com/23601.html)
- [如何利用 JConsole观察分析Java程序的运行，进行排错调优](http://jiajun.iteye.com/blog/810150)
- JVM性能调优监控工具专题（Josh_Persistence）
  - [JVM性能调优监控工具专题一：JVM自带性能调优工具（jps,jstack,jmap,jhat,jstat,hprof)](http://josh-persistence.iteye.com/blog/2161848)
  - [JVM性能调优监控工具专题二：VisualVM基本篇之监控JVM内存，CPU，线程](http://josh-persistence.iteye.com/blog/2233445)
  - [JVM性能调优监控工具专题二：VisualVM基本篇之远程监控，监控Tomcat](http://josh-persistence.iteye.com/blog/2233459)
  - [JVM性能调优监控工具专题三：VisualVM基本篇之快照分析、监控GC、Eclipse集成](http://josh-persistence.iteye.com/blog/2233787)
- JVM系列（纯洁的微笑）
  - [（1）java类的加载机制](http://www.ityouknow.com/jvm/2017/08/19/class-loading-principle.html)
  - [（2）JVM内存结构](http://www.ityouknow.com/jvm/2017/08/25/jvm-memory-structure.html)
  - [（3）GC算法 垃圾收集器](http://www.ityouknow.com/jvm/2017/08/29/GC-garbage-collection.html)
  - [（4）jvm调优-命令篇](http://www.ityouknow.com/jvm/2017/09/03/jvm-command.html)
  - [（5）Java GC 分析](http://www.ityouknow.com/jvm/2017/09/18/GC-Analysis.html)
- Become a Java GC Expert（Sangmin Lee）
  - [（1）Understanding Java Garbage Collection](https://www.cubrid.org/blog/understanding-java-garbage-collection/)
  - [（2）How to Monitor Java Garbage Collection ](https://www.cubrid.org/blog/how-to-monitor-java-garbage-collection/)
  - [（3）How to Tune Java Garbage Collection](https://www.cubrid.org/blog/how-to-tune-java-garbage-collection)
  

## Data Structures and Algorithms
- [数据结构和算法动态可视化](https://visualgo.net/zh)
- [Design patterns implemented in Java](https://java-design-patterns.com/)
- [RSA算法原理（一）](http://www.ruanyifeng.com/blog/2013/06/rsa_algorithm_part_one.html)
- [RSA算法原理（二）](http://www.ruanyifeng.com/blog/2013/07/rsa_algorithm_part_two.html)
- [Data Structures Reference](https://www.interviewcake.com/data-structures-reference)
- [图说设计模式](https://design-patterns.readthedocs.io/zh_CN/latest/index.html)

## Lucene

- [Spring Boot 中使用 Java API 调用 Lucene](https://segmentfault.com/a/1190000011916639)

## Spring
- [Spring-aop 全面解析（从应用到原理）](https://juejin.im/post/591d8c8ba22b9d00585007dd)
- [IoC-spring 的灵魂](https://juejin.im/post/591d8c8ba22b9d00585007dd)
- [中小型互联网公司微服务实践](http://www.ityouknow.com/springcloud/2017/10/19/micro-service-practice.html)
- [Spring中获取request的几种方法，及其线程安全性分析](https://www.cnblogs.com/kismetv/p/8757260.html)
- [Spring Interceptor vs Filter 拦截器和过滤器区别](http://einverne.github.io/post/2017/08/spring-interceptor-vs-filter.html)
- [Spring MVC 应用处理 CORS](http://einverne.github.io/post/2017/09/spring-with-cors.html)
- [Spring 中实现动态数据源](https://ketao1989.github.io/2015/01/12/Spring-Dynamic-Data-Source-Guide/)

### 经典书籍
- [Expert One On One J2EE Development Without EJB](./JAVA/Spring/Expert%20One%20On%20One%20J2EE%20Development%20Without%20EJB.pdf)

## Database
- [SQL与索引优化合集（58沈剑）](https://mp.weixin.qq.com/s/3xkLTe7r388lRq-SBQllXw)

### 数据库事务
- [数据库的读现象浅析](http://www.hollischuang.com/archives/900)
- [深入分析事务的隔离级别](http://www.hollischuang.com/archives/943)
- [数据库事务隔离级别和锁实现机制](https://www.iteye.com/blog/comedsh-698733)
- [MySQL中的行级锁,表级锁,页级锁](http://www.hollischuang.com/archives/914)
- [深入理解乐观锁与悲观锁](http://www.hollischuang.com/archives/934)
- [MySQL表级锁与行级锁](http://linux.it.net.cn/m/view.php?aid=11089)
- [Spring的事务管理机制](http://www.hollischuang.com/archives/1489)
- [JTA 深度历险 - 原理与实现](https://www.ibm.com/developerworks/cn/java/j-lo-jta/)
- [Java中的事务——JDBC事务和JTA事务](http://www.hollischuang.com/archives/1658)
- [事务隔离](https://zh.wikipedia.org/wiki/%E4%BA%8B%E5%8B%99%E9%9A%94%E9%9B%A2)
- [事务已提交，数据却丢了，赶紧检查下这个配置！！！](./Database/Mysql/事务已提交，数据却丢了，赶紧检查下这个配置！！！.pdf)
- [Mysql慢查询日志](https://github.com/GongchuangSu/Blog/blob/master/Mysql%26Oracle/Mysql%E6%85%A2%E6%9F%A5%E8%AF%A2%E6%97%A5%E5%BF%97.md)
- [如何选择分布式事务解决方案？](https://mp.weixin.qq.com/s/2AL3uJ5BG2X3Y2Vxg0XqnQ)

### Hibernate
- [深入理解hibernate的三种状态](http://www.cnblogs.com/xiaoluo501395377/p/3380270.html)
- [hibernate缓存机制详细分析](http://www.cnblogs.com/xiaoluo501395377/p/3377604.html)

### Mysql
- [MySQL慢查询分析mysqldumpslow（kimi）](http://kimi.it/410.html)
- [送给DBA：把这个转给你的开发，对接工作不再吐血（陈芳志）](https://dbaplus.cn/news-11-2316-1.html)
- [MySQL 性能优化技巧（月光中的污点）](https://www.extlight.com/2017/10/07/MySQL-%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7/)[【PDF】](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Database/Mysql/MySQL%20%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7.pdf)
- [MySQL 实现主从复制（月光中的污点）](https://www.extlight.com/2018/03/12/MySQL-%E5%AE%9E%E7%8E%B0%E4%B8%BB%E4%BB%8E%E5%A4%8D%E5%88%B6/)[【PDF】](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Database/Mysql/MySQL%20%E5%AE%9E%E7%8E%B0%E4%B8%BB%E4%BB%8E%E5%A4%8D%E5%88%B6.pdf)
- [为什么阿里巴巴禁止使用 count(列名)或 count(常量)来替代 count(*)](./Database/Mysql/为什么阿里巴巴禁止使用%20count(列名)或%20count(常量)来替代%20count(*).pdf)
- [MySQL索引原理及慢查询优化](https://tech.meituan.com/2014/06/30/mysql-index.html)

### QueryDSL
- [QueryDSL 与 JPA 的配合（屈定）](https://zhuanlan.zhihu.com/p/24778422?refer=dreawer)

## Linux
- [UNIX Tutorial for Beginners](http://www.ee.surrey.ac.uk/Teaching/Unix/)
- [Linux的五个查找命令（阮一峰）](http://www.ruanyifeng.com/blog/2009/10/5_ways_to_search_for_files_using_the_terminal.html)
- [Linux Find Command – Everything You Need to Know](https://www.putorius.net/linux-find-command.html)
- [awk 入门教程](http://www.ruanyifeng.com/blog/2018/11/awk.html)
- [30 Examples for Awk Command in Text Processing](https://likegeeks.com/awk-command/)
- [前后端同学必会的Linux基础命令](https://www.imooc.com/article/266441)
- [理解inode（阮一峰）](http://www.ruanyifeng.com/blog/2011/12/inode.html)
- Linux性能分析工具汇总合集（[原文](http://rdc.hundsun.com/portal/article/731.htm)、[微信](https://mp.weixin.qq.com/s/ALCbjkk29SOoWP_zS_y91A)）
- [进程间通信IPC (InterProcess Communication)](https://www.jianshu.com/p/c1015f5ffa74)

### Vim
- [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/#)
- [简明 VIM 练级攻略](https://coolshell.cn/articles/5426.html)

### Shell
- [How to write practical shell scripts](https://likegeeks.com/write-shell-script/)

### Bash
- [Bash Guide for Beginners（Machtelt Garrels）](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Linux/Bash%20Beginners%20Guide.pdf)
- [A User's Guide for GNU Awk（Arnold D. Robbins）](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Linux/A%20User's%20Guide%20for%20GNU%20Awk.pdf)
- [处理Apache日志的Bash脚本（阮一峰）](http://www.ruanyifeng.com/blog/2012/01/a_bash_script_of_apache_log_analysis.html)
- [Linux bash总结(一) 基础部分（wangkuiwu）](http://wangkuiwu.github.io/2011/09/01/shell/)
- [Linux bash总结(二) 高级部分（wangkuiwu）](http://wangkuiwu.github.io/2011/09/02/shell/)

## Nginx
- [agentzh 的 Nginx 教程](http://openresty.org/download/agentzh-nginx-tutorials-zhcn.html)
- [Nginx 极简教程](https://github.com/dunwu/nginx-tutorial)
- [什么是负载均衡](https://mp.weixin.qq.com/s/xvozZjmn-CvmQMAEAyDc3w)
- Nginx配置跨域请求
  - [Nginx配置跨域请求](https://segmentfault.com/a/1190000012550346)
  - [Nginx解决跨域](http://www.nginx.cn/4592.html)

## Docker
- [Docker — 从入门到实践](https://www.yuque.com/grasilife/docker)
- [Docker 入门教程（阮一峰）](http://www.ruanyifeng.com/blog/2018/02/docker-tutorial.html)
- Docker入门系列（纯洁的微笑）
  - [Docker(一)：Docker入门教程](http://www.ityouknow.com/docker/2018/03/07/docker-introduction.html)
  - [Docker(二)：Dockerfile 使用介绍](http://www.ityouknow.com/docker/2018/03/12/docker-use-dockerfile.html)
  - [Docker(三)：Dockerfile 命令详解](http://www.ityouknow.com/docker/2018/03/15/docker-dockerfile-command-introduction.html)
  - [Docker(四)：Docker 三剑客之 Docker Compose](http://www.ityouknow.com/docker/2018/03/22/docker-compose.html)
  - [Docker(五)：Docker 三剑客之 Docker Machine](http://www.ityouknow.com/docker/2018/03/30/docker-machine.html)
  - [Docker(六)：Docker 三剑客之 Docker Swarm](http://www.ityouknow.com/docker/2018/04/19/docker-swarm.html)

## Tomcat 
- [Tomcat中JVM内存溢出及合理配置](https://my.oschina.net/xianggao/blog/83823)
- [详解Tomcat配置文件server.xml](http://www.cnblogs.com/kismetv/p/7228274.html)
- [详解Tomcat的连接数与线程池](http://www.cnblogs.com/kismetv/p/7806063.html)
- [Tomcat 调优及 JVM 参数优化](https://www.cnblogs.com/baihuitestsoftware/articles/6483690.html)

## Message queue
- [浅谈消息队列及常见的消息中间件](https://juejin.im/post/5b41fe36e51d45191252e79e)
### Kafka
- [Kafka中文文档](http://kafka.apachecn.org/)
- [Kafka快速入门](https://colobu.com/2014/08/06/kafka-quickstart/)

## Netty

## Ehcache

## Redis
- [Redis使用手册](http://redisguide.com/)
- [Redis命令参考](http://redisdoc.com/)

## Continuous Integration
- [持续集成是什么？（阮一峰）](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)
### Jenkins
- [GitLab 自动触发 Jenkins 构建](https://www.wolfcstech.com/2018/03/26/gitlab_trigger_jenkins_build/)

## Front-End
- [Web 前端开发入门手册（前端九部）](https://www.yuque.com/fe9/basic)
### Javascript
- [Web Design in 4 minutes](https://jgthms.com/web-design-in-4-minutes)
- [JavaScript in 14 minutes](https://jgthms.com/javascript-in-14-minutes/)
- [Javascript模块化编程（一）：模块的写法](http://www.ruanyifeng.com/blog/2012/10/javascript_module.html)
- [Javascript模块化编程（二）：AMD规范](http://www.ruanyifeng.com/blog/2012/10/asynchronous_module_definition.html)
- [Javascript模块化编程（三）：require.js的用法](http://www.ruanyifeng.com/blog/2012/11/require_js.html)
- [Immediately-Invoked Function Expression (IIFE)](http://benalman.com/news/2010/11/immediately-invoked-function-expression/)
- [写给自己看的display: grid布局教程](https://www.zhangxinxu.com/wordpress/2018/11/display-grid-css-css3/)

### Jquery
- [Jquery中 .bind() .live() .delegate() 和 .on() 之间的区别](https://segmentfault.com/a/1190000010435530)
- [浏览器同源政策及其规避方法](http://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)
- [jQuery之jsonp跨域请求](https://www.cnblogs.com/chiangchou/p/jsonp.html)
- [跨域资源共享 CORS 详解](http://www.ruanyifeng.com/blog/2016/04/cors.html)
- [四种常见的 POST 提交数据方式（Jerry Qu）](https://imququ.com/post/four-ways-to-post-data-in-http.html)

### Web application
- [前端组件化框架之路（民工精髓V）](https://github.com/xufei/blog/issues/19)
- [Web应用组件化的权衡（民工精髓V）](https://github.com/xufei/blog/issues/22)
- [Web应用的组件化（一）——基本思路（民工精髓V）](https://github.com/xufei/blog/issues/6)
- [Web应用的组件化（二）——管控平台（民工精髓V）](https://github.com/xufei/blog/issues/7)
- [一种SPA（单页面应用）架构（livoras）](https://github.com/livoras/blog/issues/3)

## Network Protocol
- [网络是怎样连接的（[日]户根勤）](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Network%20Protocol/%E7%BD%91%E7%BB%9C%E6%98%AF%E6%80%8E%E6%A0%B7%E8%BF%9E%E6%8E%A5%E7%9A%84.pdf)
- [互联网协议入门（一）（阮一峰）](http://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html)
- [互联网协议入门（二）（阮一峰）](http://www.ruanyifeng.com/blog/2012/06/internet_protocol_suite_part_ii.html)
- [HTTPS协议图解](https://tls.ulfheim.net/)
- [HTTPS explained with carrier pigeons](https://medium.freecodecamp.org/https-explained-with-carrier-pigeons-7029d2193351)
- [DHCP 协议如何工作](https://www.benburwell.com/posts/how-does-dhcp-work/)
- [SSH原理与运用（一）：远程登录（阮一峰）](http://www.ruanyifeng.com/blog/2011/12/ssh_remote_login.html)
- [图解正向代理、反向代理、透明代理](http://blog.51cto.com/z00w00/1031287)
- [一分钟实现内网穿透（ngrok服务器搭建）](https://blog.csdn.net/zhangguo5/article/details/77848658)
- [What really happens when you navigate to a URL](http://igoro.com/archive/what-really-happens-when-you-navigate-to-a-url/)
- [当你在浏览器中输入 google.com 并且按下回车之后发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN)
- [DNS 原理入门（阮一峰）](http://www.ruanyifeng.com/blog/2016/06/dns.html)
- [虚拟机网络配置详解(NAT、桥接、Hostonly)](https://www.jianshu.com/p/305f7384cfe9)
- [通俗大白话来理解TCP协议的三次握手和四次分手](https://github.com/jawil/blog/issues/14)
- [服务器TIME_WAIT和CLOSE_WAIT区别及解决方案](https://blog.csdn.net/kobejayandy/article/details/46641791)
- [面试 HTTP ，99% 的面试官都爱问这些问题](./Network%20Protocol/面试%20HTTP%20，99%%20的面试官都爱问这些问题.pdf)

### OAuth2
- [The OAuth 2.0 Authorization Framework](./JAVA/Microservice/The%20OAuth%202.0%20Authorization%20Framework.pdf)
- [理解OAuth 2.0（阮一峰）](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)
- [OAuth 2.0 的一个简单解释（阮一峰）](http://www.ruanyifeng.com/blog/2019/04/oauth_design.html)
- [OAuth 2.0 的四种方式](http://www.ruanyifeng.com/blog/2019/04/oauth-grant-types.htmlx)
- [深度剖析OAuth2和微服务安全架构](./JAVA/Microservice/深度剖析OAuth2和微服务安全架构.pdf)

### WebSocket
- [WebSocket 教程（阮一峰）](http://www.ruanyifeng.com/blog/2017/05/websocket.html)

## Regular Expression
- [正则表达式30分钟入门教程](https://www.barretlee.com/tools/reg/)
- [最全的常用正则表达式大全（ZXIN）](https://www.cnblogs.com/zxin/archive/2013/01/26/2877765.html)

## Git
- [开源许可证教程（阮一峰）](http://www.ruanyifeng.com/blog/2017/10/open-source-license-tutorial.html)
- [How does git work internally](https://medium.com/@shalithasuranga/how-does-git-work-internally-7c36dcb1f2cf)

## Data Visualization
- [数据可视化入门教程](https://www.yuque.com/mo-college/beginner-tutorial)

## TensorFlow
- [TensorFlow-Course](https://github.com/open-source-for-science/TensorFlow-Course)

## System Software
- [Writing system software: code comments](http://antirez.com/news/124)
- [如何降低软件的复杂性？（阮一峰）](http://www.ruanyifeng.com/blog/2018/09/complexity.html)

## 云计算
- 阿里巴巴云原生实践十五讲【[PDF](./Others/阿里巴巴云原生实践十五讲.pdf)】

### 云原生
- [云原生技术公开课](https://edu.aliyun.com/roadmap/cloudnative)
  - 阶段1:云原生技术基础
    - [第一讲：云原生简介](./云原生/云原生技术公开课/阶段1：云原生技术基础/第一讲：云原生简介.md)
    - [第二讲：容器的基本概念](./云原生/云原生技术公开课/阶段1：云原生技术基础/第二讲：容器的基本概念.md)
    - [第三讲：Kubernetes核心概念](./云原生/云原生技术公开课/阶段1：云原生技术基础/第三讲：Kubernetes核心概念.md)

### k8s
- [Kubernetes教程](https://www.kuboard.cn/learning/)

## 微服务
- [微服务架构的理论基础 - 康威定律](https://yq.aliyun.com/articles/8611?do=login&spm=5176.12901015.0.i12901015.43ea525cSsiTVp)
- [微服务架构技术栈选型手册](https://www.infoq.cn/article/micro-service-technology-stack/)【[PDF](./JAVA/Microservice/微服务架构技术栈选型手册.pdf)】

## 分布式系统
- [初识分布式系统](http://www.hollischuang.com/archives/655)

### 分布式事务

- [聊聊分布式事务，再说说解决方案](./JAVA/Microservice/聊聊分布式事务，再说说解决方案.pdf)
- [关于分布式事务、两阶段提交协议、三阶提交协议](http://www.hollischuang.com/archives/681)
- [关于分布式事务、两阶段提交、一阶段提交、Best Efforts 1PC模式和事务补偿机制的研究](https://blog.csdn.net/bluishglc/article/details/7612811)
- [RocketMQ 4.3 正式发布，支持分布式事务](https://www.infoq.cn/article/2018/08/rocketmq-4.3-release)
- [XA 事务处理](https://www.infoq.cn/article/xa-transactions-handle)
- [分布式事务如何实现？深入解读 Seata 的 XA 模式](https://developer.51cto.com/art/202004/615530.htm?mobile)

## Web安全
- [Web Security（斯坦福大学公开课）](https://web.stanford.edu/class/cs253/)

## 系统架构

- [网站架构](https://www.yuque.com/docs/share/077f7c11-876f-46fe-8d2a-95dc9165b63d)

## Outside of technology

- [这几年的脚印（徐宥）](https://blog.youxu.info/2006/10/08/%E8%BF%99%E5%87%A0%E5%B9%B4%E7%9A%84%E8%84%9A%E5%8D%B0/)
- [4 年前端狗，2 年 CTO（Scott）](http://www.imooc.com/article/12703)
- [大龄程序员肉翻记录【一】（JavaNerd）](http://www.cnblogs.com/javanerd/p/7508399.html)
- [大龄程序员肉翻记录【二】（JavaNerd）](http://www.cnblogs.com/javanerd/p/7509819.html)
- [写给开发者的谷歌技术面试终极通关指南](https://www.infoq.cn/article/tl34RPwesHzhQfC0_Vid)
- [不止代码](https://alitech-private.oss-cn-beijing.aliyuncs.com/1530517140411/Codelife.pdf?Expires=1560959532&OSSAccessKeyId=LTAIqKGWQyF6Vd3W&Signature=gdxO5C6BVwxFFBh9H9Leodk0bLU%3D)[【PDF】](/Others/Codelife.pdf)
- [How to Use the Feynman Technique to Learn Faster (With Examples)](https://collegeinfogeek.com/feynman-technique/)
- [阿里工程师的自我修养](./Others/阿里工程师的自我修养.pdf)
- [毕玄：我在阿里的十年技术感悟](./Others/毕玄：我在阿里的十年技术感悟.pdf)
