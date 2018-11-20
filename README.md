## MyBook
* [`Introduction`](README.md)
* 面试准备
    * [`Tomcat`相关](/docs/tomcat.md)
        * [`Web`项目的启动过程](/docs/Tomcat/webStart.md)
        * [`Tomcat`的架构](/docs/Tomcat/tomcatSystem.md)
        * [`nginx`的原理](/docs/Tomcat/nginx.md)
        
    * [`JVM`相关](/docs/jvm.md) 
        * [`java`对象生命周期](/docs/jvm/objecttime.md) 
        * [垃圾回收过程](/docs/jvm/gc.md)
        * [垃圾回收器](docs/jvm/gcmachine.md)
        * [垃圾回收算法](docs/jvm/solutions.md)
        * [类加载机制](docs/jvm/classload.md)
        * [`Integer i=1`发生了什么](docs/jvm/Q1.md)
        * [`Java`的四种引用](docs/jvm/Q2.md)
    * [`JDK`有关](/docs/jdk.md) 
        * [多线程有关](/docs/jdk/multithread.md) 
        * [`synchronized`和`reentrantLock`的区别](/docs/jdk/Q1.md)
        * [`Integer` 缓存数据的范围](/docs/jdk/Q2.md)
        * [`java`作用符及其权限范围](/docs/jdk/Q3.md)
        * [序列化和反序列化](/docs/jdk/Q4.md)
        * [`JDK1.8` 函数式编程](/docs/jdk/Q5.md)
        * [集合类](/docs/jdk/Q6.md)
        * [`countdownlatch`](/docs/jdk/Q7.md)
        * [`Java IO`](/docs/jdk/Q8.md)
        * [红黑树的左右旋转](/docs/jdk/Q9.md)
        * [`FutureTask`的实现原理](/docs/jdk/Q10.md)
        * [`Java`为什么不用多继承](/docs/jdk/Q11.md)
        * [按值传递，按引用传递](/docs/jdk/Q12.md)
        * [线程池](/docs/jdk/Q13.md)
        * [`String` 和 `StringBuilder`](/docs/jdk/Q14.md)
        * [匿名类](/docs/jdk/Q15.md)
        * [静态方法怎么调用非静态方法](/docs/jdk/Q16.md)
        * [怎么自定义`String`类型](/docs/jdk/Q17.md)
        * [`Object`类下面的方法](/docs/jdk/Q18.md)
        * [接口和抽象类的区别](/docs/jdk/Q19.md)

    * [数据库相关](/docs/DataBase.md) 
        * [索引](/docs/database/index.md)
        * [事务](/docs/database/transaction.md)
        * [慢`SQL`优化](/docs/database/optimizationSql.md)
        * [引擎](/docs/database/engine.md)
        * [`MySQL`主从复制场景问题](/docs/database/binlog.md)
        * [`Mysql`存储记录的数据结构](/docs/database/data.md)
        * [数据库三大范式](/docs/database/fansi.md)
        * [连接](/docs/database/connect.md)
        * [`SQL`编译的过程](/docs/database/Q1.md)
        * [崩溃恢复过程](/docs/database/Q2.md)
        * [`count(*)`和`count(1)`的区别](/docs/database/Q3.md)
    * [`Spring`](/docs/Spring.md) 
        * [事务](/docs/Spring/transaction.md)
        * [`Spring`特点](/docs/Spring/different.md)
        * [`BeanFactory`是什么](/docs/Spring/BeanFactory.md)
        * [`Spring`怎么加载配置文件](/docs/Spring/loadxml.md)
        * [`mybatis`、`hibernate`区别](/docs/Spring/mybatis.md)
        * [`SpringMVC`工作流程](/docs/Spring/mvc.md)
        * [`Spring`容器的启动过程](/docs/Spring/container.md)
        * [`Spring`注解相关](/docs/Spring/Q1.md)
    * [设计模式](/docs/mvc.md)
        *  [单例模式](/docs/designtype/Q1.md)
        *  [代理模式](/docs/designtype/Q2.md)
        *  [适配器模式](/docs/designtype/Q3.md)
        *  [工厂模式相关](/docs/designtype/Q4.md)
        *  [策略模式相关](/docs/designtype/Q5.md)
    * [操作系统](/docs/os.md)
        * [关于赋值的原子性](/docs/os/Q1.md)
        * [系统中断](/docs/os/Q2.md)
        * [常见`Linux`命令](/docs/os/Q3.md)
        * [`Java`线程和`OS`中的线程的关系](/docs/os/Q4.md)
        * [实现`LRU`](/docs/os/Q5.md)
        * [线程状态及转换](/docs/os/Q6.md)
        * [进程的通信方式](/docs/os/Q7.md)
        * [`CPU`的执行方式](/docs/os/Q8.md)
        * [缓存更新的算法](/docs/os/Q9.md)
        * [虚拟内存](/docs/os/Q10.md)
        * [信号量`PV`原语](/docs/os/Q11.md)
        * [`Linux`内存结构](/docs/os/Q12.md)
        * [僵尸进程和孤儿进程](/docs/os/Q13.md)
    * [中间件相关](/docs/middle.md)
        * [`Redis`的一些问题](/docs/middle/redis.md) 
        * [`cap`为什么只能`3`选`2`](/docs/middle/Q1.md)
        * [具体的分布式锁](/docs/middle/Q2.md)
        * [负载均衡](/docs/middle/Q3.md)
        * [`MQ`相关](/docs/middle/mq.md)
        * [一致性`hash`](/docs/middle/hash.md)
        * [`hadoop`相关](/docs/middle/hadoop.md)
        
    * [网络相关](/docs/network.md)
        * [`DNS`解析域名过程](/docs/network/dns.md)
        * [网络分层](/docs/network/osi.md)
        * [三握四挥](/docs/network/three.md)
        * [`cookie`和`session`的区别](/docs/network/cookie.md)
        * [`tcp` 与 `udp` 区别](/docs/network/tcp.md)
        * [`http` 与 `https` 区别](/docs/network/http.md)
        * [怎么查看占用了端口号的程序的可执行文件的位置](/docs/network/Q1.md)
        * [`nio`与`bio`的区别](/docs/network/Q2.md)
        * [`http`状态码](/docs/network/Q3.md)
        * [常用的端口号](/docs/network/Q4.md)
