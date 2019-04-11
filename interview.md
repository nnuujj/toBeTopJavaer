## 一、基础篇

### 面向对象

#### 什么是面向对象

[面向对象、面向过程](/basics/java-basic/object-oriented-vs-procedure-oriented.md)

[面向对象的三大基本特征](/basics/java-basic/characteristics.md)和[五大基本原则](/basics/java-basic/principle.md)

#### 值传递

[值传递、引用传递](/basics/java-basic/java-pass-by.md)

[为什么说Java中只有值传递](/basics/java-basic/java-pass-by.md)

#### 封装、继承、多态

[什么是多态](/basics/java-basic/polymorphism.md)、[方法重写与重载](/basics/java-basic/overloading-vs-overriding.md)

Java的继承与实现

[Java的继承与组合](/basics/java-basic/inheritance-composition.md)

[构造函数与默认构造函数](/basics/java-basic/constructor.md)

[类变量、成员变量和局部变量](/basics/java-basic/variable.md)

[成员变量和方法作用域](/basics/java-basic/scope.md)

### Java基础知识

#### 基本数据类型

[7种基本数据类型：整型、浮点型、布尔型、字符型](/basics/java-basic/basic-data-types.md)

[整型中byte、short、int、long的取值范围](/basics/java-basic/integer-scope.md)

[什么是浮点型？](/basics/java-basic/float.md)

[什么是单精度和双精度？](/basics/java-basic/single-double-float.md)

[为什么不能用浮点型表示金额？](/basics/java-basic/float-amount.md)

#### 自动拆装箱

[什么是包装类型、什么是基本类型、什么是自动拆装箱](/basics/java-basic/boxing-unboxing.md)

[Integer的缓存机制](/basics/java-basic/integer-cache.md)

#### String

[字符串的不可变性](/basics/java-basic/final-string.md)

[JDK 6和JDK 7中substring的原理及区别](/basics/java-basic/substring.md)

replaceFirst、replaceAll、replace区别、

[String对“+”的重载](/basics/java-basic/string-append.md)

[字符串拼接的几种方式和区别](/basics/java-basic/string-concat.md)

String.valueOf和Integer.toString的区别、

[switch对String的支持](/basics/java-basic/switch-string.md)

字符串池、常量池（运行时常量池、Class常量池）、intern

#### 熟悉Java中各种关键字

transient、instanceof、volatile、synchronized、final、static、const 原理及用法。

#### 集合类

