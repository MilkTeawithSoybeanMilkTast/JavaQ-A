# 滴滴一面

1.自我介绍

2.计算机网络，tcp和udp，tcp的可靠性，三次握手描述，为什么不能两次握手

3.http的状态码，http与https的区别

4.Redis：数据结构 String源码 顺序存储 链式存储 

5.排序算法（堆排序） 

6.ACDI 数据库并发操作的问题 隔离级别

7.聚簇索引 b树和b+树 两个引擎的区别

8.MySQL的索引为什么要用b+树

9.redis持久化方式(RDB和AOF)，两者的区别

10.缓存击穿解决方式 分布式锁 

11.聊项目（redis集群），遇到的难点

12.敲代码（爬楼梯）

# 滴滴二面

1.自我介绍

2.项目背景，角色，架构介绍

3.为什么要用分布式、微服务，怎么实现的

4.登录—>redis数据类型，持久化（RDB和AOF两个的区别），分布式锁有哪些

5.Dubbo的核心架构、实现

6.MySQL的存储，乐观锁和悲观锁的区别，索引类型，解释ACID

7.捶代码 ——> 二叉树合并 

8.100个球50个红的50个蓝的，怎么放到两个桶里保证随机取到某个桶里的红球概率最大？

解:  一个箱子放1个红球 另一个放49红球和50篮球 拿到红球概率=0.5(1+49/99)约等于0.75

9.课程、成绩、实习时长

10.面试者提问

# 字节二面

1.自我介绍

2.项目亮点、难点问题

3.为什么要用Dubbo？

4.类加载机制，为什么使用双亲委派机制/原理，jdk里什么打破了该机制，tomcat里什么打破了该机制。

5.JDBC怎么加载driver

6.Mybatis ORM是什么，怎么实现的（答到了反射）

7.反射机制

8.Spring IOC的实现机制

9.线程池的原理

10.Lock的可重用性原理

11.lru的cache如何实现/优化，lfu怎么设计

12.MySQL事务隔离级别，读已提交实现原理，可重复读实现原理，聚簇索引，辅助索引为什么存的是主键ID不存地址。

13.http 如何知道请求发完了，如果是流媒体如何知道..，http下载比较大的文件怎么设计下载，用程序实现怎么优化性能。

14.算法题（三个线程，分别输出1，2，3，让三个线程循环顺序输出/优化（生产者、消费者））

# 网易一面

1.自我介绍

2.HashMap	put和get的过程（说到了不安全）为啥

3.ConcurrentHashMap是怎么实现的

4.ReentrantLock和synchonized的区别，怎么实现的；什么是中断

5.CAS是怎么实现的

6.线程池的核心参数；线程池的关闭过程

7.JVM CMS垃圾回收过程、G1垃圾回收过程

8.Spring的IOC原理，解耦的原理

9.MySQL的索引类型；描述一下B+树

10.事务的隔离级别以及解决的问题

11.项目描述（亮点、难点）

12.Dubbo的工作原理，负载均衡（涉及的算法）

13.为什么要使用消息的队列，如何避免消息重发、漏发

# 跟谁学一面

1.自我介绍
2.公司是go，什么看法
3.项目负责部分介绍 
4.根据项目写的问:	同步索引库是怎样的 
5.session怎样保证不会泄露(现在考虑)
6.使用的cookie能存多少商品信息
7.redis存储大概是怎样的
8.为什么用到消息队列 大概说下
9.dubbo是怎样作用的 用的什么网络交互
10.tcp/ip是个怎么样的协议
11.IP协议怎么转化为ARP
12.一个udp数据包多大 
13.分布式锁是怎么实现的
14.雪崩了如何解决 
15.redis中rdb和aof区别 集群、主从
16.做题：
－括号匹配 （算法性能
－最长无重复子串
17.基于什么考虑做这个项目 还有别的吗
18.看啥书
19.开源项目写过没
20.反提问时间

# 快手一面

**面试官小姐姐也忒好了**

1、Java的集合类，HashMap、ConcurrentHashMap

2、什么是CAS，ABA问题是什么怎么解决

3、介绍一下JVM的内存模型，介绍一下垃圾回收

4、在新生代的垃圾回收算法，垃圾回收器CMS、G1

5、动态代理，Spring的代理模式怎么实现的

6、敲代码：

1）实现单例模式的懒汉式

问：volatile有什么用；static、final关键字的用法

2）单向链表二合一

问：时间、空间复杂度各是多少

7、MySQL事务隔离级别，什么是脏读、幻读、不可重复读，MVCC

8、b树和b+树的区别，为什么要用b+树，b+树索引的过程

9、什么情况下会索引失效

10、计算数量count*和count1的区别

11、mybatis 的 #是干嘛的

12、Zookeeper是怎么实现分布式锁的（扯到Redis分布式锁的实现）

13、Redis常用的数据结构、为什么是单线程的

14、什么是缓存击穿、持久化AOF和RDB

15、synchronized实现原理（扯到ReentrantLock的实现）

16、对后端业务方向的倾向

17、面试者提问

# 京东数科

1.项目架构
2.ioc原理
3.$和%区别
4.项目启动了几个容器
5.Arraylist初始容量 加载因子
  hashmap 初始容量 加载因子 
6.数据库 隔离级别 
7.sql优化
8.syncronized可以用在什么上 与lock区别
9.redis数据结构 应用
10.dubbo
11.垃圾回收