* 面试代码
    * [多线程](/docs/multithread.md)
        * [线程池](/docs/multithread/threadpool.md) 
    * [笔试模板](/docs/writtenexamination.md)
    
* 算法
    * [数组](/docs/array.md)
        * [一个二维矩阵进行逆置操作，也就是行变列列变行](/docs/array/Q1.md) 
        * [手写快排](/docs/array/Q2.md)
        * [对角线打印`4*4`的矩阵](/docs/array/Q3.md)
        * [把`1`到`n`块钱，等概率分给`n`个人](/docs/array/Q4.md)
        * [在`a[n]`数组找第`K`大的数](/docs/array/Q5.md)
        * [给定一个递增数组循环位移之后的数组，以及数`x`，查找该数的位置](/docs/array/Q6.md)
        * [蛇形打印`n*n`的矩阵](/docs/array/Q7.md)
        * [合并多个区间的方法](/docs/array/Q8.md)
        * [找出数组中出现此数大于等于4次的数](/docs/array/Q9.md)
        * [一个有序数组，求能用这个数组能组成度二叉搜索树的个数](/docs/array/Q10.md)
        * [两个有序数组，找出他们的中位数](/docs/array/Q11.md)
        * [有序数组被旋转过后求最小点](/docs/array/Q12.md)
        * [一个无序数组里面怎么查找出现次数大于数组长度一半的数](/docs/array/Q13.md)
        * [移动字符串](/docs/array/Q14.md)
        * [数组的度](/docs/array/Q15.md)
        * [`LRU`的实现](/docs/array/Q16.md)
        * [连续子数组最大的和](/docs/array/Q17.md)
        * [旋转数组](/docs/array/Q18.md)
        * [无序数组中找出连续的数中第一个缺失的数字](/docs/array/Q19.md)
        * [迪杰斯特拉算法](/docs/array/Q20.md)
        * [`1`到`N`的所有数字，按照字典序打印，怎么做](/docs/array/Q21.md)
        * [无序数组求中位数](/docs/array/Q22.md)
    * [树](/docs/tree.md)
    
        * [两个节点的最近公共父节点](/docs/tree/Q1.md)
        * [一张纸横着对折`N`次，输出凹凸的序列](/docs/tree/Q2.md)
        * [设计一个数据库的表来存储树形结构](/docs/tree/Q3.md)
        * [层次遍历二叉树](/docs/tree/Q4.md)
        * [二叉树，叶子节点是数，其他是符号，给出二叉树定义和给定根节点时二叉树所计算出来的值](/docs/tree/Q5.md)
        * [二叉树中序非递归遍历](/docs/tree/Q6.md)
        * [手写字典树实现，包括了查询和插入方法](/docs/tree/Q7.md)
        * [二叉树非递归后序遍历](/docs/tree/Q8.md)
    * [字符串](/docs/string.md)
        * [大数相加](/docs/string/Q1.md)
        * [判断括号匹配](/docs/string/Q2.md)
        * [最长公共字串](/docs/string/Q3.md)
        * [找出所有可能的IP地址组合，比如`192168111`](/docs/string/Q4.md)
        * [寻找字符串中最大回文子串](/docs/string/Q5.md)
    * [栈和队列](/docs/stackandqueue.md)
        * 
    * [链表问题](/docs/linkedlist.md)
        * [反转部分单向链表](/docs/linkedlist/Q1.md)
        * [从单链表或双链表中删除第K个节点](/docs/linkedlist/Q2.md)
        * [两个单链表相交的系列问题](/docs/linkedlist/Q3.md)
        * [如何判断链表有环](/docs/linkedlist/Q4.md)
        * [复杂链表的复制](/docs/linkedlist/Q5.md)
        * [一个链表，奇数升序，偶数降序，变成一个全升序的链表](/docs/linkedlist/Q6.md)
    * [递归和动态规划](/docs/dp.md)
        * [斐波那契数列](/docs/dp/Q1.md)
        * [换钱的最小货币数](/docs/dp/Q2.md)
        * [换钱的方法数](/docs/dp/Q3.md)
    * [剑指`offer`] (/docs/offer.md)
        *  [输入某二叉树的前序遍历和中序遍历的结果，请重建出该二叉树](/docs/offer/Q1.md)
        * [使用两个栈来实现队列](/docs/offer/Q2.md)
        * [数组的最小数字](/docs/offer/Q3.md)
        * [矩阵放置](/docs/offer/Q4.md)
        * [二进制中`1`的个数](/docs/offer/Q5.md)
        * [树的子结构](/docs/offer/Q6.md)
        * [顺时针打印矩阵](/docs/offer/Q7.md)
        * [包含`min`函数的栈](/docs/offer/Q8.md)
        * [栈的压入、弹出序列](/docs/offer/Q9.md)
        * [复杂链表的复制](/docs/offer/Q10.md)
        * [二叉树转化为双向链表](/docs/offer/Q11.md)
        * [字符串的排列](/docs/offer/Q12.md)
        * [最小的`k`个数](/docs/offer/Q13.md)
        * [连续子数组的最大和](/docs/offer/Q14.md)
        * [从`1`到`n`整数中`1`出现的次数](/docs/offer/Q15.md)
        * [把数组排序成最小的数](/docs/offer/Q16.md)
        * [丑数](/docs/offer/Q17.md)
        * [数组中的逆序对](/docs/offer/Q18.md)
        * [两个链表的第一个公共结点](/docs/offer/Q19.md)
        * [数字在二分搜索中出现的次数](/docs/offer/Q20.md)
        * [平衡二叉树](/docs/offer/Q21.md)
        * [数组中只出现一次的数字](/docs/offer/Q22.md)
        * [左旋转字符串](/docs/offer/Q23.md)
        * [翻转句子](/docs/offer/Q24.md)
        * [圆圈内最后剩余的数](/docs/offer/Q25.md)
        * [特殊求和的方法](/docs/offer/Q26.md)
        * [不用加法实现加法运算](/docs/offer/Q27.md)
        * [数组中重复的数字](/docs/offer/Q28.md)
    * [图] (/docs/map.md)
        *  [朋友之间的点对点关系用图维护，怎么判断两人是否是朋友，并查集，时间复杂度](/docs/map/Q1.md) 
    * [综合](docs/total.md)
        * [`Top k `问题](/docs/total/topK.md) 
        * [有一个函数，输出`1`的概念是百分之三十，输出`0`的概念是百分之七十，使用这个函数等概率输出`100`以内的数字](/docs/total/Q1.md) 
        * [秒杀系统的实现](/docs/total/Q2.md)
        * [防爬虫系统的实现](/docs/total/Q3.md)
        * [`16`个球队中随机选`2`个，在大量选取后，越强的队越容易被选中](/docs/total/Q4.md)
        * [知道多线程吧。用过`CountDownLatch`吗？来写个程序，算`1！+2！+3！+4！+5！`，用`CountDownLatch`来做](/docs/total/Q5.md)
        * [问`43`亿大的文件里顺序存储`32`位的整数，怎么查找出现次数大于`2`的数](/docs/total/Q6.md)
        * [排查界面无法显示的问题](/docs/total/Q7.md)
        * [实现关键字输入提示](/docs/total/Q8.md)
        * [`10g`文件，只有`2g`内存，怎么查找文件中指定的字符串出现位置](/docs/total/Q9.md)
        * [`100w`个数，怎么找到前`1000`个最大的](/docs/total/Q10.md)
        * [十亿个数的集合和`10w`个数的集合，如何求它们的交集](/docs/total/Q11.md)
        * [数据很大内存放不下怎么办](/docs/total/Q12.md)
        * [头条面试](/docs/total/Q13.md)

* [秋招总结](/docs/review/reviewforAutumnRecruit.md)
* [春招总结](/docs/review/reviewforSpringRecruit.md)
* [总结](/docs/review/reviewRecruit.md)
* 书籍阅读
    * [`Spring`源码深度解析](/docs/)
    * [深入理解`Java`虚拟机](/docs/) 
    * [`Redis`设计与实现](/docs/)
    * [高性能`MySQL`](/docs/mysql) 


