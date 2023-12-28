<a name="readme-top"></a>
<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->

<!-- PROJECT LOGO -->

<!-- 项目LOGO -->
<br />
<div align="center">
  <!-- <a href="http://note.grft.top"> -->
  <!--   <img src="https://xiyou-oss.oss-cn-shanghai.aliyuncs.com/mkdocs/logo.png" alt="Logo" width="480" height="270"> -->
  <!-- </a> -->

  <h3 align="center">算法设计</h3>

  <p align="center">
    <br />
    <a href="http://note.grft.top/算法设计/"><strong>探索文档 »</strong></a>
    <br />
  </p>
</div>

<!-- 目录 -->
<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#关于项目">关于项目</a></li>
    <li><a href="#什么是数据结构">什么是数据结构</a></li>
    <li><a href="#什么是计算机算法">什么是计算机算法</a></li>
    <li><a href="#技术目录">技术目录</a></li>
    <li><a href="#贡献">贡献</a></li>
    <li><a href="#许可证">许可证</a></li>
    <li><a href="#联系方式">联系方式</a></li>
    <li><a href="#鸣谢">鸣谢</a></li>
  </ol>
</details>

## 关于项目

整理了数据结构与基础算法，以及一些经典的LeetCode算法

公网资料、笔记地址请访问这里 