[集合面试题](https://www.jianshu.com/p/e6076b43fdfb)

#### 枚举

[枚举的用法、枚举的实现、枚举与单例、Enum类](https://www.jianshu.com/p/174467006572)

[Java枚举如何比较](https://www.w3cschool.cn/java/java-enum-compare.html)

[switch对枚举的支持](https://blog.csdn.net/veryitman/article/details/7947640)

[枚举的序列化如何实现](/basics/java-basic/enum-serializable.md)

[枚举的线程安全性问题](https://www.cnblogs.com/z00377750/p/9177097.html)

#### IO

[字符流、字节流、输入流、输出流](https://www.jianshu.com/p/aea76bc0e6d1)

[BIO、NIO和AIO的区别、三种IO的用法与原理](https://bbym010.iteye.com/blog/2100868)

#### Java反射、动态代理、泛型、注解

[Java反射、动态代理、泛型、注解](https://www.jianshu.com/p/aaf8594e02eb)

[Java反射和动态代理源码分析](https://www.toutiao.com/i6672974675737313805/)

[注解](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486438&idx=1&sn=546501badafc016b3b864e0107ea9c49&chksm=ebb7424adcc0cb5c95e2c3b7a6a899e40709d5228212e3d3169b3078f66e6984cbf8a3ce16b5&mpshare=1&scene=1&srcid=&key=0c3894978f9d5708c80a9c83139827c9709a462c370c29280b828a06ec5d5298cbc5bb7463b5f978ffdb31a0b3f950f7aef4525d8032d38fc91fa2286c628960be371ad8b5237ab08145c1849d49729c&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

[Spring常用注解](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247485477&idx=1&sn=a1e35f607931a4d0910b8388bc123054&chksm=ebb74189dcc0c89f3becdc640c4682c886d38fbbf633268eff010e0dd0401b6acb5f168bb5c3&mpshare=1&scene=1&srcid=&key=60b42fe1b11cc8f7dea35f2e41d964ec5486db6e2f4b3b8b9f3db89b600d532558fcfeb2bb38aef98e0c896091c05a723a62eb5deed9baf37cb96f428b8cb9f8d68633c030d9c3e70cf83f337db5a83a&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

[Spring Boot常用注解](https://www.cnblogs.com/Fairy-02-11/p/8158978.html)

#### 序列化

[什么是序列化与反序列化、为什么序列化、序列化底层原理、序列化与单例模式、protobuf、为什么说序列化并不安全](https://blog.csdn.net/w372426096/article/details/83503619)

#### 单元测试

junit

#### 异常

[异常类型、正确处理异常、自定义异常](http://www.importnew.com/26613.html)

### Java并发编程

[Java 高并发综合](https://mp.weixin.qq.com/s?__biz=MjM5NzMyMjAwMA==&mid=2651479341&idx=2&sn=44e59ddb6b534503d8443eaa9a2fd213&chksm=bd2531528a52b8443641b53ab550327a898a7e11eceecb44a5ad385697b308ec10714322ac6a&mpshare=1&scene=1&srcid=0411ddLjbb5AjSFvyObyUAlY&key=0c3894978f9d57084e9f2f9a69768f0dcffe1cbe655b4e0cba6f7b8eb52b80067b5e51ec7518afb405f907d9bf623de69031ee3b3dc771ab78d692404ff93af311a1d5151519e68dea5d2bce93dcfcde&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

[并发编程](https://www.jianshu.com/p/01188fa8e511)

[Java多线程](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486463&idx=1&sn=417fb34ff5f5a7d44e89cb90aeddf3ef&chksm=ebb74253dcc0cb45a34bc28ae8c1e558e5d4c33a4993f71ebac4ff61ef08d786d7c4c0b48e10&mpshare=1&scene=1&srcid=&key=60b42fe1b11cc8f7807e44b9793907f6f7ef37a325ddf1095922954894c8644e915d2399fab6037fc1b7be92356e02925c263e224cf339fa0ab26a3482e2b1aa829d59e3f609f3af4fcbe294fb313ca0&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

### 框架知识

[SSM框架相关基础面试题整理](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486437&idx=1&sn=3cf5d4b5fbb9201a128575a8d093be1c&chksm=ebb74249dcc0cb5f7764fca43a049ecf155c3a6eb1914292403227d94908dec85bf0ab4baa4e&mpshare=1&scene=1&srcid=&key=99a9a67e26762fb3d916db77df164d3c581d6f8397f2e59c2d14421d67f45d1f8cb5a5043825201f38cd1074dc98d896f37a7d4849857c690eda573d9cd2f702c7aa00d393284ab1492173278991b89b&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

#### Servlet

[生命周期、线程安全问题](https://www.cnblogs.com/Java3y/archive/2018/03/05/8410699.html)

[filter和listener](https://www.cnblogs.com/doit8791/p/4209442.html)

[写一个迷你版的Tomcat](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486166&idx=1&sn=246a9a5c05b77ae226de5de998821a9e&chksm=ebb7437adcc0ca6c2e822caa440fd455305767948d5a2af2bc1205243fbd431441ded892614b&mpshare=1&scene=1&srcid=&key=bcb2a02128f6508d850e4d3b4d953ca07c0c69879bceabca0af28ca2d8eec5c84c8845ab74e5950580d9ef7d1983b6ad222c2a878fbd582a0e5bf063e364816040ac8cd771ad52f75053cf4d3cb57637&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

#### Mybatis

[面试题](https://blog.csdn.net/a745233700/article/details/80977133)

[代码自动生成](https://www.jianshu.com/p/fcd66129f6e6)

[缓存机制](https://blog.csdn.net/z742182637/article/details/72569014)

[Mybatis初始化机制详解](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247485809&idx=1&sn=9ed89609a9937cace029900eb8aa1508&chksm=ebb740dddcc0c9cb538334662be701ac6395adfe40a0809175dc48260416e0d5b31c01e07329&mpshare=1&scene=1&srcid=&key=bcb2a02128f6508d0b64cf83dfe846eb32d9b8f2c61b70615bbb60f98321f3263fa5bb2e42baa0c546f953b2dd985fa4931add42abd0229fb02abdacd23d8971c240b88b8ba3493476f3d827ee553ae4&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

[从 0 开始手写一个 Mybatis 框架](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247485968&idx=1&sn=707e4dbb6096ccf5d5e7ae89f6afc866&chksm=ebb743bcdcc0caaa94f88248a0e7c5cea0763120ddaa17c777432063da9406535759499ddad3&mpshare=1&scene=1&srcid=&key=970da011e7204cee3bcd5e9b62e68150ff7b42f5df9ea78d7f66e87521996eec727c7ed3487e7845b7a69a4c274eb8275ef56700d61d762bd60a805a7d2721b20e10bec0a39ced81e0134ad8916f9560&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

#### Spring 

[Bean的初始化](https://www.cnblogs.com/yxh1008/p/6012230.html)

[AOP原理](http://www.importnew.com/24305.html)

[实现Spring的IOC](https://www.cnblogs.com/fingerboy/p/5425813.html)

[Spring四种依赖注入方式](https://blog.csdn.net/elishjun/article/details/77104397)

[Spring IOC基于注解启动分析](https://www.toutiao.com/a6674737145250316803/)

[Spring事务](https://www.cnblogs.com/yixianyixian/p/8372832.html)

#### Spring MVC

[SpringMVC执行过程](https://www.toutiao.com/a6677171511918330380/)

#### Spring Boot

[Spring Boot 2.0、起步依赖、自动配置](https://www.jianshu.com/p/63ad69c480fe/)

[Spring Boot启动机制](https://www.cnblogs.com/hjwublog/p/10332042.html)

[自己实现一个starter](https://www.cnblogs.com/hjwublog/p/10335464.html)

#### RPC框架

[从 0 开始手写实现一个 RPC 框架](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486014&idx=1&sn=255288c8df2286404af3cc33c0b163b5&chksm=ebb74392dcc0ca84a66832ed1bb5cd6ad2bb6dfc60ffbe91836c2a78b12faff2645d7479dfe5&mpshare=1&scene=1&srcid=&key=970da011e7204cee997f1ec16d248121e4e82f0ce0ed9ee6aec92bb295eda88e54d0072d157f1f231a0eb71dc4ab823835896962e97f22de979fc7b9d1643c191c0f1fbf45e752f569dc93d59b2a060e&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

#### OAuth2

[OAuth2知识](http://www.ruanyifeng.com/blog/2019/04/oauth_design.html)
[OAuth授权方式](http://www.ruanyifeng.com/blog/2019/04/oauth-grant-types.html)

### Spring Cloud

[Spring Cloud知识](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247483712&idx=1&sn=4cd88761830428a2e485ac4c2cf120f9&chksm=fba6e943ccd16055344222ce9c794358e1a4a84fdf4263eaa7c91e9756597bd06e49f9b390cb&mpshare=1&scene=1&srcid=0411TzBJkU7JF4sotJVZVZMz&key=bcb2a02128f6508d4feccc227960ba0b57fa79a4d70adb6e2bfe15800c88b13c652b60cfa90aa69264ecdb1ada66cd0c464bb1a10a7e02b5eceb0d3b06a8b1ddd605a79b61fb2318fa0d5a2c6e369e0d&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=1PYBVSfmnr6DibAX881eoVK16HfbL6y2K94MutFzTjXKgU7VFdcaGipuLCCZOA90)

#### 分库分表

[分库分表](https://mp.weixin.qq.com/s?__biz=MzUzMTA2NTU2Ng==&mid=2247486591&idx=1&sn=53b9bc2c40b4a02a4cbed93c481ab9a0&chksm=fa4973cecd3efad8c41dfc3984abbbad34fafb9495377ecb0144a7632ece2e5cd5ee85a455ed&scene=0&xtrack=1&key=60b42fe1b11cc8f7eeddff8133a9db8eedb31fe6c173ac4fc103035bf16197e77a499be22fd0df021acdfd9ff62f0c4f718f5abc62b572de20c92f6a8a01e449e0bbdbc0eb8f8b2de1a7088613ceb6ef&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=1PYBVSfmnr6DibAX881eoVK16HfbL6y2K94MutFzTjXKgU7VFdcaGipuLCCZOA90)

### JVM

#### JVM原理

[JVM原理](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247485779&idx=1&sn=06d214b87db425ddbe4e7c16b3106734&chksm=ebb740ffdcc0c9e9ddd271a4607e8a3dafc0630984fa3df021640fdbe1ce2a55a16c82d34393&mpshare=1&scene=1&srcid=&key=0c3894978f9d57080ee520f64c379207fe5bdad786d501beb3c9b0faa31b1174f75dcb3f605c0484a97b41b867892aceb9dba8d9933da96f92307b22ca447239ce0e6b0607eb5f67cb985413a2fbc416&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

#### 垃圾回收

GC算法：标记清除、引用计数、复制、标记压缩、分代回收、增量式回收

GC参数、对象存活的判定、垃圾收集器（CMS、G1、ZGC、Epsilon）

#### JVM参数及调优

-Xmx、-Xmn、-Xms、Xss、-XX:SurvivorRatio、

-XX:PermSize、-XX:MaxPermSize、-XX:MaxTenuringThreshold

#### 常用设计模式

[常用的设计模式汇总](https://mp.weixin.qq.com/s?__biz=MzI4MDYwMDc3MQ==&mid=2247486279&idx=1&sn=ec4246973da89afb66ef2e7fed1b0a55&chksm=ebb742ebdcc0cbfd73b2d70ef484d6abf37c58f136fdbbd31fafb364ba62b64ed6a4eecdda68&mpshare=1&scene=1&srcid=&key=60b42fe1b11cc8f743feb64d382553f90abfc1a56cafac7fe7ad7a69f380c6e877c4931702c04b061556e24093df4678e6001ea0cdb4ba1b5923e41e42fc935490f0b4a8cad87761bf50903a2a91aaf0&ascene=0&uin=MTU4OTc2MDgyMw%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.4+build(16E195)&version=12020110&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=9ImWiJUU9u8k8wocn4xLa0OSjA7ocf8jdQvN58zs2uALtW%2BhV40SMJQ8VXs87fGM)

### 网络编程知识

#### tcp、udp、http、https等常用协议

[tcp三次握手与四次关闭、OSI七层模型](https://www.cnblogs.com/qiaoconglovelife/p/5733056.html)

[tcp和udp的区别](https://www.cnblogs.com/xiaomayizoe/p/5258754.html)

[tcp粘包与拆包](https://blog.csdn.net/wxy941011/article/details/80428470)

[http中get和post区别](https://www.cnblogs.com/huaxingtianxia/p/5895236.html)

[常见的web请求返回的状态码](https://www.cnblogs.com/mengbin0546/p/9362617.html)
404、302、301、500分别代表什么

#### cookie 与 session

[cookie被禁用，如何实现session](https://blog.csdn.net/ai_shuyingzhixia/article/details/80778183)

#### 前后端token的安全机制

[接口签名验证](https://www.toutiao.com/a6266755667001114882/)

### 负载均衡

[Nginx+Tomcat负载均衡 (动静分离)](https://www.toutiao.com/a6631496390872662536/)

Nginx七层负载均衡

LVS四层负载均衡

#### Linux的常用命令

ps -eaf grep cat vi top 

### 数据库知识

#### MySql 执行引擎

[执行引擎](https://www.toutiao.com/a6509988920770429448/)

#### MySQL 执行计划

[如何查看执行计划，如何根据执行计划进行SQL优化](https://blog.csdn.net/ld395353765/article/details/81129710)

#### 索引

[Hash索引、B树索引（B+树、和B树、R树](https://blog.csdn.net/javawcj123/article/details/79824020)

#### 数据库锁

[行锁、表锁、使用数据库锁实现乐观锁](https://www.cnblogs.com/wmbg/p/6800354.html)

#### 连接

[内连接，左连接，右连接](https://www.cnblogs.com/zhaoyini/p/join.html)

#### 数据库主备搭建

[主备原理](https://blog.csdn.net/weixin_39445556/article/details/84302962)

#### 常用的nosql数据库

[redis](https://www.cnblogs.com/jasontec/p/9699242.html)

### 数据结构与算法知识

[数据结构和算法](http://blog.jobbole.com/110835/)

#### 排序算法

[排序](https://blog.csdn.net/hguisu/article/details/7776068/)

### 网络安全知识

#### XSS

[XSS的防御](https://www.jianshu.com/p/599fcd03fd3b)

#### CSRF

#### 注入攻击

[SQL注入、XML注入、CRLF注入](https://www.cnblogs.com/KevinGeorge/p/8250700.html)

#### 加密与解密

[对称加密、非对称加密、哈希算法、加盐哈希算法](https://www.jianshu.com/p/945ea7940e65)

MD5，SHA1、DES、AES、RSA、DSA

#### SSL、TLS，HTTPS

[SSL、TLS，HTTPS](https://blog.csdn.net/enweitech/article/details/81781405)

[用openssl签一个证书部署到apache或nginx](https://blog.csdn.net/hatmen2/article/details/81265593)

## 二、架构篇

### 分布式

[数据一致性、服务治理、服务降级](https://blog.csdn.net/guwei9111986/article/details/51649240)

#### 分布式事务

[2PC、3PC、CAP、BASE、 可靠消息最终一致性、最大努力通知、TCC](https://www.jianshu.com/p/16b1baf015e8)

#### 分布式文件系统

阿里OSS

#### 消息队列

[RabbitMQ](https://blog.csdn.net/qq_42629110/article/details/84965084)

[RocketMQ](https://www.jianshu.com/p/01cc72114c47)

## 前端

[VueJS](https://www.cnblogs.com/aimeeblogs/p/9501490.html)
