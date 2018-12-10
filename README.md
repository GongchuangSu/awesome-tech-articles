# Awesome Technical Articles [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome technical articles.

# Content
* [Java](#Java)
  * [并发](#并发)
  * [I/O](#I/O)
  * [单点登录](#单点登录)

* [JVM](#JVM)

* [Data Structures and Algorithms](#Data-Structures-and-Algorithms)

* [Spring](#Spring)

* [Database](#Database)
  * [Hibernate](#Hibernate)
  * [Mysql](#Mysql)

* [Linux](#Linux)
  * [Vim](#Vim)
  * [Shell](#Shell)

* [Nginx](#Nginx)

* [Docker](#Docker)

* [Tomcat](#Tomcat)

* [Message queue](#Message-queue)
  * [Kafka](#Kafka)

* [Continuous Integration](#Continuous-Integration)
  * [Jenkins](#Jenkins)

* [Front-End](#Front-End)
  * [Javascript](#Javascript)
  * [Jquery](#Jquery)
  * [Web application](#Web-application)

* [Network Protocol](#Network-Protocol)
  * [WebSocket](#WebSocket)

* [Regular Expression](#Regular-Expression)

* [Git](#Git)

* [Data Visualization](#Data-Visualization)

* [TensorFlow](#TensorFlow)

* [System Software](#System-Software)

* [Outside of technology](#Outside-of-technology)

## Java
- [从命名风格等方面解读阿里巴巴 Java 代码规范](https://www.ibm.com/developerworks/cn/java/deconding-code-specification-part-1/index.html)
- [从代码处理等方面解读阿里巴巴 Java 代码规范](https://www.ibm.com/developerworks/cn/java/deconding-code-specification-part-2/index.html)
- [Java 编程要点之并发（Concurrency）详解](https://waylau.com/essential-java-concurrency/#)

### 并发
- [还在疑惑并发和并行？（laike9m）](https://laike9m.com/blog/huan-zai-yi-huo-bing-fa-he-bing-xing,61/)

### I/O
- [Java中导入、导出Excel](https://www.cnblogs.com/jerehedu/p/4343509.html)

### 单点登录
- [八幅漫画理解使用JSON Web Token设计单点登录系统（John Wu）](http://blog.leapoahead.com/2015/09/07/user-authentication-with-jwt/)
- [JSON Web Token - 在Web应用间安全地传递信息（John Wu）](http://blog.leapoahead.com/2015/09/06/understanding-jwt/)

## JVM
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
- [Design patterns implemented in Java](https://java-design-patterns.com/)
- [RSA算法原理（一）](http://www.ruanyifeng.com/blog/2013/06/rsa_algorithm_part_one.html)
- [RSA算法原理（二）](http://www.ruanyifeng.com/blog/2013/07/rsa_algorithm_part_two.html)
- [Data Structures Reference](https://www.interviewcake.com/data-structures-reference)
- [图说设计模式](https://design-patterns.readthedocs.io/zh_CN/latest/index.html)
 
## Spring
- [Spring-aop 全面解析（从应用到原理）](https://juejin.im/post/591d8c8ba22b9d00585007dd)
- [IoC-spring 的灵魂](https://juejin.im/post/591d8c8ba22b9d00585007dd)
- [中小型互联网公司微服务实践](http://www.ityouknow.com/springcloud/2017/10/19/micro-service-practice.html)

## Database
### Hibernate
- [深入理解hibernate的三种状态](http://www.cnblogs.com/xiaoluo501395377/p/3380270.html)
- [hibernate缓存机制详细分析](http://www.cnblogs.com/xiaoluo501395377/p/3377604.html)

### Mysql
- [MySQL慢查询分析mysqldumpslow（kimi）](http://kimi.it/410.html)
- [送给DBA：把这个转给你的开发，对接工作不再吐血（陈芳志）](https://dbaplus.cn/news-11-2316-1.html)
- [MySQL 性能优化技巧（月光中的污点）](https://www.extlight.com/2017/10/07/MySQL-%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7/)[【PDF】](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Database/Mysql/MySQL%20%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7.pdf)
- [MySQL 实现主从复制（月光中的污点）](https://www.extlight.com/2018/03/12/MySQL-%E5%AE%9E%E7%8E%B0%E4%B8%BB%E4%BB%8E%E5%A4%8D%E5%88%B6/)[【PDF】](https://github.com/GongchuangSu/awesome-tech-articles/blob/master/Database/Mysql/MySQL%20%E5%AE%9E%E7%8E%B0%E4%B8%BB%E4%BB%8E%E5%A4%8D%E5%88%B6.pdf)

## Linux
- [UNIX Tutorial for Beginners](http://www.ee.surrey.ac.uk/Teaching/Unix/)
- [Linux的五个查找命令（阮一峰）](http://www.ruanyifeng.com/blog/2009/10/5_ways_to_search_for_files_using_the_terminal.html)
- [awk 入门教程](http://www.ruanyifeng.com/blog/2018/11/awk.html)
- [30 Examples for Awk Command in Text Processing](https://likegeeks.com/awk-command/)

### Vim
- [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/#)
- [简明 VIM 练级攻略](https://coolshell.cn/articles/5426.html)

### Shell
- [How to write practical shell scripts](https://likegeeks.com/write-shell-script/)

## Nginx
- [agentzh 的 Nginx 教程](http://openresty.org/download/agentzh-nginx-tutorials-zhcn.html)
- [什么是负载均衡](https://mp.weixin.qq.com/s/xvozZjmn-CvmQMAEAyDc3w)

## Docker
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

## Message queue
- [浅谈消息队列及常见的消息中间件](https://juejin.im/post/5b41fe36e51d45191252e79e)
### Kafka
- [Kafka快速入门](https://colobu.com/2014/08/06/kafka-quickstart/)

## Continuous Integration
- [持续集成是什么？（阮一峰）](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)
### Jenkins
- [GitLab 自动触发 Jenkins 构建](https://www.wolfcstech.com/2018/03/26/gitlab_trigger_jenkins_build/)

## Front-End
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
- [jQuery之jsonp跨域请求](https://www.cnblogs.com/chiangchou/p/jsonp.html)
- [四种常见的 POST 提交数据方式（Jerry Qu）](https://imququ.com/post/four-ways-to-post-data-in-http.html)

### Web application
- [前端组件化框架之路（民工精髓V）](https://github.com/xufei/blog/issues/19)
- [Web应用组件化的权衡（民工精髓V）](https://github.com/xufei/blog/issues/22)
- [Web应用的组件化（一）——基本思路（民工精髓V）](https://github.com/xufei/blog/issues/6)
- [Web应用的组件化（二）——管控平台（民工精髓V）](https://github.com/xufei/blog/issues/7)

## Network Protocol
- [互联网协议入门（一）（阮一峰）](http://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html)
- [互联网协议入门（二）（阮一峰）](http://www.ruanyifeng.com/blog/2012/06/internet_protocol_suite_part_ii.html)
- [理解OAuth 2.0（阮一峰）](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)
- [HTTPS协议图解](https://tls.ulfheim.net/)
- [HTTPS explained with carrier pigeons](https://medium.freecodecamp.org/https-explained-with-carrier-pigeons-7029d2193351)
- [DHCP 协议如何工作](https://www.benburwell.com/posts/how-does-dhcp-work/)
- [SSH原理与运用（一）：远程登录（阮一峰）](http://www.ruanyifeng.com/blog/2011/12/ssh_remote_login.html)
- [图解正向代理、反向代理、透明代理](http://blog.51cto.com/z00w00/1031287)
- [一分钟实现内网穿透（ngrok服务器搭建）](https://blog.csdn.net/zhangguo5/article/details/77848658)
- [What really happens when you navigate to a URL](http://igoro.com/archive/what-really-happens-when-you-navigate-to-a-url/)
- [DNS 原理入门（阮一峰）](http://www.ruanyifeng.com/blog/2016/06/dns.html)

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

## Outside of technology
- [这几年的脚印（徐宥）](https://blog.youxu.info/2006/10/08/%E8%BF%99%E5%87%A0%E5%B9%B4%E7%9A%84%E8%84%9A%E5%8D%B0/)
- [4 年前端狗，2 年 CTO（Scott）](http://www.imooc.com/article/12703)
- [大龄程序员肉翻记录【一】（JavaNerd）](http://www.cnblogs.com/javanerd/p/7508399.html)
- [大龄程序员肉翻记录【二】（JavaNerd）](http://www.cnblogs.com/javanerd/p/7509819.html)