- 文档地址: [http://note.grft.top/算法设计/](http://note.grft.top/算法设计/)

其他相关技术可以访问我的博客，主页地址请访问这里

- 访问入口：[http://note.grft.top](https://mkdoc.grft.top)

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

## 什么是数据结构
数据结构是一种组织和存储数据的方式，它提供了对数据的操作和访问方法。

### 数组（Array）
数组是一种线性数据结构，由相同类型的元素按顺序存储。可以通过索引来访问数组中的元素，具有常数时间复杂度的随机访问。

### 链表（Linked List）
链表是由节点组成的线性数据结构，每个节点包含一个数据项和指向下一个节点的引用。链表可以是单链表、双链表或循环链表。

### 栈（Stack）
栈是一种后进先出（LIFO）的数据结构，只允许在栈顶进行插入和删除操作。常见的应用场景包括函数调用、表达式求值和撤销操作等。

### 队列（Queue）
队列是一种先进先出（FIFO）的数据结构，只允许在队尾插入元素，在队头删除元素。常见的应用场景包括任务调度、消息传递和缓冲区管理等。

### 树（Tree）
树是一种非线性数据结构，由节点和边组成。树的每个节点可以有多个子节点，但每个节点只有一个父节点。常见的树结构包括二叉树、堆和平衡树等。

### 图（Graph）
图是由节点和边组成的非线性数据结构，用于表示对象之间的关系。图可以是有向图或无向图，支持各种算法如最短路径、最小生成树和网络流等。

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

## 什么是计算机算法
计算机算法是一系列定义明确的指令，用于解决某个问题或执行某项任务。算法在计算机科学与编程领域中非常关键，它们能够让计算机执行各种复杂的数据处理工作。一个好的算法能够高效地运用计算资源，比如处理器时间和内存空间，来快速且准确地得出结果。

算法的设计和分析主要关注算法的正确性和效率。效率通常涉及算法的时间复杂度（即算法所需时间）和空间复杂度（即算法所需内存空间）。时间和空间复杂度通常用大O表示法（Big O notation）来描述，该表示法可以大致描述算法的规模增长对时间或空间需求的影响。

### 搜索算法
全文搜索算法，如倒排索引、布尔查询等，用于提供搜索引擎服务。
图搜索算法，如BFS（广度优先搜索）和DFS（深度优先搜索），用于社交网络图谱分析。

### 排序算法
快速排序、归并排序、堆排序等算法用于数据排序，提升用户界面和体验，如电商平台的商品列表排序。

### 压缩算法
赫夫曼编码、LZ77、LZ78、Deflate等用于数据压缩，在网络传输中减少数据量，提高效率。

### 加密算法
对称加密算法（如AES）、非对称加密算法（如RSA）和散列函数（如SHA系列）用于数据加密和认证，保障用户数据隐私和网络通信安全。

### 机器学习算法
监督学习算法（如决策树、支持向量机、神经网络），无监督学习算法（如K-Means、PCA）和强化学习算法在推荐系统、广告投放、语音识别等方面有着广泛应用。

### 推荐算法
协同过滤、基于内容的推荐、混合推荐算法等，用于个性化推荐，如电影、音乐、新闻等。

### 缓存算法
最近最少使用（LRU），最不经常使用（LFU）和随机替换（Random Replacement）等算法用于缓存管理，提高系统的性能和响应速度。

### 网络路由和流量控制算法
Dijkstra算法和A*算法用于网络路由的计算，而拥塞控制算法（如TCP/IP协议中的拥塞避免和控制算法）用于流量控制。

### 验证码算法
不同类型的验证码算法，如基于字符的验证码、图像识别验证码或逻辑问题验证码，用于防止自动化的垃圾邮件和网络攻击。

### 分布式系统算法
Paxos和Raft等一致性算法，用于分布式系统中的状态一致性和故障容错。

### 数据库查询优化算法
索引查询算法、查询执行计划生成算法，用于数据库性能优化。
上述算法只是互联网应用中常见算法的一部分，各个领域会根据具体需求和场景进行算法的选择、优化和实现。随着技术的发展和新算法的不断涌现，互联网应用中的算法也在不断进化。

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>


## 技术目录

[目录与大纲](index.md)

### 数据结构与算法

+ [数据结构详细笔记](https://github.com/rogertan30/Love-Leetcode)
+ [基础算法在线图示](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
+ [尚硅谷数据结构与算法](尚硅谷课件/笔记/尚硅谷图解Java数据结构和算法.pdf)

### LeetCode 案例分析

+ [LeetCode 官网](https://leetcode.cn/problemset/all/)

#### 动态规划

+ [动态规划之KMP字符匹配算法](算法汇总/动态规划系列/动态规划之KMP字符匹配算法.md)
+ [动态规划之博弈问题](算法汇总/动态规划系列/动态规划之博弈问题.md)
+ [动态规划之四键键盘](算法汇总/动态规划系列/动态规划之四键键盘.md)
+ [动态规划之正则表达](算法汇总/动态规划系列/动态规划之正则表达.md)
+ [动态规划设计之最长递增子序列](算法汇总/动态规划系列/动态规划设计之最长递增子序列.md)
+ [动态规划详解进阶](算法汇总/动态规划系列/动态规划详解进阶.md)
+ [团灭股票问题](算法汇总/动态规划系列/团灭股票问题.md)
+ [子序列问题模板](算法汇总/动态规划系列/子序列问题模板.md)
+ [抢房子](算法汇总/动态规划系列/抢房子.md)
+ [最优子结构](算法汇总/动态规划系列/最优子结构.md)
+ [最长公共子序列](算法汇总/动态规划系列/最长公共子序列.md)
+ [编辑距离](算法汇总/动态规划系列/编辑距离.md)
+ [背包问题](算法汇总/动态规划系列/背包问题.md)
+ [贪心算法之区间调度问题](算法汇总/动态规划系列/贪心算法之区间调度问题.md)
+ [高楼扔鸡蛋进阶](算法汇总/动态规划系列/高楼扔鸡蛋进阶.md)
+ [高楼扔鸡蛋问题](算法汇总/动态规划系列/高楼扔鸡蛋问题.md)


#### 算法与思维

+ [FloodFill算法详解及应用](算法汇总/算法思维系列/FloodFill算法详解及应用.md)
+ [twoSum问题的核心思想](算法汇总/算法思维系列/twoSum问题的核心思想.md)
+ [UnionFind算法应用](算法汇总/算法思维系列/UnionFind算法应用.md)
+ [UnionFind算法详解](算法汇总/算法思维系列/UnionFind算法详解.md)
+ [为什么推荐算法4](算法汇总/算法思维系列/为什么推荐算法4.md)
+ [二分查找详解](算法汇总/算法思维系列/二分查找详解.md)
+ [信封嵌套问题](算法汇总/算法思维系列/信封嵌套问题.md)
+ [几个反直觉的概率问题](算法汇总/算法思维系列/几个反直觉的概率问题.md)
+ [前缀和技巧](算法汇总/算法思维系列/前缀和技巧.md)
+ [区间交集问题](算法汇总/算法思维系列/区间交集问题.md)
+ [区间调度问题之区间合并](算法汇总/算法思维系列/区间调度问题之区间合并.md)
+ [双指针技巧](算法汇总/算法思维系列/双指针技巧.md)
+ [回溯算法详解修订版](算法汇总/算法思维系列/回溯算法详解修订版.md)
+ [字符串乘法](算法汇总/算法思维系列/字符串乘法.md)
+ [学习数据结构和算法的高效方法](算法汇总/算法思维系列/学习数据结构和算法的高效方法.md)
+ [常用的位操作](算法汇总/算法思维系列/常用的位操作.md)
+ [洗牌算法](算法汇总/算法思维系列/洗牌算法.md)
+ [滑动窗口技巧](算法汇总/算法思维系列/滑动窗口技巧.md)
+ [烧饼排序](算法汇总/算法思维系列/烧饼排序.md)
+ [算法学习之路](算法汇总/算法思维系列/算法学习之路.md)
+ [递归详解](算法汇总/算法思维系列/递归详解.md)

#### 高频面试案例

+ [koko偷香蕉](算法汇总/高频面试系列/koko偷香蕉.md)
+ [k个一组反转链表](算法汇总/高频面试系列/k个一组反转链表.md)
+ [LRU算法](算法汇总/高频面试系列/LRU算法.md)
+ [一行代码解决的智力题](算法汇总/高频面试系列/一行代码解决的智力题.md)
+ [二分查找判定子序列](算法汇总/高频面试系列/二分查找判定子序列.md)
+ [判断回文链表](算法汇总/高频面试系列/判断回文链表.md)
+ [合法括号判定](算法汇总/高频面试系列/合法括号判定.md)
+ [如何去除有序数组的重复元素](算法汇总/高频面试系列/如何去除有序数组的重复元素.md)
+ [子集排列组合](算法汇总/高频面试系列/子集排列组合.md)
+ [座位调度](算法汇总/高频面试系列/座位调度.md)
+ [打印素数](算法汇总/高频面试系列/打印素数.md)
+ [接雨水](算法汇总/高频面试系列/接雨水.md)
+ [最长回文子串](算法汇总/高频面试系列/最长回文子串.md)
+ [水塘抽样](算法汇总/高频面试系列/水塘抽样.md)
+ [消失的元素](算法汇总/高频面试系列/消失的元素.md)
+ [缺失和重复的元素](算法汇总/高频面试系列/缺失和重复的元素.md)

#### 工作中遇到的一些算法

+ [工作中遇到的一些算法](学习笔记/工作中遇到的一些算法.md)

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>

<!-- 贡献 -->

## 贡献

贡献是使开源社区成为一个如此令人惊叹的地方，以学习、激励和创造。您所做的任何贡献都将非常感谢。

如果您对使这个项目变得更好有建议，请 fork 该仓库并创建 pull request。您也可以打开一个带有“enhancement”标签的问题。不要忘记给这个项目点个星！再次感谢！

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>


<!-- 许可证 -->
## 许可证

根据 MIT 许可证进行分发。更多信息请参见 [LICENSE.txt](LICENSE)。

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>

<!-- 联系方式 -->
## 联系方式

关注我: [小昊子](https://github.com/worst001)

博客地址: [http://note.grft.top](http://note.grft.top)

项目链接: [https://github.com/worst001/note_algorithm](https://github.com/worst001/note_algorithm)

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>

## 鸣谢

因为仓库与文档的数量比较大，有些借鉴资料忘了在`参考文档`部分提及原作者与原仓库，若有疏漏请告诉，我及时补上。

所有引用的原资料都确认是开源认证，若有侵权请告知。

[尚硅谷系列教程资料](http://www.atguigu.com/opensource.shtml)

[https://www.cs.usfca.edu/~galles/visualization/Algorithms.html](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

[https://github.com/rogertan30/Love-Leetcode](https://github.com/rogertan30/Love-Leetcode)

[https://github.com/labuladong/fucking-algorithm](https://github.com/labuladong/fucking-algorithm)

[https://openai.com/chatgpt](https://openai.com/chatgpt)


<p align="right">(<a href="#readme-top">返回顶部</a>)</p>


<!-- links -->
[your-project-path]:shaojintian/Best_README_template
[contributors-shield]: https://img.shields.io/github/contributors/worst001/note_algorithm.svg?style=flat-square
[contributors-url]: https://github.com/worst001/note_algorithm/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/worst001/note_algorithm.svg?style=flat-square
[forks-url]: https://github.com/worst001/note_algorithm/network/members
[stars-shield]: https://img.shields.io/github/stars/worst001/note_algorithm.svg?style=flat-square
[stars-url]: https://github.com/worst001/note_algorithm/stargazers
[issues-shield]: https://img.shields.io/github/issues/worst001/note_algorithm.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/worst001/note_algorithm.svg
[license-shield]: https://img.shields.io/github/license/worst001/note_algorithm.svg?style=flat-square
[license-url]: https://github.com/worst001/note_algorithm/blob/main/LICENSE.txt
<!-- [linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555 -->
<!-- [linkedin-url]: https://linkedin.com/in/shaojintian -->

