# level-up
presented by Zuo Er Ting Feng from time.geekbang.org

# 程序员练级攻略

Table of Contents
=================

   * [level-up](#level-up)
   * [程序员练级攻略](#程序员练级攻略)
      * [正式入门](#正式入门)
      * [程序员修养](#程序员修养)
      * [编程语言](#编程语言)
         * [学习 Go 语言](#学习-go-语言)
      * [理论学科](#理论学科)
         * [数据结构和算法](#数据结构和算法)
         * [其它理论基础知识](#其它理论基础知识)
         * [小结](#小结)
      * [系统知识](#系统知识)
         * [C10K 问题](#c10k-问题)
         * [实践项目](#实践项目)
         * [小结](#小结-1)
      * [软件设计](#软件设计)
         * [编程范式](#编程范式)
         * [一些软件设计的相关原则](#一些软件设计的相关原则)
         * [一些软件设计的读物](#一些软件设计的读物)
         * [小结](#小结-2)
      * [Linux系统、内存和网络](#linux系统内存和网络)
         * [Linux 系统相关](#linux-系统相关)
         * [内存相关](#内存相关)
         * [计算机网络](#计算机网络)
            * [网络学习](#网络学习)
            * [网络调优](#网络调优)
            * [网络协议](#网络协议)
         * [小结](#小结-3)
      * [异步I/O模型和Lock-Free编程](#异步io模型和lock-free编程)
         * [异步 I/O 模型](#异步-io-模型)
         * [Lock-Free 编程相关](#lock-free-编程相关)
         * [其它](#其它)
         * [相关论文](#相关论文)
         * [小结](#小结-4)
      * [Java底层知识](#java底层知识)
         * [Java 字节码相关](#java-字节码相关)
         * [JVM 相关](#jvm-相关)
         * [小结](#小结-5)
      * [数据库](#数据库)
         * [关系型数据库](#关系型数据库)
         * [NoSQL 数据库](#nosql-数据库)
         * [小结](#小结-6)
      * [分布式架构入门](#分布式架构入门)
         * [分布式架构入门](#分布式架构入门-1)
         * [分布式理论](#分布式理论)
         * [小结](#小结-7)
      * [分布式架构经典图书和论文](#分布式架构经典图书和论文)
         * [经典图书](#经典图书)
         * [经典论文](#经典论文)
            * [分布式事务](#分布式事务)
            * [Paxos 一致性算法](#paxos-一致性算法)
            * [Raft 一致性算法](#raft-一致性算法)
            * [Gossip 一致性算法](#gossip-一致性算法)
            * [分布式存储和数据库](#分布式存储和数据库)
            * [分布式消息系统](#分布式消息系统)
            * [日志和数据](#日志和数据)
            * [分布式监控和跟踪](#分布式监控和跟踪)
            * [数据分析](#数据分析)
            * [与编程相关的论文](#与编程相关的论文)
            * [其它的分布式论文阅读列表](#其它的分布式论文阅读列表)
         * [小结](#小结-8)
      * [分布式架构工程设计](#分布式架构工程设计)
         * [设计模式](#设计模式)
         * [设计与工程实践](#设计与工程实践)
            * [分布式系统的故障测试](#分布式系统的故障测试)
            * [弹性伸缩](#弹性伸缩)
            * [一致性哈希](#一致性哈希)
            * [数据库分布式](#数据库分布式)
            * [缓存](#缓存)
            * [消息队列](#消息队列)
            * [关于日志方面](#关于日志方面)
            * [关于性能方面](#关于性能方面)
            * [关于搜索方面](#关于搜索方面)
            * [各公司的架构实践](#各公司的架构实践)
         * [小结](#小结-9)
      * [微服务](#微服务)
         * [微服务架构](#微服务架构)
         * [微服务和 SOA](#微服务和-soa)
         * [设计模式和最佳实践](#设计模式和最佳实践)
         * [相关资源](#相关资源)
         * [小结](#小结-10)
      * [容器化和自动化运维](#容器化和自动化运维)
         * [Docker](#docker)
         * [Kubernetes](#kubernetes)
         * [小结](#小结-11)
      * [机器学习和人工智能](#机器学习和人工智能)
         * [基本原理简介](#基本原理简介)
         * [相关课程](#相关课程)
         * [相关图书](#相关图书)
         * [相关文章](#相关文章)
         * [相关算法](#相关算法)
         * [相关资源](#相关资源-1)
         * [小结](#小结-12)
      * [前端基础和底层原理](#前端基础和底层原理)
         * [HTML5](#html5)
         * [CSS](#css)
         * [JavaScript](#javascript)
         * [浏览器原理](#浏览器原理)
         * [网络协议](#网络协议-1)
         * [小结](#小结-13)
      * [前端性能优化和框架](#前端性能优化和框架)
         * [前端性能优化](#前端性能优化)
         * [前端框架](#前端框架)
         * [React.js 框架](#reactjs-框架)
         * [Vue.js 框架](#vuejs-框架)
         * [小结](#小结-14)
      * [UI/UX设计](#uiux设计)
         * [图书和文章推荐](#图书和文章推荐)
         * [原子设计（Atomic Design）](#原子设计atomic-design)
         * [设计语言和设计系统](#设计语言和设计系统)
         * [其它公司](#其它公司)
         * [动画效果设计](#动画效果设计)
         * [相关资源](#相关资源-2)
            * [文章资源](#文章资源)
            * [设计收集](#设计收集)
         * [小结](#小结-15)
      * [技术资源集散地](#技术资源集散地)
         * [个人技术博客](#个人技术博客)
         * [YouTube 技术频道](#youtube-技术频道)
         * [各大公司技术博客](#各大公司技术博客)
         * [论文](#论文)
            * [如何读论文](#如何读论文)
            * [论文集散地](#论文集散地)
         * [小结](#小结-16)
      * [面试前的准备](#面试前的准备)
         * [怎样写简历](#怎样写简历)
         * [技术知识准备](#技术知识准备)
         * [算法题准备](#算法题准备)
         * [工作项目准备](#工作项目准备)
      * [面试中的技巧](#面试中的技巧)
         * [形象和谈吐](#形象和谈吐)
         * [答不出来](#答不出来)
         * [尖锐问题](#尖锐问题)
         * [结尾问题](#结尾问题)
      * [面试风格](#面试风格)
      * [实力才是王中王](#实力才是王中王)
         * [程序员练级攻略](#程序员练级攻略-1)
         * [面试的训练](#面试的训练)
         * [跳槽和升职](#跳槽和升职)
         * [最重要的事](#最重要的事)


## [正式入门](#table-of-contents)

1. 编程技巧
    - 《代码大全》

2. 操作系统
    - 《鸟哥的 Linux 私房菜》

3. 网络协议
    - HTTP

4. 数据库设计
    - [MySQL 文档](https://dev.mysql.com/doc/refman/5.7/en/)
    - 《MySQL 必知必会》

5. 前端
    - jQuery
    - Bootstrap
    - ES6

6. 字符编码

7. 编程工具
    - IDE：Intellij IDEA
    - 版本管理工具：Git
    - 调试前端程序：Chrome
    - 数据库设计工具：MySQL Workbench

8. 文章
    - [The Key To Accelerating Your Coding Skills](http://blog.thefirehoseproject.com/posts/learn-to-code-and-be-self-reliant/)
    - [HTTP 文档](https://developer.mozilla.org/zh-CN/docs/Web/HTTP)
    - [数据库设计的那些事](https://www.imooc.com/learn/117)
    - [阮一峰翻译的 ES6 的教程](http://es6.ruanyifeng.com/#docs/promise)
    - [关于字符编码，你所需要知道的（ASCII,Unicode,Utf-8,GB2312…）](http://www.imkevinyang.com/2010/06/%E5%85%B3%E4%BA%8E%E5%AD%97%E7%AC%A6%E7%BC%96%E7%A0%81%EF%BC%8C%E4%BD%A0%E6%89%80%E9%9C%80%E8%A6%81%E7%9F%A5%E9%81%93%E7%9A%84.html)
    - [The history of Character Encoding](http://www.developerknowhow.com/1091/the-history-of-character-encoding)
    - [Wikipedia - Character encoding](https://en.wikipedia.org/wiki/Character_encoding)
    - [Awesome Unicode](https://github.com/jagracey/Awesome-Unicode)
    - [Awesome Code Points](https://github.com/Codepoints/awesome-codepoints)
    - [Pro Git 第二版](https://git-scm.com/book/zh/v2/)
    - [GitHub and Git 图文教程](https://github.com/JiapengLi/GitTutorial)
    - [Git 图文教程及详解](https://www.jianshu.com/p/1b65ed31da97)
    - [超完整的 Chrome 浏览器客户端调试大全](http://www.igeekbar.com/igeekbar/post/156.htm)

## [程序员修养](#table-of-contents)
1. 文章
    - [What are some of the most basic things every programmer should know?](https://www.quora.com/What-are-some-of-the-most-basic-things-every-programmer-should-know)
        - Bad architecture causes more problems than bad code.
        - You will spend more time thinking than coding.
        - The best programmers are always building things.
        - There’s always a better way.
        - Code reviews by your peers will make all of you better.
        - Fewer features for better code is always the right answer in the end.
        - If it’s not tested, it doesn’t work.
        - Don’t reinvent the wheel, library code is there to help.
        - Code that’s hard to understand is hard to maintain.
        - Code that’s hard to maintain is next to useless.
        - Always know how your business makes money, that determines who gets paid what.
        - If you want to feel important as a software developer, work at a tech company.
    - [97 Things Every Programmer Should Know](https://97-things-every-x-should-know.gitbooks.io/97-things-every-programmer-should-know/content/en/index.html)
    - [How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html)
    - [X-Y Problem](http://xyproblem.info/)
    - [X-Y 问题](https://coolshell.cn/articles/10804.html)
    - [FAQ for StackExchange Site](https://meta.stackexchange.com/questions/7931/faq-for-stack-exchange-sites)

2. 写代码的修养
    - 《代码大全》
    - 《重构：改善既有代码的设计》
    - 《修改代码的艺术》
    - 《代码整洁之道》
    - 《程序员的职业素养》
    - Code Review
        - [Code Review Best Practices](https://medium.com/@palantir/code-review-best-practices-19e02780015f)
        - [How Google Does Code Review](https://dzone.com/articles/how-google-does-code-review)
        - [LinkedIn’s Tips for Highly Effective Code Review](https://thenewstack.io/linkedin-code-review/)

    - Unit Test
        - [JUnit User Guide](https://junit.org/junit5/docs/current/user-guide/)
        - [JUnit User Guide（中文版）](http://sjyuan.cc/junit5/user-guide-cn/)
        - [You Still Don’t Know How to Do Unit Testing](https://stackify.com/unit-testing-basics-best-practices/)
        - [Unit Testing Best Practices: JUnit Reference Guide](https://dzone.com/articles/unit-testing-best-practices)
        - [JUnit Best Practices](http://www.kyleblaney.com/junit-best-practices/)

3. 安全防范
    - [OWASP - Open Web Application Security Project](https://www.owasp.org/index.php/Main_Page)
    - [OWASP Top 10 2017 PDF 中文版](https://www.owasp.org/images/d/dc/OWASP_Top_10_2017_%E4%B8%AD%E6%96%87%E7%89%88v1.3.pdf)
    - [伯克立大学的 Secure Coding Practice Guidelines](https://security.berkeley.edu/secure-coding-practice-guidelines)
    - [卡内基梅隆大学的 SEI CERT Coding Standards](https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards)
    - [Hardening Your HTTP Security Headers](https://www.keycdn.com/blog/http-security-headers/)
    - 防御性编程 [Defensive Programming](https://en.wikipedia.org/wiki/Defensive_programming)
        - [The Art of Defensive Programming](https://medium.com/web-engineering-vox/the-art-of-defensive-programming-6789a9743ed4)
        - [Overly defensive programming](https://medium.com/@cvitullo/overly-defensive-programming-e7a1b3d234c2)
    
4. 软件工程和上线

    - [完美软件：对软件测试的各种幻想](https://book.douban.com/subject/4187479/)
    - [Google 软件测试之道](https://book.douban.com/subject/25742200/)
    - [Server Side checklist](https://github.com/mtdvio/going-to-production/blob/master/serverside-checklist.md)
    - [Single Page App Checklist](https://github.com/mtdvio/going-to-production/blob/master/spa-checklist.md)
    - [Monitoring 101](https://www.datadoghq.com/blog/monitoring-101-collecting-data/)

5. 小结

    - 比较重要的几个方面：英文能力、问问题的能力、写代码的修养、安全防范意识、软件工程和上线规范等。这些能力的训练和培养将为后续的学习和发展夯实基础。

6. 附录：编程规范

- 可以让你的代码很规整，这有利于代码易读性，从而可以更容易地维护。

- 提升开发效率，我们知道，效率来自于结构化，而不是杂乱。
  
- 可以让你的软件避免一些容易掉坑的陷阱，也让 Bug 更少，质量更高。

- 可以让团队成员更高效率地协作。

- **Go 语言**

  - [Effective Go](https://golang.org/doc/effective_go.html) ，Go 的语法不复杂，所以，Go 语言的最佳实践只需要看这篇官方文档就够了。
  
- **PHP 语言**
  
  - [PHP FIG](http://www.php-fig.org/psr/)，PHP 编码规范及标准推荐。
      - [PHP The Right Way](http://www.phptherightway.com)，除了编码规范之外的各种 PHP 的最佳实践，还包括一些设计模式，安全问题，以及服务部署，Docker 虚拟化以及各种资源。
  - [Clean Code PHP](https://github.com/jupeter/clean-code-php)，《代码整洁之道》的 PHP 实践。
  
- **Python 语言**

  - [Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)，Python 官方的编程码规范。
  - [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)，Google 公司的 Python 编码规范。
  - [The Hitchhiker’s Guide to Python](http://docs.python-guide.org/en/latest/)，这不只是 Python 的编程规范，还是 Python 资源的集散地，强烈推荐。
  
- **Shell 语言**
  
  - [Google Shell Style Guide](https://google.github.io/styleguide/shell.xml)，Google 的 Shell 脚本编程规范。
  
- **API 相关**

  - [HAL](http://stateless.co/hal_specification.html)，一个简单的 API 规范教程。
    - [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines)，微软软的 Rest API 规范。

  - [API Design Guide](http://apiguide.readthedocs.io/en/latest/)。
      - [RESTful API Designing guidelines - The best practices](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9)。
  - [JSON API - Recommendations](http://jsonapi.org/recommendations)，JSON 相关的 API 的一些推荐实践。
      - [API Security Checklist](https://github.com/shieldfy/API-Security-Checklist) ，API 的安全问题的检查列表。

- **Markdown 相关**
  
  - [Google Markdown Style Guide](https://github.com/google/styleguide/blob/gh-pages/docguide/style.md)。
  - [Markdown Style Guide](http://www.cirosantilli.com/markdown-style-guide/)。
  
- **JSON**
  
  - [Google JSON Style Guide](https://google.github.io/styleguide/jsoncstyleguide.xml)。
  - [JSON Style Guide](http://www.w3resource.com/slides/json-style-guide.php)。
  
- **Git 相关**

  - [Git Style Guide](https://github.com/agis/git-style-guide)。
  - [Few Rules from Git Documentation](https://github.com/git/git/blob/master/Documentation/CodingGuidelines)。

- **正则表达式相关**
      - [RegexHQ](https://github.com/regexhq)。
      - [Learn regex the easy way](https://github.com/zeeshanu/learn-regex)。

## [编程语言](#table-of-contents)

- [Go 语言、Docker 和新技术](https://coolshell.cn/articles/18190.html)
- [程序员的荒谬之言还是至理名言？](https://coolshell.cn/articles/4235.html)

### [学习 Go 语言](#table-of-contents)

C 语言太原始了，C++ 太复杂了，Go 语言是不二之选。有了 C/C++ 的功底，学习 Go 语言非常简单。

首推 [Go by Example](https://gobyexample.com/) 作为你的入门教程。然后，[Go 101](https://go101.org/article/101.html) 也是一个很不错的在线电子书。如果你想看纸书的话，[The Go Programming Language](https://book.douban.com/subject/26337545/) 一书在豆瓣上有 9.2 分。（当然，我以前也写过两篇入门的供你参考 “[GO 语言简介（上）- 语法](https://coolshell.cn/articles/8460.html)” 和 “[GO 语言简介（下）- 特性](https://coolshell.cn/articles/8489.html)”）。

另外，Go 语言官方的 [Effective Go](https://golang.org/doc/effective_go.html) 是必读的，这篇文章告诉你如何更好地使用 Go 语言，以及 Go 语言中的一些原理。

Go 语言最突出之处是并发编程，Unix 老牌黑客罗勃·派克（Rob Pike）在 Google I/O 上的两个分享，可以让你学习到一些并发编程的模式。

- Go Concurrency Patterns（ [幻灯片](https://talks.golang.org/2012/concurrency.slide)和[演讲视频](https://www.youtube.com/watch?v=f6kdp27TYZs)）。
- Advanced Go Concurrency Patterns（[幻灯片](https://talks.golang.org/2013/advconc.slide)、[演讲视频](https://youtu.be/QDDwwePbDtw)）。

然后，Go 在 GitHub 的 wiki 上有好多不错的学习资源，你可以从中学习到多。比如：

- [Go 精华文章列表](https://github.com/golang/go/wiki/Articles)。
- [Go 相关博客列表](https://github.com/golang/go/wiki/Blogs)。
- [Go Talks](https://github.com/golang/go/wiki/GoTalks)。

此外，还有个内容丰富的 Go 资源列表 [Awesome Go](https://github.com/avelino/awesome-go)，推荐看看。

## [理论学科](#table-of-contents)

进入专业的编程领域，算法、数据结构、网络模型、计算机原理等这样的计算机科学专业需要学习的理论知识是必须要学习的。

### [数据结构和算法](#table-of-contents)

算法是比较难学习的，而且学习 " 算法 " 是需要智商的。数组、链表、哈希表、二叉树、排序算法等一些基础知识，对大多数人来说是没什么问题的。但是一旦进入到路径规划、背包问题、字符串匹配、动态规划、递归遍历等一些比较复杂的问题上，就会让很多人跟不上了，不但跟不上，而且还会非常痛苦。是的，解决算法问题的确是可以区分人类智商的一个比较好的方式，这也是为什么好些公司用算法题当面试题来找到智商比较高的程序员。

然而，在很多时候，我们在工作中却发现根本用不到算法，或是一些基本的算法也没有必要实现，只需要使用一下第三方的库就好了。于是，导致社会上出现很多 " 算法无用论 " 的声音。

对此，我想说，算法真的很重要。我这 20 年的经历告诉我，无论是做业务还是做底层系统，经常需要使用算法处理各种各样的问题。比如，业务上我需要用算法比较两个数组中差异的布隆过滤器，或是在做监控系统时实时计算过去一分钟的 P99 统计时的蓄水池算法，或是数据库的 B+ 树索引，还有 Linux 内核中的 epoll 的红黑树，还有在做服务调度里的 " 背包问题 " 等都会用算法，真的是会本质上帮助到你，也是会让你非常有成就感的一件事。

虽然算法很难，需要智商，但我还是想鼓励你，这其中是有很多的套路是可以学习的，一旦学会这些套路，你会受益无穷的。

这里有几本书着重推荐一下。

- **基础知识**。《[算法](https://book.douban.com/subject/10432347/)》，是算法领域经典的参考书，不但全面介绍了关于算法和数据结构的必备知识，还给出了每位程序员应知应会的 50 个算法，并提供了实际代码。最不错的是，其深入浅出的算法介绍，让一些比较难的算法也变得容易理解，尤其是书中对红黑树的讲解非常精彩。其中，还有大量的图解，详尽的代码和讲解，也许是最好的数据结构入门图书。不好的是不深，缺乏进一步的算法设计内容，甚至连动态规划都未提及。另外，如果你觉得算法书比较枯燥的话，你可以看看这本有趣的《[算法图解](https://book.douban.com/subject/26979890/)》。
- **理论加持**。如果说上面这本书偏于实践和工程，而你看完后，对算法和数据结构的兴趣更浓了，那么你可以再看看另一本也是很经典的偏于理论方面的书——《[算法导论](https://book.douban.com/subject/20432061/)》。虽然其中的一些理论知识在《算法》那本书中也有提过，但《算法导论》这本书更为专业一些，是美国计算机科学本科生的教科书。
- **思维改善**。还有一本叫《[编程珠玑](https://book.douban.com/subject/3227098/)》的书，写这本书的人是世界著名计算机科学家乔恩·本特利（Jon Bentley），被誉为影响算法发展的十位大师之一。你可能不认识这个人，但是你知道他的学生有多厉害吗？我例举几个，一个是 Tcl 语言设计者约翰·奥斯德奥特（John Ousterhout），另一个是 Java 语言设计者詹姆斯·高斯林（James Gosling），还有一个是《算法导论》作者之一查尔斯·雷斯尔森（Charles Leiserson），还有好多好多。这本书也是很经典的算法书，其中都是一些非常实际的问题，并以其独有的洞察力和创造力，来引导读者理解并学会解决这些问题的方法，也是一本可以改善你思维方式的书。

然后，你需要去做一些题来训练一下自己的算法能力，这里就要推荐 [LeetCode](https://leetcode.com/) 这个网站了。它是一个很不错的做算法训练的地方。现在也越做越好了。基本上来说，这里会有两类题。

- **基础算法题**。其中有大量的算法题，解这些题都是有套路的，不是用递归（深度优先 DFS，广度优先 BFS），就是要用动态规划（Dynamic Programming），或是折半查找（Binary Search），或是回溯（Back tracing），或是分治法（Divide and Conquer），还有大量的对树、数组、链表、字符串和 hash 表的操作。通过做这些题能让你对这些最基础的算法的思路有非常扎实的了解和训练。对我而言，Dynamic Programming 是我的短板，尤其是一些比较复杂的问题，在推导递推公式上总是有思维的缺陷（数学是我的硬伤）。做了这些题后，我能感到我在动态编程的思路上受到了很大的启发。
- **编程题**。比如：atoi，strstr，add two nums，括号匹配，字符串乘法，通配符匹配，文件路径简化，Text Justification，反转单词等，这些题的 Edge Case 和 Corner Case 有很多。这些题需要你想清楚了再干，只要你稍有疏忽，就会有几个 case 让你痛不欲生，而且一不小心就会让你的代码写得又臭又长，无法阅读。通过做这些题，可以非常好地训练你对各种情况的考虑，以及你对程序代码组织的掌控（其实就是其中的状态变量）。

我觉得每个程序员都应该花时间和精力做这些题，因为你会从这些题中得到很大的收益。我在 Leetcode 上做的一些题的代码在这——我的 [Github](https://github.com/haoel/leetcode) 上，可以给你一些参考。

如果能够把这些算法能力都掌握了，那么你就有很大的概率可以很容易地通过这世界上最优的公司的面试，比如：Google、Amazon、Facebook 之类的公司。对你来说，如果能够进入到这些公司里工作，那么你未来的想像空间也会大得多得多。

最后，我们要知道这个世界上的数据结构和算法很多很多，下面给出了两个网站。

- **List of Algorithms** ，这个网站罗列了非常多的算法，完全可以当成一个算法字典，或是用来开阔眼界。
- 还有一个数据结构动画图的网站 [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)。

### [其它理论基础知识](#table-of-contents)

下面这些书，基本上是计算机科学系的大学教材。如果你想有科班出生的理论基础，那么这些书是必读的。当然，这些理论基础知识比较枯燥，但我觉得如果你想成为专业的程序员，那么应该要找时间读一下。

- 《[数据结构与算法分析](https://book.douban.com/subject/1139426/)》，这本书曾被评为 20 世纪顶尖的 30 部计算机著作之一，作者 Mark Allen Weiss 在数据结构和算法分析方面卓有建树，他在数据结构和算法分析等方面的著作尤其畅销，并广受好评，已被世界 500 余所大学用作教材。
- 《[数据库系统概念](https://book.douban.com/subject/1929984/)》，它是数据库系统方面的经典教材之一。国际上许多著名大学包括斯坦福大学、耶鲁大学、德克萨斯大学、康奈尔大学、伊利诺伊大学、印度理工学院等都采用本书作为教科书。这本书全面介绍了数据库系统的各种知识，透彻阐释数据库管理的基本概念。不仅讨论了数据库查询语言、模式设计、数据仓库、数据库应用开发、基于对象的数据库和 XML、数据存储和查询、事务管理、数据挖掘与信息检索以及数据库系统体系结构等方面的内容，而且对性能评测标准、性能调整、标准化以及空间与地理数据、事务处理监控等高级应用主题进行了广泛讨论。
- 《[现代操作系统](https://book.douban.com/subject/3852290/)》，这本书是操作系统领域的经典之作，书中集中讨论了操作系统的基本原理，包括进程、线程、存储管理、文件系统、输入 / 输出、死锁等，同时还包含了有关计算机安全、多媒体操作系统、掌上计算机操作系统、微内核、多核处理机上的虚拟机以及操作系统设计等方面的内容。
- 《[计算机网络](https://book.douban.com/subject/1391207/)》，这本书采用了独创的自顶向下方法，即从应用层开始沿协议栈向下讲解计算机网络的基本原理，强调应用层范例和应用编程接口，内容深入浅出，注重教学方法，理论与实践相结合。新版中还增加了无线和移动网络一章，并扩充了对等网络、BGP、MPLS、网络安全、广播选路和因特网编址及转发方面的材料。是一本不可多得的教科书。
- 《[计算机程序的构造和解释](https://book.douban.com/subject/1148282/)》，这本书也很经典，是 MIT 的计算机科学系的教材。这本书中主要证实了很多程序是怎么构造出来的，以及程序的本质是什么。整本书主要是使用 Scheme/Lisp 语言，从数据抽象、过程抽象、迭代、高阶函数等编程和控制系统复杂性的思想，到数据结构和算法，到编译器 / 解释器、编程语言设计。
- 《[编译原理](https://book.douban.com/subject/3296317/)》，这本书又叫 " 龙书 "，其全面、深入地探讨了编译器设计方面的重要主题，包括词法分析、语法分析、语法制导定义和语法制导翻译、运行时刻环境、目标代码生成、代码优化技术、并行性检测以及过程间分析技术，并在相关章节中给出大量的实例。与上一版相比，本书进行了全面的修订，涵盖了编译器开发方面的最新进展。每章中都提供了大量的系统及参考文献。

### 小结

好了，最后我们来总结一些今天分享的内容。在这篇文章中，我建议想进入专业编程领域的人，一定要算法、数据结构、网络模型、计算机原理等理论知识，并推荐了相应的学习素材，给出了我的思考和建议。

我认为，虽然这些理论知识枯燥难学，而且通常学完了在工作中也并不是马上就能用上，但这些知识是必须要学好的。**这些理论知识可以说是计算机科学这门学科最精华的知识了，认真学习，理解其背后的逻辑和思维方式，会令你受益匪浅**。不管是未来学习新知识，还是解决什么疑难问题，都能在这些知识中获得灵感或者启发。

## [系统知识](#table-of-contents)

进入专业的编程领域，学习系统知识是非常关键的一部分。

首先推荐的是翻译版图书《[深入理解计算机系统](https://book.douban.com/subject/5333562/)》，原书名为《Computer Systems A Programmer’s Perspective》。不过，这本书叫做《程序员所需要了解的计算机知识》更为合适。

本书的最大优点是为程序员描述计算机系统的实现细节，帮助其在大脑中构造一个层次型的计算机系统。从最底层的数据在内存中的表示到流水线指令的构成，到虚拟存储器，到编译系统，到动态加载库，到最后的用户态应用。通过掌握程序是如何映射到系统上，以及程序是如何执行的，你能够更好地理解程序的行为为什么是这样的，以及效率低下是如何造成的。

**再强调一下，这本书是程序员必读的一本书！**

然后就是美国计算机科学家 [理查德·史蒂文斯（Richard Stevens）](https://zh.wikipedia.org/wiki/理查德·史蒂文斯) 的三套巨经典无比的书。（理查德·史蒂文斯于 1999 年 9 月 1 日离世，终年 48 岁。死因不详，有人说是滑雪意外，有人说是攀岩意外，有人说是滑翔机意外。总之，家人没有透露。大师的 [个人主页](http://www.kohala.com/start/) 今天还可以访问。）

- 《[Unix 高级环境编程](https://book.douban.com/subject/1788421/)》。
- 《Unix 网络编程》 [第 1 卷 套接口 API](https://book.douban.com/subject/1500149/) 、[第 2 卷 进程间通信](https://book.douban.com/subject/4118577/) 。
- 《[TCP/IP 详解 卷 I 协议](https://book.douban.com/subject/1088054/)》。

这几书的地位我就不多说了，你可以自己看相关的书评。但是，这三本书可能都不容易读，一方面是比较厚，另一方面是知识的密度太大了，所以，读起来有点枯燥和乏味。但是，这没办法，你得忍住。

这里要重点说一下《TCP/IP 详解》这本书，是一本很奇怪的书。这本书迄今至少被 [近五百篇学术论文引用过](http://portal.acm.org/citation.cfm?id=161724) 。这本写给工程师看的书居然被各种学院派的论文来引用，也是很神奇的一件事了。而且，虽然理查德·史蒂文斯不是 TCP 的发明人，但是这本书中把这个协议深入浅出地讲出来，还画了几百张时序图，也是令人叹为观止了。

如果你觉得上面这几本经典书比较难啃，你可以试试下面这些通俗易懂的（当然，如果读得懂上面那三本的，下面的这些也就不需要读了）。

- 《[Linux C 编程一站式学习](https://book.douban.com/subject/4141733/)》。
- 《[TCP/IP 网络编程](https://book.douban.com/subject/25911735/)》。
- 《[图解 TCP/IP](https://book.douban.com/subject/24737674/)》，这本书其实并不是只讲了 TCP/IP，应该是叫《计算机网络》才对，主要是给想快速入门的人看的。
- 《[The TCP/IP Guide](http://www.tcpipguide.com/free/index.htm)》，这本书在豆瓣上的评分 9.2，这里给的链接是这本书的 HTML 英文免费版的，里面的图画得很精彩。

另外，学习网络协议不单只是看书，你最好用个抓包工具看看这些网络包是什么样的。所以，这里推荐一本书《[Wireshark 数据包分析实战](https://book.douban.com/subject/21691692/)》。在这本书中，作者结合一些简单易懂的实际网络案例，图文并茂地演示使用 Wireshark 进行数据包分析的技术方法，可以让我们更好地了解和学习网络协议。当然，也拥有了一定的黑客的技能。

看完《Unix 高级环境编程》后，你可以趁热打铁看看《[Linux/Unix 系统编程手册](https://book.douban.com/subject/25809330/)》或是罗伯特·拉姆（Robert Love）的 [Linux System Programming 英文电子版](http://igm.univ-mlv.fr/~yahya/progsys/linux.pdf) 。其中文翻译版[Linux 系统编程](https://book.douban.com/subject/25828773/)也值得一读，虽然和《Unix 高级环境编程》很像，不过其主要突出的是 Linux 的一些关键技术和相关的系统调用。

关于 TCP 的东西，你还可以看看下面这一系列的文章。

- [Let’s code a TCP/IP stack, 1: Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
- [Let’s code a TCP/IP stack, 2: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
- [Let’s code a TCP/IP stack, 3: TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
- [Let’s code a TCP/IP stack, 4: TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
- [Let’s code a TCP/IP stack, 5: TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)

**对于系统知识，我认为主要有以下一些学习要点。**

- 用这些系统知识操作一下文件系统，实现一个可以拷贝目录树的小程序。
- 用 fork / wait / waitpid 写一个多进程的程序，用 pthread 写一个多线程带同步或互斥的程序。比如，多进程购票的程序。
- 用 signal / kill / raise / alarm / pause / sigprocmask 实现一个多进程间的信号量通信的程序。
- 学会使用 gcc 和 gdb 来编程和调试程序（参看我的《**用 gdb 调试程序**》[一](https://blog.csdn.net/haoel/article/details/2879)、[二](https://blog.csdn.net/haoel/article/details/2880)、[三](https://blog.csdn.net/haoel/article/details/2881)、[四](https://blog.csdn.net/haoel/article/details/2882)、[五](https://blog.csdn.net/haoel/article/details/2883)、[六](https://blog.csdn.net/haoel/article/details/2884)、[七](https://blog.csdn.net/haoel/article/details/2885)）。
- 学会使用 makefile 来编译程序（参看我的《**跟我一起写 makefile**》[一](https://blog.csdn.net/haoel/article/details/2886)、[二](https://blog.csdn.net/haoel/article/details/2887)、[三](https://blog.csdn.net/haoel/article/details/2888)、[四](https://blog.csdn.net/haoel/article/details/2889)、[五](https://blog.csdn.net/haoel/article/details/2890)、[六](https://blog.csdn.net/haoel/article/details/2891)、[七](https://blog.csdn.net/haoel/article/details/2892)、[八](https://blog.csdn.net/haoel/article/details/2893)、[九](https://blog.csdn.net/haoel/article/details/2894)、[十](https://blog.csdn.net/haoel/article/details/2895)、[十一](https://blog.csdn.net/haoel/article/details/2896)、[十二](https://blog.csdn.net/haoel/article/details/2897)、[十三](https://blog.csdn.net/haoel/article/details/2898)、[十四](https://blog.csdn.net/haoel/article/details/2899)）。
- Socket 的进程间通信。用 C 语言写一个 1 对 1 的聊天小程序，或是一个简单的 HTTP 服务器。

### [C10K 问题](#table-of-contents)

然后，当你读完《Unix 网络编程》后，千万要去读一下 “[C10K Problem](http://www.kegel.com/c10k.html) （[中文翻译版](https://www.oschina.net/translate/c10k)）”。提出这个问题的人叫丹·凯格尔（Dan Kegel），目前工作在美国 Google 公司。

他从 1978 年起开始接触计算机编程，是 Winetricks 的作者，也是 Wine 1.0 的管理员，同时也是 Crosstool（ 一个让 gcc/glibc 编译器更易用的工具套件）的作者。还是 Java JSR 51 规范的提交者并参与编写了 Java 平台的 NIO 和文件锁，同时参与了 RFC 5128 标准中有关 NAT 穿越（P2P 打洞）技术的描述和定义。

C10K 问题本质上是操作系统处理大并发请求的问题。对于 Web 时代的操作系统而言，对于客户端过来的大量的并发请求，需要创建相应的服务进程或线程。这些进程或线程多了，导致数据拷贝频繁（缓存 I/O、内核将数据拷贝到用户进程空间、阻塞）， 进程 / 线程上下文切换消耗大，从而导致资源被耗尽而崩溃。这就是 C10K 问题的本质。

了解这个问题，并了解操作系统是如何通过多路复用的技术来解决这个问题的，有助于你了解各种 I/O 和异步模型，这对于你未来的编程和架构能力是相当重要的。

另外，现在，整个世界都在解决 C10M 问题，推荐看看 [The Secret To 10 Million Concurrent Connections -The Kernel Is The Problem, Not The Solution](http://highscalability.com/blog/2013/5/13/the-secret-to-10-million-concurrent-connections-the-kernel-i.html) 一文。

### [实践项目](#table-of-contents)

我们已经学习完了编程语言、理论学科和系统知识三部分内容，下面就来做几个实践项目，小试牛刀一下。实现语言可以用 C、C++ 或 Java。

实现一个 telnet 版本的聊天服务器，主要有以下需求。

- 每个客户端可以用使用`telnet ip:port`的方式连接到服务器上。
- 新连接需要用用户名和密码登录，如果没有，则需要注册一个。
- 然后可以选择一个聊天室加入聊天。
- 管理员有权创建或删除聊天室，普通人员只有加入、退出、查询聊天室的权力。
- 聊天室需要有人数限制，每个人发出来的话，其它所有的人都要能看得到。

实现一个简单的 HTTP 服务器，主要有以下需求。

- 解释浏览器传来的 HTTP 协议，只需要处理 URL path。
- 然后把所代理的目录列出来。
- 在浏览器上可以浏览目录里的文件和下级目录。
- 如果点击文件，则把文件打开传给浏览器（浏览器能够自动显示图片、PDF，或 HTML、CSS、JavaScript 以及文本文件）。
- 如果点击子目录，则进入到子目录中，并把子目录中的文件列出来。

实现一个生产者 / 消费者消息队列服务，主要有以下需求。

- 消息队列采用一个 Ring-buffer 的数据结构。
- 可以有多个 topic 供生产者写入消息及消费者取出消息。
- 需要支持多个生产者并发写。
- 需要支持多个消费者消费消息（只要有一个消费者成功处理消息就可以删除消息）。
- 消息队列要做到不丢数据（要把消息持久化下来）。
- 能做到性能很高。

### [小结](#table-of-contents)

到今天，我们已经学习完了专业编程方面最为重要的三部分内容：编程语言、理论学科和系统知识，我们针对这些内容做个小结。如果想看完我推荐的那些书和知识，并能理解和掌握，我估计怎么也得需要 4-5 年的时间。嗯，是的，就是一个计算机科学系科班出身的程序员需要学习的一些东西。这其中，最重要的是下面这几点。

**编程语言**。以工业级的 C、C++、Java 这三门语言为主，这三门语言才是真正算得上工业级的编程语言，因为有工业级的标准化组织在控制着这几门语言，而且也有工业级的企业应用。尤其是 Java，还衍生出了大量的企业级架构上的开源生态。你至少需要掌握 C 语言和 Java 语言，这对你以后面对各式各样的编程语言是非常重要的。

此外，还推荐学习 Go 语言，它已成为云计算领域事实上的标准语言，尤其是在 Docker、Kubernetes 等项目中。而且，Go 语言在国内外一些知名公司中有了一定的应用和实践，并且其生态圈也越来越好。

**算法和数据结构**。这个太重要了，尤其是最基础的算法和数据结构，这是任何一个称职的程序员都需要学习和掌握的。你必需要掌握。

**计算机的相关系统**。你至少要掌握三个系统的基础知识，一个是操作系统，一个是网络系统，还有一个是数据库系统。它们分别代表着计算机基础构架的三大件——计算、存储、网络。

如果你能够走到这里，把前面的那些知识都了解了（不用精通，因为精通是需要时间和实践来慢慢锤炼出来的，所以，你也不用着急），那么你已经是一个非常非常合格的程序员了，而且你的潜力和可能性是非常非常高的。

如果经历过这些比较枯燥的理论知识，而且你还能有热情和成就感，那么我要恭喜你了。因为你已经超过了绝大多数人，而且还是排在上游的比较抢手的程序员了。我相信你至少可以找到年薪 50 万以上的工作了。

但是，你还需要很多的经验或是一些实践，以及一些大系统大项目的实际动手的经验。没关系，我们后面会有教你怎么实操的方法和攻略。

但是，往后面走，你需要开始需要术业有专攻了。下面给一些建议的方向。

- **底层方向**：操作系统、文件系统、数据库、网络……
- **架构方向**：分布式系统架构、微服务、DevOps、Cloud Native……
- **数据方向**：大数据、机器学习、人工智能……
- **前端方向**：你对用户体验或是交互更感兴趣，那么你走前端的路吧。
- **其它方向**：比如，安全开发、运维开发、嵌入式开发……

这些方向你要仔细选择，因为一旦选好，就要勇往直前地走下去，当然，你要回头转别的方向也没什么问题，因为你有前面的这些基础知识在身，所以，不用害怕。只是不同的方向上会有不同的经验积累，经验积累是看书看不来的，这个是转方向的成本。

## [软件设计](#table-of-contents)

### [编程范式](#table-of-contents)

学习编程范式可以让你明白编程的本质和各种语言的编程方式。虽然很多程序员都忽略了这个事，但是其实是非常非常重要的事。因此，我推荐以下一些资料，帮助你系统化地学习和理解。

- 一个是我在极客时间写的《编程范式游记》系列文章，目录如下。

  - [编程范式游记（1）- 起源](https://time.geekbang.org/column/article/301)
  - [编程范式游记（2）- 泛型编程](https://time.geekbang.org/column/article/303)
  - [编程范式游记（3）- 类型系统和泛型的本质](https://time.geekbang.org/column/article/2017)
  - [编程范式游记（4）- 函数式编程](https://time.geekbang.org/column/article/2711)
  - [编程范式游记（5）- 修饰器模式](https://time.geekbang.org/column/article/2723)
  - [编程范式游记（6）- 面向对象编程](https://time.geekbang.org/column/article/2729)
  - [编程范式游记（7）- 基于原型的编程范式](https://time.geekbang.org/column/article/2741)
  - [编程范式游记（8）- Go 语言的委托模式](https://time.geekbang.org/column/article/2748)
  - [编程范式游记（9）- 编程的本质](https://time.geekbang.org/column/article/2751)
  - [编程范式游记（10）- 逻辑编程范式](https://time.geekbang.org/column/article/2752)
  - [编程范式游记（11）- 程序世界里的编程范式](https://time.geekbang.org/column/article/2754)

- [Wikipedia: Programming paradigm](https://en.wikipedia.org/wiki/Programming_paradigm) ，维基百科上有一个编程范式的页面，顺着这个页面看下去，你可以看到很多很多有用的和编程相关的知识。这些东西对你的编程技能的提高会非常非常有帮助。

- [Six programming paradigms that will change how you think about coding](https://www.ybrikman.com/writing/2014/04/09/six-programming-paradigms-that-will/)，中文翻译版为 [六个编程范型将改变你对编程的看法](https://my.oschina.net/editorial-story/blog/890965)。这篇文章讲了默认支持并发（Concurrent by default）、依赖类型（Dependent types）、连接性语言（Concatenative languages）、声明式编程（Declarative programming）、符号式编程（Symbolic programming）、基于知识的编程（Knowledge-based programming）等六种不太常见的编程范式，并结合了一些你没怎么听说过的语言来分别进行讲述。

  比如在讲 Concatenative languages 时，以 Forth、cat 和 joy 三种语言为例讲述这一编程范式背后的思想——语言中的所有内容都是一个函数，用于将数据推送到堆栈或从堆栈弹出数据；程序几乎完全通过功能组合来构建（concatenation is composition）。作者认为，这些编程范式背后的思想十分有魅力，能够改变对编程的思考。我看完此文，对此也深信不疑。虽然这些语言和编程范式不常用到，但确实能在思想层面给予人很大的启发。这也是我推荐此文的目的。

- [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf) ，这篇文章的作者彼得·范·罗伊（Peter Van Roy）是比利时鲁汶大学的计算机科学教师。他在这篇文章里分析了编程语言在历史上的演进，有哪些典型的、值得研究的案例，里面体现了哪些值得学习的范式。

  比如，在分布式编程领域，他提到了 Erlang、E、Distributed Oz 和 Didactic Oz 这四种编程语言。虽然它们都是分布式编程语言，但各有特色，各自解决了不同的问题。通过这篇文章能学到不少在设计编程语言时要考虑的问题，让你重新审视自己所使用的编程语言应该怎样用才能用好，有什么局限性，这些局限性能否被克服等。

- [斯坦福大学公开课：编程范式](http://open.163.com/special/opencourse/paradigms.html)，这是一门比较基础且很详细的课程，适合学习编程语言的初学者。它通过讲述 C、C++、并发编程、Scheme、Python 这 5 门语言，介绍了它们各自不同的编程范式。以 C 语言为例，它解释了 C 语言的基本要素，如指针、内存分配、堆、C 风格的字符串等，并解释了为什么 C 语言会在泛型编程、多态等方面有局限性。通过学习这门课程，你会对一些常用的编程范式有所了解。

### [一些软件设计的相关原则](#table-of-contents)

- **Don’t Repeat Yourself (DRY)** ，DRY 是一个最简单的法则，也是最容易被理解的。但它也可能是最难被应用的（因为要做到这样，我们需要在泛型设计上做相当的努力，这并不是一件容易的事）。它意味着，当在两个或多个地方发现一些相似的代码的时候，我们需要把它们的共性抽象出来形成一个唯一的新方法，并且改变现有地方的代码让它们以一些合适的参数调用这个新的方法。

- **Keep It Simple, Stupid(KISS)** ，KISS 原则在设计上可能最被推崇，在家装设计、界面设计和操作设计上，复杂的东西越来越被众人所鄙视了，而简单的东西越来越被人所认可。宜家（IKEA）简约、高效的家居设计和生产思路；微软（Microsoft）“所见即所得”的理念；谷歌（Google）简约、直接的商业风格，无一例外地遵循了“KISS”原则。也正是“KISS”原则，成就了这些看似神奇的商业经典。而苹果公司的 iPhone 和 iPad 将这个原则实践到了极至。

- **Program to an interface, not an implementation**，这是设计模式中最根本的哲学，注重接口，而不是实现，依赖接口，而不是实现。接口是抽象是稳定的，实现则是多种多样的。在面向对象的 S.O.L.I.D 原则中会提到我们的依赖倒置原则，就是这个原则的另一种样子。还有一条原则叫 Composition over inheritance（喜欢组合而不是继承），这两条是那 23 个经典设计模式中的设计原则。

- **You Ain’t Gonna Need It (YAGNI)** ，这个原则简而言之为——只考虑和设计必须的功能，避免过度设计。只实现目前需要的功能，在以后你需要更多功能时，可以再进行添加。如无必要，勿增复杂性。软件开发是一场 trade-off 的博弈。

- **Law of Demeter**，迪米特法则 (Law of Demeter)，又称“最少知识原则”（Principle of Least Knowledge），其来源于 1987 年荷兰大学的一个叫做 Demeter 的项目。克雷格·拉尔曼（Craig Larman）把 Law of Demeter 又称作“不要和陌生人说话”。在《程序员修炼之道》中讲 LoD 的那一章将其叫作“解耦合与迪米特法则”。

  关于迪米特法则有一些很形象的比喻：1) 如果你想让你的狗跑的话，你会对狗狗说还是对四条狗腿说？2) 如果你去店里买东西，你会把钱交给店员，还是会把钱包交给店员让他自己拿？和狗的四肢说话？让店员自己从钱包里拿钱？这听起来有点儿荒唐，不过在我们的代码里这几乎是见怪不怪的事情了。对于 LoD，正式的表述如下：

  对于对象 ‘O’ 中一个方法’M’，M 应该只能够访问以下对象中的方法：

  1. 对象 O；
  2. 与 O 直接相关的 Component Object；
  3. 由方法 M 创建或者实例化的对象；
  4. 作为方法 M 的参数的对象。

- **面向对象的 S.O.L.I.D 原则">http://en.wikipedia.org/wiki/Solid_(object-oriented_design)**：

  - **SRP（Single Responsibility Principle）- 职责单一原则**。关于单一职责原则，其核心的思想是：一个类，只做一件事，并把这件事做好，其只有一个引起它变化的原因。单一职责原则可以看作是低耦合、高内聚在面向对象原则上的引申，将职责定义为引起变化的原因，以提高内聚性来减少引起变化的原因。

  职责过多，可能引起它变化的原因就越多，这将导致职责依赖，相互之间就产生影响，从而极大地损伤其内聚性和耦合度。单一职责，通常意味着单一的功能，因此不要为一个模块实现过多的功能点，以保证实体只有一个引起它变化的原因。

  - **OCP（Open/Closed Principle）- 开闭原则**。关于开发封闭原则，其核心的思想是：模块是可扩展的，而不可修改的。也就是说，对扩展是开放的，而对修改是封闭的。对扩展开放，意味着有新的需求或变化时，可以对现有代码进行扩展，以适应新的情况。对修改封闭，意味着类一旦设计完成，就可以独立完成其工作，而不要对类进行任何修改。
  - **LSP（Liskov substitution principle）- 里氏代换原则**。软件工程大师罗伯特·马丁（Robert C. Martin）把里氏代换原则最终简化为一句话：“Subtypes must be substitutable for their base types”。也就是，子类必须能够替换成它们的基类。即子类应该可以替换任何基类能够出现的地方，并且经过替换以后，代码还能正常工作。另外，不应该在代码中出现 if/else 之类对子类类型进行判断的条件。里氏替换原则 LSP 是使代码符合开闭原则的一个重要保证。正是由于子类型的可替换性才使得父类型的模块在无需修改的情况下就可以扩展。
  - **ISP（Interface Segregation Principle ）- 接口隔离原则**。接口隔离原则的意思是把功能实现在接口中，而不是类中，使用多个专门的接口比使用单一的总接口要好。举个例子，我们对电脑有不同的使用方式，比如：写作、通讯、看电影、打游戏、上网、编程、计算和数据存储等。

  如果我们把这些功能都声明在电脑的抽象类里面，那么，我们的上网本、PC 机、服务器和笔记本的实现类都要实现所有的这些接口，这就显得太复杂了。所以，我们可以把这些功能接口隔离开来，如工作学习接口、编程开发接口、上网娱乐接口、计算和数据服务接口，这样，我们的不同功能的电脑就可以有所选择地继承这些接口。

  - **DIP（Dependency Inversion Principle）- 依赖倒置原则**。高层模块不应该依赖于低层模块的实现，而是依赖于高层抽象。举个例子，墙面的开关不应该依赖于电灯的开关实现，而是应该依赖于一个抽象的开关的标准接口。这样，当我们扩展程序的时候，开关同样可以控制其它不同的灯，甚至不同的电器。也就是说，电灯和其它电器继承并实现我们的标准开关接口，而开关厂商就可以不需要关于其要控制什么样的设备，只需要关心那个标准的开关标准。这就是依赖倒置原则。

- [CCP（Common Closure Principle） - 共同封闭原则](http://c2.com/cgi/wiki?CommonClosurePrinciple)，一个包中所有的类应该对同一种类型的变化关闭。一个变化影响一个包，便影响了包中所有的类。一个更简短的说法是：一起修改的类，应该组合在一起（同一个包里）。如果必须修改应用程序里的代码，那么我们希望所有的修改都发生在一个包里（修改关闭），而不是遍布在很多包里。

  CCP 原则就是把因为某个同样的原因而需要修改的所有类组合进一个包里。如果两个类从物理上或者从概念上联系得非常紧密，它们通常一起发生改变，那么它们应该属于同一个包。CCP 延伸了开闭原则（OCP）的“关闭”概念，当因为某个原因需要修改时，把需要修改的范围限制在一个最小范围内的包里。

- [CRP（Common Reuse Principle）- 共同重用原则](http://c2.com/cgi/wiki?CommonReusePrinciple) ，包的所有类被一起重用。如果你重用了其中的一个类，就重用全部。换个说法是，没有被一起重用的类不应该组合在一起。CRP 原则帮助我们决定哪些类应该被放到同一个包里。依赖一个包就是依赖这个包所包含的一切。

  当一个包发生了改变，并发布新的版本，使用这个包的所有用户都必须在新的包环境下验证他们的工作，即使被他们使用的部分没有发生任何改变。因为如果包中包含未被使用的类，即使用户不关心该类是否改变，但用户还是不得不升级该包并对原来的功能加以重新测试。CCP 则让系统的维护者受益。CCP 让包尽可能大（CCP 原则加入功能相关的类），CRP 则让包尽可能小（CRP 原则剔除不使用的类）。它们的出发点不一样，但不相互冲突。

- [好莱坞原则 - Hollywood Principle](http://en.wikipedia.org/wiki/Hollywood_Principle) ，好莱坞原则就是一句话——“don’t call us, we’ll call you.”。意思是，好莱坞的经纪人不希望你去联系他们，而是他们会在需要的时候来联系你。也就是说，所有的组件都是被动的，所有的组件初始化和调用都由容器负责。

  简单来讲，就是由容器控制程序之间的关系，而非传统实现中，由程序代码直接操控。这也就是所谓“控制反转”的概念所在：1) 不创建对象，而是描述创建对象的方式。2）在代码中，对象与服务没有直接联系，而是容器负责将这些联系在一起。控制权由应用代码中转到了外部容器，控制权的转移，是所谓反转。好莱坞原则就是[IoC（Inversion of Control）](http://en.wikipedia.org/wiki/Inversion_of_Control) 或[DI（Dependency Injection）](https://martinfowler.com/articles/injection.html)的基础原则。

- [高内聚， 低耦合 & - High Cohesion & Low/Loose coupling](http://en.wikipedia.org/wiki/Coupling_(computer_science))，这个原则是 UNIX 操作系统设计的经典原则，把模块间的耦合降到最低，而努力让一个模块做到精益求精。内聚，指一个模块内各个元素彼此结合的紧密程度；耦合指一个软件结构内不同模块之间互连程度的度量。内聚意味着重用和独立，耦合意味着多米诺效应牵一发动全身。对于面向对象来说，你也可以看看马萨诸塞州戈登学院的面向对象课中的这一节讲义[High Cohesion and Low Coupling](http://www.math-cs.gordon.edu/courses/cs211/lectures-2009/Cohesion,Coupling,MVC.pdf)。

- [CoC（Convention over Configuration）- 惯例优于配置原则](http://en.wikipedia.org/wiki/Convention_over_Configuration) ，简单点说，就是将一些公认的配置方式和信息作为内部缺省的规则来使用。例如，Hibernate 的映射文件，如果约定字段名和类属性一致的话，基本上就可以不要这个配置文件了。你的应用只需要指定不 convention 的信息即可，从而减少了大量 convention 而又不得不花时间和精力啰里啰嗦的东东。

  配置文件在很多时候相当影响开发效率。Rails 中很少有配置文件（但不是没有，数据库连接就是一个配置文件）。Rails 的 fans 号称其开发效率是 Java 开发的 10 倍，估计就是这个原因。Maven 也使用了 CoC 原则，当你执行 `mvn -compile` 命令的时候，不需要指定源文件放在什么地方，而编译以后的 class 文件放置在什么地方也没有指定，这就是 CoC 原则。

- [SoC (Separation of Concerns) - 关注点分离](http://sulong.me/archives/99) ，SoC 是计算机科学中最重要的努力目标之一。这个原则，就是在软件开发中，通过各种手段，将问题的各个关注点分开。如果一个问题能分解为独立且较小的问题，就是相对较易解决的。问题太过于复杂，要解决问题需要关注的点太多，而程序员的能力是有限的，不能同时关注于问题的各个方面。

  正如程序员的记忆力相对于计算机知识来说那么有限一样，程序员解决问题的能力相对于要解决的问题的复杂性也是一样的非常有限。在我们分析问题的时候，如果我们把所有的东西混在一起讨论，那么就只会有一个结果——乱。实现关注点分离的方法主要有两种，一种是标准化，另一种是抽象与包装。标准化就是制定一套标准，让使用者都遵守它，将人们的行为统一起来，这样使用标准的人就不用担心别人会有很多种不同的实现，使自己的程序不能和别人的配合。

  就像是开发镙丝钉的人只专注于开发镙丝钉就行了，而不用关注镙帽是怎么生产的，反正镙帽和镙丝钉按照标准来就一定能合得上。不断地把程序的某些部分抽象并包装起来，也是实现关注点分离的好方法。一旦一个函数被抽象出来并实现了，那么使用函数的人就不用关心这个函数是如何实现的。同样的，一旦一个类被抽象并实现了，类的使用者也不用再关注于这个类的内部是如何实现的。诸如组件、分层、面向服务等这些概念都是在不同的层次上做抽象和包装，以使得使用者不用关心它的内部实现细节。

- [DbC（Design by Contract）- 契约式设计](http://en.wikipedia.org/wiki/Design_by_contract) ，DbC 的核心思想是对软件系统中的元素之间相互合作以及“责任”与“义务”的比喻。这种比喻从商业活动中“客户”与“供应商”达成“契约”而得来。如果在程序设计中一个模块提供了某种功能，那么它要：

  - 期望所有调用它的客户模块都保证一定的进入条件：这就是模块的先验条件（客户的义务和供应商的权利，这样它就不用去处理不满足先验条件的情况）。
  - 保证退出时给出特定的属性：这就是模块的后验条件（供应商的义务，显然也是客户的权利）。
  - 在进入时假定，并在退出时保持一些特定的属性：不变式。

- [ADP（Acyclic Dependencies Principle）- 无环依赖原则](http://c2.com/cgi/wiki?AcyclicDependenciesPrinciple) ，包（或服务）之间的依赖结构必须是一个直接的无环图形，也就是说，在依赖结构中不允许出现环（循环依赖）。如果包的依赖形成了环状结构，怎么样打破这种循环依赖呢？

  有两种方法可以打破这种循环依赖关系：第一种方法是创建新的包，如果 A、B、C 形成环路依赖，那么把这些共同类抽出来放在一个新的包 D 里。这样就把 C 依赖 A 变成了 C 依赖 D 以及 A 依赖 D，从而打破了循环依赖关系。第二种方法是使用 DIP（依赖倒置原则）和 ISP（接口分隔原则）设计原则。无环依赖原则（ADP）为我们解决包之间的关系耦合问题。在设计模块时，不能有循环依赖。

### [一些软件设计的读物](#table-of-contents)

- 《[领域驱动设计](https://book.douban.com/subject/26819666/)》 ，本书是领域驱动设计方面的经典之作。全书围绕着设计和开发实践，结合若干真实的项目案例，向读者阐述如何在真实的软件开发中应用领域驱动设计。书中给出了领域驱动设计的系统化方法，并将人们普遍接受的一些实践综合到一起，融入了作者的见解和经验，展现了一些可扩展的设计新实践、已验证过的技术以及便于应对复杂领域的软件项目开发的基本原则。
- 《[UNIX 编程艺术](https://book.douban.com/subject/1467587/)》 ，这本书主要介绍了 Unix 系统领域中的设计和开发哲学、思想文化体系、原则与经验，由公认的 Unix 编程大师、开源运动领袖人物之一埃里克·雷蒙德（Eric S. Raymond）倾力多年写作而成。包括 Unix 设计者在内的多位领域专家也为本书贡献了宝贵的内容。本书内容涉及社群文化、软件开发设计与实现，覆盖面广、内容深邃，完全展现了作者极其深厚的经验积累和领域智慧。
- 《[Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)》，如果你读过 《[Clean Code](https://book.douban.com/subject/5442024/)》 和 《[The Clean Coder](https://book.douban.com/subject/11614538/)》这两本书。你就能猜得到这种 Clean 系列一定也是出自“Bob 大叔”之手。没错，就是 Bob 大叔的心血之作。除了这个网站，《[Clean Architecture](https://book.douban.com/subject/26915970/)》也是一本书，这是一本很不错的架构类图书。对软件架构的元素、方法等讲得很清楚。示例都比较简单，并带一些软件变化历史的讲述，很开阔视野。
- [The Twelve-Factor App](https://12factor.net/) ，如今，软件通常会作为一种服务来交付，它们被称为网络应用程序，或软件即服务（SaaS）。12-Factor 为构建 SaaS 应用提供了方法论，这也是架构师必读的文章。（[中译版](https://12factor.net/zh_cn/)） 这篇文章在业内的影响力很大，必读！
- [Avoid Over Engineering](https://medium.com/@rdsubhas/10-modern-software-engineering-mistakes-bc67fbef4fc8) ，有时候，我们会过渡设计我们的系统，过度设计会把我们带到另外一个复杂度上，所以，我们需要一些工程上的平衡。这篇文章是一篇非常不错地告诉你什么是过度设计的文章。
- [Instagram Engineering’s 3 rules to a scalable cloud application architecture](https://medium.com/@DataStax/instagram-engineerings-3-rules-to-a-scalable-cloud-application-architecture-c44afed31406) ，Instagram 工程的三个黄金法则：1）使用稳定可靠的技术（迎接新的技术）；2）不要重新发明轮子；3）Keep it very simple。我觉得这三条很不错。其实，Amazon 也有两条工程法则，一个是自动化，一个是简化。
- [How To Design A Good API and Why it Matters - Joshua Bloch](https://www.infoq.com/presentations/effective-api-design) ，Google 的一个分享，关于如何设计好一个 API。
- 关于 Restful API 的设计，你可以学习并借鉴一下下面这些文章。
  - [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
  - [Ideal REST API design](https://betimdrenica.wordpress.com/2015/03/09/ideal-rest-api-design/)
  - [HTTP API Design Guide](https://github.com/interagent/http-api-design)
  - [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md)
  - [IBM Watson REST API Guidelines](https://github.com/watson-developer-cloud/api-guidelines)
  - [Zalando RESTful API and Event Scheme Guidelines](https://opensource.zalando.com/restful-api-guidelines/)
- [The Problem With Logging](https://blog.codinghorror.com/the-problem-with-logging/) ，一篇关于程序打日志的短文，可以让你知道一些可能以往不知道的打日志需要注意的问题。
- [Concurrent Programming for Scalable Web Architectures](http://berb.github.io/diploma-thesis/community/index.html) ，这是一本在线的免费书，教你如何架构一个可扩展的高性能的网站。其中谈到了一些不错的设计方法和知识。

### [小结](#table-of-contents)

好了，总结一下今天分享的内容。我认为，“品位”不同，是各层次程序员之间最大的区别，这也决定了他们所做出来的软件的质量和价值。因此，我特意撰写了软件设计这一篇章，帮助那些想成长为软件工程师、设计师或架构师的程序员，提高软件设计的品位，进而实现自己的目标。

虽然很多程序员都忽略了对编程范式的学习，但我觉得学习编程范式其实是非常非常重要的事，能够明白编程的本质和各种语言的编程方式。为此，我推荐了好几份学习资料，帮助你系统化地学习和理解。随后我介绍了 DRY- 避免重复原则、KISS- 简单原则、迪米特法则（又称“最少知识原则”）、 面向对象的 S.O.L.I.D 原则等多个经典的软件设计原则。

最后，我精选并推荐了软件设计方面的学习资料，如《领域驱动设计》、《UNIX 编程艺术》和《Clean Architecture》等必读好书，以及如何构建 SaaS，如何避免过度设计，如何设计 API，如何用程序打日志等方面的资料。

## [Linux 系统、内存和网络](#table-of-contents)

这一篇章，是本文最长的一篇，其中包括了如下的内容。

- **系统底层相关**。 主要是以 Linux 系统为主，其中有大量的文章可以让你学习到 Linux 内核，以及内存、网络、异步 I/O 模型、Lock-free 的无锁编程，还有其它和系统底层相关的东西。注意，系统底层要是深下去是可以完全不见底的。而且内存方面的知识也是比较多的，所以，这里还是主要给出一些非常有价值的基础性的知识和技术。学好这些东西，你会对系统有很深的理解，而且可以把这些知识反哺到架构设计上来。
- **数据库相关**。数据库方面主要是 MySQL 和各种开源 NoSQL 的一些相关的有价值的文章和导读，主要是让你对这些数据库的内在有一定的了解，但又不会太深。真正的深入是需要扎入到源代码中的。需要说明的是，这块技术不是我的长项，但又是每个架构师需要知道的，所以，我在这里给的学习资源可能会比较浅，这点还希望你来补充和指正。
- **分布式架构**。这一部分是最长最多的。其中有架构入门、分布式理论中各种非常有价值的经典论文，然后是一些分布式工程设计方面的文章，其中包括设计模式和工程应用，最后还有各大公司的架构供参考。
- **微服务**。有了分布式架构理论和工程的基础，接下来是对微服务的学习。在这部分内容中，我会罗列几个介绍微服务架构非常系统的文章，然后比较一下微服务和 SOA 的差别，最后则是一些工程实践和最佳实践。
- **容器化和自动化运维**。在容器化和自动化运维中，主要是学习 Docker 和 Kubernetes 这两个自动化运维的杀手型技术。而不是 Salt、Puppet、Chef 和 Ansible 这样比较传统的工具。原因很简单，因为自动化部署根本不够，还需要对环境和运行时的管理和运维才够，而只有 Docker 和 Kubernetes 才是未来。所以，这里重点让你学习这两个技术，其中有很多文章需要一些系统底层的知识。
- **机器学习和人工智能**。机器学习和人工智能，也不是我的长项，我也只是一个入门者。这里，我主要给了一些基础性的知识，其中包括基本原理、图书、课程、文章和相关的算法。你顺着我画的这路走，不能说能成为一个人工智能专家，但成为一个机器学习的高级工程师甚至准专家还是可能的。
- **前端开发**。这里的前端主要是 H5 的前端了，这一节会带你学习一下前端开发所需要知道的基础知识，尤其是对前端开发语言 JavaScript 的学习，我花费了相当的篇幅列出了很多很经典的学习资料，必定会让你成为一个 JavaScript 高手。然后你还需要了解浏览器是怎样工作的，还有相关的网络协议和一些性能优化的技巧。最后则是 JavaScript 框架的学习，这里我只给了 React.js 和 Vue.js，并通过 React.js 带出来函数式编程的学习。我虽然不是一个前端程序员，但是，我相信我这个后端程序员给出来的这组前端开发的学习资料和路径会比前端程序员更靠谱一些。
- **信息源**。最后，则是一些信息源，其中包括各大公司的技术 Blog，还有相关的论文集散地。

### Linux 系统相关

### 内存相关

### 计算机网络

#### 网络学习

#### 网络调优

#### 网络协议

### 小结

好了，总结一下今天的内容。这是程序员练级攻略 2018 版第五篇章——高手成长篇的第一篇文章。前面的内容先介绍了一些这一系列内容的总体构成，及每一部分的学习重点。后面是这一篇章第一个主题系统底层知识中的部分内容，即 Linux 系统、内存和计算机网络，并给出了相应的学习资料。

我认为，学习到一定程度，就是要从书本中走出去，到社区里和大家一起学习，而且还需要自己找食吃了。所以，这篇文章中，我罗列了各种文章和资源，并给出了简短的推荐语言，就是在为你梳理信息源，而不是喂你吃饭。我更希望看到你自趋势地成长。

下篇文章中，我们分享的内容为系统底层知识中的异步 I/O 模型、Lock-Free 编程以及其他一些相关的知识点和学习资源。敬请期待。

## 异步I/O模型和Lock-Free编程

### 异步 I/O 模型

### Lock-Free 编程相关

### 其它

### 相关论文

### 小结

## Java底层知识

### Java 字节码相关

### JVM 相关

### 小结

## 数据库

### 关系型数据库

### NoSQL 数据库

### 小结

## [分布式架构入门](#table-of-contents)

学习分布式系统跟学习其它技术非常不一样，分布式系统涵盖的面非常广，具体来说涵盖如下几方面：

- **服务调度**，涉及服务发现、配置管理、弹性伸缩、故障恢复等。
- **资源调度**，涉及对底层资源的调度使用，如计算资源、网络资源和存储资源等。
- **流量调度**，涉及路由、负载均衡、流控、熔断等。
- **数据调度**，涉及数据复本、数据一致性、分布式事务、分库、分表等。
- **容错处理**，涉及隔离、幂等、重试、业务补偿、异步、降级等。
- **自动化运维**，涉及持续集成、持续部署、全栈监控、调用链跟踪等。

所有这些形成了分布式架构的整体复杂度，也造就了分布式系统中的很多很多论文、图书以及很多很多的项目。要学好分布式系统及其架构，我们需要大量的时间和实践才能真正掌握这些技术。

这里有几点需要你注意一下。

- **分布式系统之所以复杂，就是因为其太容易也太经常出错了**。这意味着，**你要把处理错误的代码当成正常功能的代码来处理**。
- **开发一个健壮的分布式系统的成本是单体系统的几百倍甚至几万倍**。这意味着，**我们要自己开发一个，需要能力很强的开发人员**。
- **非常健壮的开源的分布式系统并不多，或者说基本没有**。这意味着，**如果你要用开源的，那么你需要 hold 得住其源码**。
- **管理或是协调多个服务或机器是非常难的**。这意味着，**我们要去读很多很多的分布式系统的论文**。
- **在分布式环境下，出了问题是很难 debug 的**。这意味着，**我们需要非常好的监控和跟踪系统，还需要经常做演练和测试**。
- **在分布式环境下，你需要更科学地分析和统计**。这意味着，**我们要用 P90 这样的统计指标，而不是平均值，我们还需要做容量计划和评估**。
- **在分布式环境下，需要应用服务化**。这意味着，**我们需要一个服务开发框架，比如 SOA 或微服务**。
- **在分布式环境下，故障不可怕，可怕的是影响面过大，时间过长**。这意味着，**我们需要花时间来开发我们的自动化运维平台**。

总之，在分布式环境下，一切都变得非常复杂。要进入这个领域，你需要有足够多的耐性和足够强的心态来接受各式各样的失败。当拥有丰富的实践和经验后，你才会有所建树。这并不是一日之功，你可能要在这个领域花费数年甚至数十年的时间。

### 分布式架构入门

### 分布式理论

### 小结

## 分布式架构经典图书和论文

### 经典图书

### 经典论文

#### 分布式事务

#### Paxos 一致性算法

#### Raft 一致性算法

#### Gossip 一致性算法

#### 分布式存储和数据库

#### 分布式消息系统

#### 日志和数据

#### 分布式监控和跟踪

#### 数据分析

#### 与编程相关的论文

#### 其它的分布式论文阅读列表

### 小结

## 分布式架构工程设计

### 设计模式

### 设计与工程实践

#### 分布式系统的故障测试

#### 弹性伸缩

#### 一致性哈希

#### 数据库分布式

#### 缓存

#### 消息队列

#### 关于日志方面

#### 关于性能方面

#### 关于搜索方面

#### 各公司的架构实践

### 小结

## 微服务

微服务是分布式系统中最近比较流行的架构模型，也是 SOA 架构的一个进化。微服务架构并不是银弹，所以，也不要寄希望于微服务构架能够解决所有的问题。微服务架构主要解决的是如何快速地开发和部署我们的服务，这对于一个能够适应快速开发和成长的公司是非常必要的。同时我也觉得，微服务中有很多很不错的想法和理念，所以学习微服务是每一个技术人员迈向卓越的架构师的必经之路。

### 微服务架构

### 微服务和 SOA

### 设计模式和最佳实践

### 相关资源

### 小结

## [容器化和自动化运维](#table-of-contents)

这篇文章重点学习 Docker 和 Kubernetes，它们已经是分布式架构和自动化运维的必需品了，也是你必需要学习的。对于这两个东西，你千万不要害怕，因为技术方面都不算复杂，只是它们的玩法和传统运维不一样，所以你不用担心，只要你花上一点时间，一定会学好的。

### Docker

### Kubernetes

Kubernetes 是 Google 开源的容器集群管理系统，是 Google 多年大规模容器管理技术 Borg 的开源版本，也是 CNCF 最重要的项目之一，主要功能包括：

- 基于容器的应用部署、维护和滚动升级；
- 负载均衡和服务发现；
- 跨机器和跨地区的集群调度；
- 自动伸缩；
- 无状态服务和有状态服务；
- 广泛的 Volume 支持；
- 插件机制保证扩展性。

Kubernetes 发展非常迅速，已经成为容器编排领域的领导者。

### 小结

## [机器学习和人工智能](#table-of-contents)

我之前写过一篇机器学习的入门文章，因为我也是在入门和在学习的人，所以，那篇文章和这篇机器学习和人工智能方向的文章可能都会有点太肤浅。如果你有更好的学习方式或资料，欢迎补充。

### [基本原理简介](#table-of-contents)

我们先来介绍一下机器学习的基本原理。

机器学习主要有两种方式，一种是监督式学习（Supervised Learning），另一种是非监督式学习（Unsupervised Learning）。下面简单地说一下这两者的不同。

- **监督式学习（Supervised Learning）**。所谓监督式学习，也就是说，我们需要提供一组学习样本，包括相关的特征数据和相应的标签。我们的程序可以通过这组样本来学习相关的规律或是模式，然后通过得到的规律或模式来判断没有被打过标签的数据是什么样的数据。

  举个例子，假设需要识别一些手写的数字，我们要找到尽可能多的手写体的数字的图像样本，然后人工或是通过某种算法来明确地标注上什么是这些手写体的图片，谁是 1，谁是 2，谁是 3…… 这组数据叫样本数据，又叫训练数据（training data）。然后通过机器学习的算法，找到每个数字在不同手写体下的特征，找到规律和模式。通过得到的规律或模式来识别那些没有被打过标签的手写数据，以此完成识别手写体数字的目的。

- **非监督式学习（Unsupervised Learning）**。对于非监督式学习，也就是说，数据是没有被标注过的，所以相关的机器学习算法需要找到这些数据中的共性。因为大量的数据是没被被标识过的，所以这种学习方式可以让大量的未标识的数据能够更有价值。而且，非监督式学习，可以为我们找到人类很难发现的数据里的规律或模型，所以也有人称这种学习为 " 特征点学习 "，其可以让我们自动地为数据进行分类，并找到分类的模型。

  一般来说，非监督式学习会应用在一些交易型的数据中。比如，你有一堆堆的用户购买数据，但是对于人类来说，我们很难找到用户属性和购买商品类型之间的关系。所以，非监督式学习算法可以帮助我们找到它们之间的关系。比如，一个在某个年龄段的女性购买了某种肥皂，有可能说明这个女性在怀孕期，或是某人购买儿童用品，有可能说明这个人的关系链中有孩子，等等。于是，这些信息会被用作一些所谓的精准市场营销活动，从而可以增加商品销量。

我们这么来说吧，监督式学习是在被告诉过了正确的答案后的学习，而非监督式学习是在没有被告诉正确答案时的学习。所以，非监督式学习是在大量的非常乱的数据中找寻一些潜在的关系，这个成本也比较高。非监督式学习经常被用来检测一些不正常的事情发生，比如信用卡的诈骗或是盗刷。也被用在推荐系统，比如买了这个商品的人又买了别的什么商品，或是如果某个人喜欢某篇文章、某个音乐、某个餐馆，那么他可能会喜欢某个车、某个明星或某个地方。

在监督式学习算法下，我们可以用一组 " 狗 " 的照片来确定某个照片中的物体是不是狗。而在非监督式学习算法下，我们可以通过一个照片来找到其中有与其相似的事物的照片。这两种学习方式都有些有用的场景。

关于机器学习，你可以读一读 [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471) ，这篇文章（[中文翻译版](https://zhuanlan.zhihu.com/p/24339995)）恐怕是全世界最简单的入门资料了。

- [Data Science Simplified Part 1: Principles and Process](https://becominghuman.ai/data-science-simplified-principles-and-process-b06304d63308)
- [Data Science Simplified Part 2: Key Concepts of Statistical Learning](https://towardsdatascience.com/data-science-simplified-key-concepts-of-statistical-learning-45648049709e)
- [Data Science Simplified Part 3: Hypothesis Testing](https://towardsdatascience.com/data-science-simplified-hypothesis-testing-56e180ef2f71)
- [Data Science Simplified Part 4: Simple Linear Regression Models](https://towardsdatascience.com/data-science-simplified-simple-linear-regression-models-3a97811a6a3d)
- [Data Science Simplified Part 5: Multivariate Regression Models](https://towardsdatascience.com/data-science-simplified-part-5-multivariate-regression-models-7684b0489015)
- [Data Science Simplified Part 6: Model Selection Methods](https://towardsdatascience.com/data-science-simplified-part-6-model-selection-methods-2511cbdf7cb0)
- [Data Science Simplified Part 7: Log-Log Regression Models](https://towardsdatascience.com/data-science-simplified-part-7-log-log-regression-models-499ecd1495f0)
- [Data Science Simplified Part 8: Qualitative Variables in Regression Models](https://towardsdatascience.com/data-science-simplified-part-8-qualitative-variables-in-regression-models-d1817d56245c)
- [Data Science Simplified Part 9: Interactions and Limitations of Regression Models](https://towardsdatascience.com/data-science-simplified-part-9-interactions-and-limitations-of-regression-models-4702dff03820)
- [Data Science Simplified Part 10: An Introduction to Classification Models](https://towardsdatascience.com/data-science-simplified-part-10-an-introduction-to-classification-models-82490f6c171f)
- [Data Science Simplified Part 11: Logistic Regression](https://towardsdatascience.com/data-science-simplified-part-11-logistic-regression-5ae8d994bf0e)

### [相关课程](#table-of-contents)

接下来，我们需要比较专业地学习一下机器学习了。

在学习机器学习之前，我们需要学习数据分析，所以，我们得先学一些大数据相关的东西，也就是 Data Science 相关的内容。下面是两个不错的和数据科学相关的教程以及一个资源列表。

- [UC Berkeley’s Data 8: The Foundations of Data Science](http://data8.org/) 和电子书 [Computational and Inferential Thinking](https://www.inferentialthinking.com/) 会讲述数据科学方面非常关键的概念，会教会你在数据中找到数据的关联、预测和相关的推断。
- [Learn Data Science](https://github.com/nborwankar/LearnDataScience) ，这是 GitHub 上的一本电子书，主要是一些数据挖掘的算法，比如线性回归、逻辑回归、随机森林、K-Means 聚类的数据分析。然后，[donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks#scikit-learn) 这个代码仓库中用 TensorFlow、scikit-learn、Pandas、NumPy、Spark 等把这些经典的例子实现了个遍。
- [Data Science Resources List](https://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) ，这个网站上有一个非常长的和数据科学相关的资源列表，你可以从中得到很多你想要的东西。

之后，有下面几门不错的在线机器学习的课程供你入门，也是非常不错。

- 吴恩达教授（Andrew Ng）在 [Coursera 上的免费机器学习课程](https://www.coursera.org/learn/machine-learning) 非常棒。我强烈建议从此入手。对于任何拥有计算机或科学学位的人，或是还能记住一点点数学知识的人来说，都应该非常容易入门。这个斯坦福大学的课程请尽量拿满分。可以在 [网易公开课](http://open.163.com/special/opencourse/machinelearning.html) 中找到这一课程。除此之外，吴恩达教授还有一组新的和深度学习相关的课程，现在可以在网易公开课上免费学习——[Deep Learning Specialization](https://mooc.study.163.com/smartSpec/detail/1001319001.htm)。
- [Deep Learning by Google](https://www.udacity.com/course/deep-learning--ud730) ，Google 的一个关于深度学习的在线免费课程，其支持中英文。这门课会教授你如何训练和优化基本神经网络、卷积神经网络和长短期记忆网络。你将通过项目和任务接触完整的机器学习系统 TensorFlow。
- 卡内基梅隆大学汤姆·米切尔（Tom Mitchell）的机器学习 [英文原版视频与课件 PDF](http://www.cs.cmu.edu/~tom/10701_sp11/lectures.shtml) 。
- 2013 年加利福尼亚理工学院亚瑟·阿布 - 穆斯塔法（Yaser Abu-Mostafa）的 Learning from Data [课程视频及课件 PDF](http://work.caltech.edu/lectures.html)，内容更适合进阶。
- 关于神经网络方面，YouTube 上有一个非常火的课程视频，由宾夕法尼亚大学的雨果·拉罗歇尔（Hugo Larochelle）的教学课程 - [Neural networks class - Université de Sherbrooke ](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)。

除此之外，还有很多的在线大学课程你可以学习。比如：

- 斯坦福大学的《[统计学学习](https://lagunita.stanford.edu/courses/HumanitiesandScience/StatLearning/Winter2015/about)》、《[机器学习](http://cs229.stanford.edu/)》、《[卷积神经网络](http://cs231n.stanford.edu/)》、《[深度学习之自然语言处理](http://cs224d.stanford.edu/)》等。
- 麻省理工大学的《[神经网络介绍](http://ocw.mit.edu/courses/brain-and-cognitive-sciences/9-641j-introduction-to-neural-networks-spring-2005/index.htm) 》、《[机器学习](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-867-machine-learning-fall-2006/)》、《[预测](http://ocw.mit.edu/courses/sloan-school-of-management/15-097-prediction-machine-learning-and-statistics-spring-2012/index.htm)》等。

更多的列表，请参看——[Awesome Machine Learning Courses](https://github.com/RatulGhosh/awesome-machine-learning)。

### [相关图书](#table-of-contents)

- 《[Pattern Recognition and Machine Learning](https://book.douban.com/subject/2061116/)》，这本书是机器学习领域的圣经之作。该书也是众多高校机器学习研究生课程的教科书，Google 上有[PDF 版的下载](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop - Pattern Recognition And Machine Learning - Springer  2006.pdf)。这本书很经典，但并不适合入门来看。GitHub 上有这本中的 [Matlab 实现](https://github.com/PRML/PRMLT)。

- 下面这两本电子书也是比较经典的，其中讲了很多机器学习的知识，可以当做手册或字典。

  - 《[Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf)》。
  - 《[The Elements of Statistical Learning - Second Edition](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)》。

- 《[Deep Learning: Adaptive Computation and Machine Learning series](https://book.douban.com/subject/27087503/)》 中文翻译为《深度学习》，又叫 " 花书 "。这本书由全球知名的三位专家伊恩·古德费洛（Ian Goodfellow）、友华·本吉奥（Yoshua Bengio）和亚伦·考维尔（Aaron Courville）撰写，是深度学习领域奠基性的经典教材。

  全书内容包括 3 部分：第 1 部分介绍基本的数学工具和机器学习的概念，它们是深度学习的预备知识；第 2 部分系统深入地讲解现今已成熟的深度学习方法和技术；第 3 部分讨论某些具有前瞻性的方向和想法，它们被公认为是深度学习未来的研究重点。这本书的官网为 “[deeplearningbook.org](http://www.deeplearningbook.org/)”，在 GitHub 上也有中文翻译 - 《[Deep Learning 中文翻译](https://github.com/exacity/deeplearningbook-chinese)》。

- 《[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)》（[中文翻译版](https://tigerneil.gitbooks.io/neural-networks-and-deep-learning-zh/content/)），这是一本非常不错的神经网络的入门书，在[豆瓣上评分 9.5 分](https://book.douban.com/subject/26727997/)，从理论讲到了代码。虽然有很多数学公式，但是有代码相助，就不难理解了。其中讲了很多如激活函数、代价函数、随机梯度下降、反向传播、过度拟合和规范化、权重初始化、超参数优化、卷积网络的局部感受野、混合层、特征映射的东西。

- 《[Introduction to Machine Learning with Python](https://book.douban.com/subject/26279609/)》，算是本不错的入门书，也是本比较易读的英文书。其是以 Scikit-Learn 框架来讲述的。如果你用过 Scikit 这个框架，那么你学这本书还是很不错的。

- 《[Hands-On Machine Learning with Scikit-Learn and TensorFlow](https://book.douban.com/subject/26840215/) 》，这是一门以 TensorFlow 为工具的入门书，其用丰富的例子从实站的角度来让你学习。这本书对于无基础的人也是适合的，对于小白来说虽然略难但是受益匪浅。

### [相关文章](#table-of-contents)

除了上述的那些课程和图书外，下面这些文章也很不错。

- YouTube 上的 Google Developers 的 [Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal) ，这 9 集视频，每集不到 10 分钟，从 Hello World 讲到如何使用 TensorFlow，非常值得一看。
- 还有 [Practical Machine Learning Tutorial with Python Introduction](https://pythonprogramming.net/machine-learning-tutorial-python-introduction/) 上面一系列的用 Python 带着你玩 Machine Learning 的教程。
- Medium 上的 [Machine Learning - 101](https://medium.com/machine-learning-101) ，讲述了好些我们上面提到过的经典算法。
- Medium 上的 [Marchine Learning for Humans](https://medium.com/machine-learning-for-humans)。
- [Dr. Jason Brownlee 的博客](https://machinelearningmastery.com/blog/) ，也非常值得一读，其中好多的 “How-To”，会让你有很多的收获。
- [Rules of Machine Learning: Best Practices for ML Engineering](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf) ，一些机器学习相关的最佳实践。
- [i am trask](http://iamtrask.github.io) ，也是一个很不错的博客。
- 关于 Deep Learning 中的神经网络，YouTube 上有介绍视频 [Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)。
- 麻省理工学院的电子书 [Deep Learning](http://www.deeplearningbook.org)。
- 用 Python 做自然语言处理[Natural Language Processing with Python](http://www.nltk.org/book/)。
- 最后一个是 Machine Learning 和 Deep Learning 的相关教程列表，[Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials)。

下面是一些和神经网络相关的不错的文章。

- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) ，这是一篇必读的文章 ，告诉你为什么要学 RNN，以及展示了最简单的 NLP 形式。
- [Neural Networks, Manifolds, and Topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/) ，这篇文章可以帮助你理解神经网络的一些概念。
- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) ，解释了什么是 LSTM 的内在工作原理。
- [Attention and Augmented Recurrent Neural Networks](http://distill.pub/2016/augmented-rnns/) ，用了好多图来说明了 RNN 的 attention 机制。
- [Recommending music on Spotify with deep learning](http://benanne.github.io/2014/08/05/spotify-cnns.html) ，一个在 Spotify 的实习生分享的音乐聚类的文章。

### [相关算法](#table-of-contents)

下面是 10 个非常经典的机器学习的算法。

- 对于监督式学习，有如下经典算法。
  1. [决策树（Decision Tree）](https://en.wikipedia.org/wiki/Decision_tree)，比如自动化放贷、风控。
  2. [朴素贝叶斯分类器（Naive Bayesian classifier)](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)，可以用于判断垃圾邮件、对新闻的类别进行分类，比如科技、政治、运动、判断文本表达的感情是积极的还是消极的、人脸识别等。
  3. [最小二乘法（Ordinary Least Squares Regression）](https://en.wikipedia.org/wiki/Ordinary_least_squares)，是一种线性回归。
  4. [逻辑回归（Logisitic Regression）](https://en.wikipedia.org/wiki/Logistic_regression)，一种强大的统计学方法，可以用一个或多个变量来表示一个二项式结果。可以用于信用评分，计算营销活动的成功率，预测某个产品的收入。
  5. [支持向量机（Support Vector Machine，SVM）](https://en.wikipedia.org/wiki/Support_vector_machine)，可以用于基于图像的性别检测、图像分类等。
  6. [集成方法（Ensemble methods）](https://en.wikipedia.org/wiki/Ensemble_learning)，通过构建一组分类器，然后通过它们的预测结果进行加权投票来对新的数据点进行分类。原始的集成方法是贝叶斯平均，但最近的算法包括纠错输出编码、Bagging 和 Boosting。
- 对于无监督式的学习，有如下经典算法。
  1. [聚类算法（Clustering Algorithms）](https://en.wikipedia.org/wiki/Cluster_analysis)。聚类算法有很多，目标是给数据分类。有 5 个比较著名的聚类算法你必需要知道：[K-Means](https://en.wikipedia.org/wiki/K-means_clustering)、[Mean-Shift](https://en.wikipedia.org/wiki/Mean_shift)、[DBSCAN](https://en.wikipedia.org/wiki/DBSCAN)、[EM/GMM](https://en.wikipedia.org/wiki/Expectation–maximization_algorithm)、和 [Agglomerative Hierarchical](https://en.wikipedia.org/wiki/Hierarchical_clustering)。
  2. [主成分分析（Principal Component Analysis，PCA）](https://en.wikipedia.org/wiki/Principal_component_analysis)。PCA 的一些应用包括压缩、简化数据便于学习、可视化等。
  3. [奇异值分解（Singular Value Decomposition，SVD）](https://en.wikipedia.org/wiki/Singular-value_decomposition)。实际上，PCA 是 SVD 的一个简单应用。在计算机视觉中，第一个人脸识别算法使用 PCA 和 SVD 来将面部表示为 " 特征面 " 的线性组合，进行降维，然后通过简单的方法将面部匹配到身份。虽然现代方法更复杂，但很多方面仍然依赖于类似的技术。
  4. [独立成分分析（Independent Component Analysis，ICA）](https://en.wikipedia.org/wiki/Independent_component_analysis)。ICA 是一种统计技术，主要用于揭示随机变量、测量值或信号集中的隐藏因素。

如果你想了解更全的机器学习的算法列表，你可以看一下 Wikipedia 上的 [List of Machine Learning Algorithms](https://en.wikipedia.org/wiki/Outline_of_machine_learning#Machine_learning_algorithms)。

在 [A Tour of Machine Learning Algorithms](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) ，这篇文章带你概览了一些机器学习算法，其中还有一个 " 脑图 " 可以下载，并还有一些 How-To 的文章供你参考。

对于这些算法，[SciKit-Learn](http://scikit-learn.org/stable/)有一些文档供你学习。

- [1. Supervised learning](http://scikit-learn.org/stable/supervised_learning.html#supervised-learning)
- [2.3 Clustering](http://scikit-learn.org/stable/modules/clustering.html#clustering)
- [2.5. Decomposing signals in components (matrix factorization problems)](http://scikit-learn.org/stable/modules/decomposition.html#decompositions)
- [3. Model selection and evaluation](http://scikit-learn.org/stable/model_selection.html#model-selection)
- [4.3. Preprocessing data](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing)

### [相关资源](#table-of-contents)

- 对于初学者来说，动手是非常非常重要的，不然，你会在理论的知识里迷失掉自己，这里有篇文章 "[8 Fun Machine Learning Projects for Beginners](https://elitedatascience.com/machine-learning-projects-for-beginners)"，其中为初学者准备了 8 个很有趣的项目，你可以跟着练练。
- 学习机器学习或是人工智能你需要数据，这里有一个非常足的列表给你足够多的公共数据 – 《[Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)》，其中包括农业、生物、天气、计算机网络、地球科学、经济、教育、金融、能源、政府、健康、自然语言、体育等。
- GitHub 上的一些 Awesome 资源列表。
  - [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
  - [Awesome - Most Cited Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers)
  - [Awesome Deep learning papers and other resources](https://github.com/endymecy/awesome-deeplearning-resources)

### [小结](#table-of-contents)

总结一下今天的内容。我首先介绍了机器学习的基本原理：监督式学习和非监督式学习，然后给出了全世界最简单的入门资料 [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471)。随后给出了与机器学习密切相关的数据分析方面的内容和资料，然后推荐了深入学习机器学习知识的在线课程、图书和文章等，尤其列举了神经网络方面的学习资料。最后描述了机器学习的十大经典算法及相关的学习资料。

在机器学习和人工智能领域，我也在学习，也处于入门阶段，所以本文中推荐的内容，可能在你看来会有些浅。如果你有更好的信息和资料，欢迎补充。目前文章中给出来的是，我在学习过程中认为很不错的内容，我从中受益良多，所以希望它们也能为你的学习提供帮助。

## 前端基础和底层原理

### HTML5

### CSS

### JavaScript

### 浏览器原理

### 网络协议

### 小结

## 前端性能优化和框架

### 前端性能优化

### 前端框架

### React.js 框架

### Vue.js 框架

### 小结

## UI/UX设计

### 图书和文章推荐

### 原子设计（Atomic Design）

### 设计语言和设计系统

### 其它公司

### 动画效果设计

### 相关资源

#### 文章资源

#### 设计收集

### 小结

## [技术资源集散地](#table-of-contents)

### [个人技术博客](#table-of-contents)

首先，我先推荐一些不错的个人技术博客。

- [Coding Horror](https://blog.codinghorror.com/) ，这是杰夫·阿特伍德（Jeff Atwood）于 2004 年创办的博客，记录其在软件开发经历中的所思所想、点点滴滴。时至今日，该博客每天都有近 10 万人次的访问量，读者纷纷参与评论，各种观点与智慧在这里不断地激情碰撞。其博文选集在中国被翻译成《[高效能程序员的修练](https://book.douban.com/subject/24868904/)》，在豆瓣上有 8.3 的高分。2008 年，他和 Joel Spolsky 联合创办了 [StackOverflow](https://stackoverflow.com)问答网站，为程序员在开发软件时节省了非常多的时间，并开启了“StackOverflow Copy + Paste 式编程”。
- [Joel on Software](https://joelonsoftware.com/) ，Joel Spolsky 的这个博客在全世界都有很多的读者和粉丝，其博文选集在中国被翻译成《[软件随想录](https://book.douban.com/subject/4163938/)》在豆瓣上有 8.7 的高分。这是一本关于软件技术、人才、创业和企业管理的随想文集，作者以诙谐幽默的笔触将自己在软件行业的亲身感悟娓娓道来，观点新颖独特，简洁实用。
- [Clean Coder Blog](http://blog.cleancoder.com/) ，这是编程大师“Bob 大叔”的博客，其真名叫 Robert C. Martin，世界级软件开发大师，设计模式和敏捷开发先驱，敏捷联盟首任主席，C++ Report 前主编，被后辈程序员尊称为“Bob 大叔”。其博文选集在中国被翻译成《[程序员的职业素养](https://book.douban.com/subject/11614538/)》，在豆瓣上有 8.8 的高分。
- [Martin Fowler](https://martinfowler.com/) ，这是另外一个程序员大师，Martin 主要专注于面向对象分析与设计、统一建模语言、领域建模，以及敏捷软件开发方法，包括极限编程。他的《[重构](https://book.douban.com/subject/1229923/)》、《[分析模式](https://book.douban.com/subject/4832380/)》、《[企业应用架构模式](https://book.douban.com/subject/1230559/)》、《[领域特定语言](https://book.douban.com/subject/21964984/)》和《[NoSQL 精粹](https://book.douban.com/subject/25662138/)》都是非常不错的书。在他的博客上有很多很多的编程和架构模式方法可以学习。
- [Paul Graham Essays](http://www.paulgraham.com/articles.html) ，美国著名程序员、风险投资家、博客和技术作家。《[黑客与画家](https://book.douban.com/subject/6021440/)》是他的著作之一。2005 年他与人共同创建了著名的创业投资公司 Y Combinator，是初创公司最想被投的。他有几篇创业方面的文章都很经典，如果你想创业，可以读一读这几篇：《[How to Get Startup Ideas](http://paulgraham.com/startupideas.html)》、《[Do Things that Don’t Scale](http://paulgraham.com/ds.html)》、《[Startup = Growth](http://www.paulgraham.com/growth.html)》。Paul Graham 的文章以清新自然，思想深刻见长。不仅可以跟 Paul Graham 学创业，学思考，学技术，更可以学习写作。
- [Steve Yegge](https://medium.com/@steve.yegg) ，Steve Yegge 这个人算是一个知名的程序员了，在 Amazon 呆过，现在在 Google，他的文章都是长篇大论，最知名的文章就是[对 Amazon 和 Google 平台的吐槽](https://coolshell.cn/articles/5701.html)，这篇文章引发了大家的讨论和议论。
- [Bruce Eckel’s Programming Blog](http://bruceeckel.github.io/) ，《Thinking in Java》作者的博客，他之前的博客在 artima - [Computing Thoughts](https://www.artima.com/weblogs/index.jsp?blogger=beckel) 。
- [Herb Sutter](https://herbsutter.com/) ，C++ 大拿，C++ 标准委员会专家，微软软件架构师。《Exceptional C++ 》、《More Exceptional C++》、《Exceptional C++ Style》作者。
- [Eli Bendersky’s website](https://eli.thegreenplace.net/) ，这位老哥从 2003 年就一直写博客到今天，其中的文章都非常不错，原理型的，主要是 C、C++ 和 Python 相关的。里面有很多干货。
- [Peter Krumins’ blog ](http://www.catonmat.net/)，这位老哥从 2007 年开始写博客，他博客里好玩的东西太多了。
- [Brendan D. Gregg](http://www.brendangregg.com/index.html) ，Brendan 是 Netflix 的工程师，他的博客里有大量的非常非常不错的文章，基本上都是和 Linux 性能分析相关的，这是一个如果你要玩底层性能分析一定不能错过的博客。
- [Evan Klitzke](https://eklitzke.org/) ，主要讨论 Linux 和 C++ 相关的内容。
- [Julia Evans](https://jvns.ca/) ，主要讨论 Linux debug 工具和网络相关的内容。
- [null program](http://nullprogram.com/) ，和 C/C++ 相关的一个博客。其中关于 Linux 系统调用、GPU、无锁编程、JIT 编译的一些文章非常不错。
- [Fluent {C++}](http://www.fluentcpp.com/) ，博主是 Murex 的首席工程师，主要玩 C++，在这个博客里有很多很不错的 C++ 相关的文章。
- [Preshing on Programming](http://preshing.com/) ，这也是一个和 C/C++ 相关的博客，其中有很多的干货。
- [Programming is Terrible](https://programmingisterrible.com/) ，这个博客有很多强观点的文章，主要是软件开发中的一些教训。
- [Accidentally Quadratic](https://accidentallyquadratic.tumblr.com/) ，姑且翻译成事故二次方，这里有好些非常有趣的文章。
- [Hacker Noon](https://hackernoon.com/) ，这是一个一堆人在写的博客，里面有很多质量很高的文章。

其实还有很多不错的博客，不过，现在国外不错的博客都在一个叫 [Medium](https://medium.com/) 的网站，我也发现我 Google 很多东西时都会到这个网站上。这个网站上的内容不只有技术的，还有很多很多其他方面的内容，比如文化、艺术、科学等等。这个网站就是一个博客发布系统，其是由 Twitter 联合创始人埃文·克拉克·威廉姆斯（Evan Clark Williams）和克里斯多福·艾萨克·比兹·斯通（Christopher Isaac Biz Stone）创办的，这两个人觉得 Twitter 上全是垃圾没有营养的信息。所以，创办了 Medium，这个平台上有专业和非专业的贡献者，亦有受雇的编者。

我已经感觉到，未来高质量的文章都会在 Medium 这个平台上出现，因为有一些公司的技术博客也在这个平台上发布了，比如 Netflix 的。所以，你有必要上到这个平台上 follow 一些作者、专栏和主题。

### [YouTube 技术频道](#table-of-contents)

下面是我订阅的一些我认为还不错的和编程相关的频道，推荐给你。

- [Devoxx](https://www.youtube.com/channel/UCCBVCTuk6uJrN3iFV_3vurg) ，Devoxx 的频道，其中有各种很不错的技术分享。
- [Coding Tech](https://www.youtube.com/channel/UCtxCXg-UvSnTKPOzLH4wJaQ) ，也是个非常不错的编程频道，涵盖各种技术。
- [Amazon Web Services](https://www.youtube.com/channel/UCd6MoB9NC6uYN2grvUNT-Zg)
- [Facebook Developers](https://www.youtube.com/user/FacebookDevelopers/)
- [Google Developer](https://www.youtube.com/user/GoogleDevelopers) ，Google 公司的官方频道，其中包括 Google I/O 大会、教程、新闻、最佳实践、技巧分享……
- [Spring Developer](https://www.youtube.com/user/SpringSourceDev) ，Spring 的官方频道。
- [Microsoft Research](https://www.youtube.com/user/MicrosoftResearch)
- [MIT 公开课](https://www.youtube.com/user/MIT)
- [Stanford Online](https://www.youtube.com/user/stanfordonline)
- [Prof. Dr. Jens Dittrich](https://www.youtube.com/user/jensdit) ，一个德国教授开的一个关于数据库相关的频道，里面有很不错的数据库内在原理的内容。
- [Red Hat Summit](https://www.youtube.com/user/redhatsummit) ，RedHat 峰会频道，其中有很多和 Linux 相关的技术新闻和分享。
- [Open Networking Summit](https://www.youtube.com/user/OpenNetSummit) ，这是一个网络相关的频道。
- [Dan Van Boxel](https://www.youtube.com/user/dvbuntu/) ，这是一个机器学习工程师折腾各种事的视频，挺有意思的。
- [The New Boston](https://www.youtube.com/user/thenewboston/) ，这个频道应该是前端开发工程师必去的地方，可能也是我所知道的最好的关于前端技术的 YouTube 频道。
- [Derek Banas](https://www.youtube.com/user/derekbanas) 是一个教程型的频道，其中包括编程语言、游戏开发、Web 开发……我个人觉得是一个可以用来练英文听力的频道。
- [Java](https://www.youtube.com/user/java/) ，Java 相关的各种分享。
- [CppCon](https://www.youtube.com/user/CppCon) ，C++ 大会的一些视频，可以让你了解很多 C++ 最新功能和相关的动态。
- [Computerphile](https://www.youtube.com/user/Computerphile) ，这个频道是布雷迪·哈伦（Brady Haran）运作的几个频道中的一个，在这个频道里你可以看到很多很有趣的技术方面的科普教程、资讯、见闻等，说得都非常地简单易懂，所以有大量的订阅用户。布雷迪是个对任何技术都很有热情的人，这个频道是关于计算机技术的。除此之外，他还运作 [Numberphile](https://www.youtube.com/user/Numberphile)（数学）、[Periodic Videos](https://www.youtube.com/user/periodicvideos)（化学）、[Sixty Symbols](https://www.youtube.com/user/sixtysymbols)（物理）、[Deep Sky Videos](https://www.youtube.com/user/DeepSkyVideos)（天文）等有众多阅人数的频道。如果你喜欢，你都可以一一订阅，感觉就是一个个人版的 Discovery。
- 关于安全，有如下四个频道你可以订阅一下：
  - [DEFCONConference](https://www.youtube.com/user/DEFCONConference) ，defcon.org 的官方频道。
  - [CCCen](https://www.youtube.com/user/CCCen) ，Chaos Computer Club。
  - [RSA Conference](https://www.youtube.com/user/RSAConference) ，RSA Conference。
  - [Black Hat](https://www.youtube.com/user/BlackHatOfficialYT) - Black Hat Conference。

### [各大公司技术博客](#table-of-contents)

细心的你一定会发现这份攻略中的很多推荐文章都来自于各个公司的技术团队的博客。是的，跟随这些公司的博客，你不但可以看到这些公司的工程技术，还能掌握到一些技术方向和趋势。

下面是 Airbnb、AWS、Cloudera、Dropbox、Facebook、Google 等各个公司的技术博客列表。

- [Airbnb Engineering](http://nerds.airbnb.com/)
- AWS 相关
  - [All Things Distributed](https://www.allthingsdistributed.com/)
  - [AWS Architecture Blog](https://aws.amazon.com/cn/blogs/architecture/)
  - [On Efficiency, Reliability, Scaling - James Hamilton, VP at AWS](http://mvdirona.com/jrh/work/)
- [Bandcamp Tech](http://bandcamptech.wordpress.com/)
- [BankSimple Simple Blog](https://www.simple.com/engineering/)
- [Bitly Engineering Blog](http://word.bitly.com/)
- [Cloudera Developer Blog](http://blog.cloudera.com/blog/)
- [Dropbox Tech Blog](https://tech.dropbox.com/)
- [Etsy Code as Craft](http://codeascraft.com/)
- [Facebook Engineering](https://www.facebook.com/Engineering)
- [Flickr Code](http://code.flickr.net/)
- [Foursquare Engineering Blog](http://engineering.foursquare.com/)
- [Google Research Blog](http://googleresearch.blogspot.com/)
- [Groupn Engineering Blog](https://engineering.groupon.com/)
- [High Scalability](http://highscalability.com/)
- [Instagram Engineering](http://instagram-engineering.tumblr.com/)
- [LinkedIn Engineering](http://engineering.linkedin.com/blog)
- [Oyster Tech Blog](http://tech.oyster.com/)
- [Pinterest Engineering Blog](http://engineering.pinterest.com/)
- [Quora Engineering](http://engineering.quora.com/)
- [Songkick Technology Blog](http://devblog.songkick.com/)
- [SoundCloud Backstage Blog](https://developers.soundcloud.com/blog/)
- [Square The Corner](http://corner.squareup.com/)
- [The Reddit Blog](http://www.redditblog.com/)
- [The GitHub Blog](https://github.com/blog/category/engineering)
- [The Netflix Tech Blog](http://techblog.netflix.com/)
- [Twilio Engineering Blog](http://www.twilio.com/engineering)
- [Twitter Engineering](https://engineering.twitter.com/)
- [WebEngage Engineering Blog](http://engineering.webengage.com/)
- [Yammer Engineering](http://eng.yammer.com/blog/)
- [Yelp Engineering Blog](http://engineeringblog.yelp.com/)
- [Smarkets Blog](https://smarketshq.com/)

### [论文](#table-of-contents)

要想将技术研究得精深，论文是必不可少的。那要如何读论文呢？

#### [如何读论文](#table-of-contents)

下面有几篇文章，教你一些读论文的方法，非常不错。

- [How to read an academic article](http://organizationsandmarkets.com/2010/08/31/how-to-read-an-academic-article/)
- [Advice on reading academic papers](https://www.cc.gatech.edu/~akmassey/posts/2012-02-15-advice-on-reading-academic-papers.html)
- [How to read and understand a scientific paper](http://violentmetaphors.com/2013/08/25/how-to-read-and-understand-a-scientific-paper-2/)
- [Should I Read Papers?](http://michaelrbernste.in/2014/10/21/should-i-read-papers.html)
- [The Refreshingly Rewarding Realm of Research Papers](https://www.youtube.com/watch?v=8eRx5Wo3xYA)

#### [论文集散地](#table-of-contents)

要成长为一个高手，论文是你一定要读的。下面是一些非常不错的计算机方面的论文集散地。

- [2 Minute Papers](https://www.youtube.com/user/keeroyz) ，这是一个 YouTube 的频道，其会给出一些非常不错的和计算机相关的论文介绍，让你了解目前最有意思的一些科学突破，每次两分钟左右。

- [Best Paper Awards in Computer Science](http://jeffhuang.com/best_paper_awards.html) ，从 1996 年以来，获奖的计算机科学方面的论文收集。

- [Google Scholar](http://scholar.google.com/citations?view_op=top_venues&hl=en&vq=eng) ，Google 学术搜索（英语：Google Scholar）是一个可以免费搜索学术文章的网络搜索引擎，由计算机专家阿努拉格·阿查里雅（Anurag Acharya）开发。2004 年 11 月，Google 第一次发布了 Google 学术搜索的试用版。该项索引包括了世界上绝大部分出版的学术期刊。

- [Facebook](https://research.fb.com/publications/) ，Facebook 公司的论文。

- [Research at Google](https://research.google.com/pubs/papers.html) ，Google 发布一些论文。

- [Microsoft Research](http://research.microsoft.com/apps/catalog/default.aspx?t=publications) ，微软发布的论文。

- [MIT’s Artificial Intelligence Lab Publications](http://dspace.mit.edu/handle/1721.1/39813) ，MIT 和人工智能相关的论文。

- [MIT’s Distributed System’s Reading Group](http://dsrg.pdos.csail.mit.edu/) ，MIT 和分布式系统相关的论文。

- [arXiv Paper Repository](http://arxiv.org/) ，arXiv 是一个收集物理学、数学、计算机科学与生物学的论文预印本的网站，始于 1991 年 8 月 14 日。截至 2008 年 10 月，arXiv.org 已收集超过 50 万篇预印本。至 2014 年底，藏量达到 1 百万篇。

  在 2014 年时，约以每月 8000 篇的速度增加。arXiv 的存在是造就科学出版业中所谓开放获取运动的因素之一。[现今的一些数学家及科学家习惯先将其论文上传至 arXiv.org](http://xn--arXiv-fg1hkcv1bsq8ou4ah3qdrav4x3y4aba27kca63mi37cvtv0oa620yrgo0ot6k2c1f3c.org)，再提交予专业的学术期刊。这个趋势对传统学术期刊的经营模式造成了可观的冲击。

- [SciRate](https://scirate.com/) ，arXiv 上的论文太多，所以，SciRate 索引了 arXiv 上的一些好评的论文，并供大家评论和打分。（[开源代码](https://github.com/scirate/scirate)。）

- [cat-v.org](http://doc.cat-v.org/) ，这个网站，不只有论文，还有技术手册或是一些有意思的文章，包括一些历史资料什么的。

- [Usenix: Best Papers](https://www.usenix.org/conferences/best-papers) ，Usenix 上推荐的最佳论文。

- [The Morning Paper](https://blog.acolyer.org/) ，该博客会每天推送一篇论文，特别棒。

- [Lobste.rs tagged as PDF](https://lobste.rs/t/pdf) ，Lobsters 是一个聚焦于技术的社区，主要是链接聚合和对话题进行讨论。其中的 PDF 分类可以认为也是一个论文的集散地。

- [Papers We Love](https://github.com/papers-we-love/papers-we-love) ，GitHub 上的一个近 3 万颗星的计算机科学方面的论文社区。

### [小结](#table-of-contents)

总结一下今天的内容。这篇文章我主要跟你分享了一些好的学习资源，帮你开拓眼界，为后续学习夯实基础。

首先，我推荐了 Coding Horror、Joel on Software、Clean Coder Blog、Martin Fowler、Paul Graham Essays 等多个知名的个人技术博客。然后分享了一些我订阅的我认为还不错的和编程相关的 YouTube 频道，比如 Coding Tech、Amazon Web Services、Facebook Developers、Google Developer 等。

随后是 Airbnb、AWS、Cloudera、Dropbox、Facebook、Google 等各个公司的技术博客，跟随这些公司的博客，你不但可以看到这些公司的工程技术，还能掌握到一些技术方向和趋势。最后，想成长为一个高手，论文是一定要读的。所以，我给出了一个非常不错的计算机方面的论文集散地，并推荐了一些学习资源来教你如何读这些论文。

我一直认为，学习需要自我驱动，要学会自己“找食物”，而不是“等着喂”。程序员练级攻略 2018 版到今天就全部更新完成了，但我认为，这其实只是技术练级的起点，还有很多知识和技术，需要我们不断地去探索和发现。加油，我能做到的，你一定也可以做到。

## [面试前的准备](#table-of-contents)

### [怎样写简历](#table-of-contents)

当然，**我们知道真正的好简历是要用自己的经历去写的**，比如，有人的简历就是一句话：我发明了 Unix。

你要去那些能让你的简历有更多含金量的公司工作，要做那些能让你的简历更闪亮的工作。这是写简历的最佳实践——用自己的经历聊，而不是用文字写。

- **自我简介**。这个自我简介是用最简单的话来说明自己的情况，不超过 200 字。比如：10+ 年的软件开发经验（说明你的主业），4+ 年的团队 leader 经验（说明你的领导力），擅长高可用高性能的分布式架构（说明你的专业和专攻），多年互联网和金融行业背景（说明你的行业背景），任职于 XXX 公司的 XX 职位（说明你的职业），负责 XXX 平台或系统（说明你的业务场景）……
- **个人信息**。这里有几点需要注意。
  - **基本信息**。电子邮箱建议用 Gmail，千万不要用 QQ 邮箱，要让人感觉职业化一些。
  - **个人网站**。如果你有个人主页、博客、GitHub 或是 Stack Overfow，请一定附上，这是加分项。如果个人主页或博客有独立域名，那更好，这会给人一种你爱动手做事的感觉。页面也要干净有美感，这样会让人感觉你有品味。
  - **网站内容**。一般来说这些项都会被面试官点看浏览，所以，里面的内容你需要小心组织和呈现，千万不要造假。另外，除了技术上的一些知识总结（不要太初级，要有深度的、原理型的、刨根问底型的文章），你也可以秀一秀自己的技术价值观（比如，对代码整洁的追求，对一些技术热点事件的看法），这会让你更容易获得面试官的好感。面试官的好感很重要。
  - **作品展**。如果你有一些作品展现，会更好。当然，对于前端程序员来说，这是比较容易的。而对于后端程序员来说，这会比较难一些，只能展示一下自己的 GitHub 了。如果你有一些比较不错的证书或奖项（如微软的认证、Oracle 的认证），也可以展示一下。
- **个人技能**。个人信息下面你应该罗列几条个人的技能。这些内容要能很明显地让对方了解你掌握的技术和熟悉的领域。
  - **技术技能栈**。其中包括你擅长和会用的编程语言（如 Java、Go、Python 等），编程框架或一些重要的库（如 Spring Boot、Netty、React.js、gRPC 等），熟悉的一些技术软件（如Redis、Kafka、Docker 等），设计或架构（如面向对象设计、分布式系统架构、异步编程、高性能调优等）。
  - **技术领域**。前端、算法、机器学习、分布式、底层、数据库等。
  - **业务领域**。一方面是行业领域，如金融、电商、电信等，另一方面是业务领域，如 CRM、支付、物流、商品等。
  - **经验和软技能**。带过多少人的团队、有多少年的项目管理经验、学习能力如何、执行力怎么样、设计过什么样的系统。（不要太多，几句话就好。）

其实和用人单位发布的招聘信息中的职位技能需求很相似。有时候我都在想，明明用人单的职位需求里写成那样，为什么应聘人还不依葫芦画瓢呢？所以，对应于你的简历，如果能和职位需求看齐有相类似的描述，这样可以快速地让人觉得你和要应聘的职位很匹配。

- **工作经历和教育经历**
  - 列一下你的工作经历。每份工作完成的主要项目（不要列一大堆项目，挑重要的），主要突出项目的难度、规模、挑战、职责，以及获得的认可和荣誉。
  - 工作经历和教育经历，主要是对上述的个人技能的印证。不要东拉西扯，要紧紧地围绕着你的技能、特长和亮点来展开。

一般来说，你简历中的内容最好控制在两页 A4 纸以内，最好有中英文版，简历不要是 Word 版的，最好是 PDF 版，然后简历的格式和风格请参考 LinkedIn 上的（在 微软的 Offce 模板网站 上也能找到一些不错的简历模板）。简历的内容不要太多，内容太多，重点就不明显了。写简历的目的是呈现自己的特长、亮点和特点。只要你能呈现出 2-3 个亮点和特长，就可以吸引到人了。

简历只是一块敲门砖。一些热门的公司和项目能够吸引到很多很多人的简历，所以，你要在众多的简历中脱颖而出。除了自己的经历和能力有亮点外，你还需要有吸引用人单位的方法。

有很多公司都是 HR 先来筛一遍简历，HR 其实并不懂技术，她们只会看你的过往经历、能力是否和职位描述上的匹配。如果简历上的经历和技术亮点不足的话，那么你可以在简历的版式和形式的制作上花些心思，以及在简历的自我描述中加上一些 " 虚 " 的东西。

比如 " 工作态度积极，不分份内和份外的事，只要对公司和个人有利，都会努力做好；勤奋踏实，热爱学习，喜欢做一个全栈工程师；善于发现问题，并解决问题……" 表示我虽然现在的经历和技能不足以打动你，但是我的态度端正，潜力巨大，你不能错过……

### [技术知识准备](#table-of-contents)

一般来说，你的简历上写什么，面试官就会问什么，所以，不要打自己的脸，精通就是精通，熟悉就是熟悉，了解就是了解。然后对于你列出来的这些技术，你一定要把其最基本的技术细节给掌握了。面试官一般也会逐步加大问题的难度和深度，看看你到底在哪个层次上。所以，你还是需要系统地看看书，才能应对面试官的问题。比如：

- 你写上了 Java，那么 Java 的基本语法都要了解，并发编程、NIO、JVM 等，你多少要有点儿了解，Spring、Netty 这些框架也要了解。
- 你写上了 Go，那么至少得把官网上的 Effective Go 给看了。
- 你写上了 Redis，那么除了 Redis 的数据结构，Redis 的性能优化、高可用配置、分布式锁什么的，你多少也要把官网上的那几篇文章读一读。
- 你写上了面向对象，那么怎么着也得把《设计模式》中的 23 个模式了解一下。
- 你写上了分布式架构，那么 CAP 理论、微服务架构、弹力设计、Spring Cloud、Cloud Native这些架构就要做到心里有数。
- 你写上网络编程，那么 TCP/IP 的三次握手，四次挥手，两端的状态变化你得知道吧，Socket 编程的那几个系统调用，还有 select、poll、epoll 这些异步 IO 多路复用的东西，你得知道。

总之，无论你在简历里写什么技术，这些技术的基础知识你都得学一下。本质上来说，这跟考试一样啊。你想想你是怎样准备期末考试的，是不是得把教科书上所有章节中的关键知识点都过一下？你不见得要记住所有的知识点，但是 80% 以上的关键知识点，你多少得知道吧。

### [算法题准备](#table-of-contents)

国外的公司一般还会面算法题，他们用算法题来过滤掉那些非计算机专业出身的人。国内的一些公司也一样，尤其是一些校招面试，也有很多算法题。所以，算法是很重要的，是你需要努力学习和准备的。

LeetCode 是一个不错的地方。如果你能完成其中 50% 的题，那么你基本上可以想面哪里就面哪里了。这里，你要知道，一些面试官也是新手，他们也是从网上找一些算法题来考你。所以，你不用太害怕算法题，都是有套路的。比如：

1. 如果是数据排序方面的题，那基本上是和二分查找有关系的。
2. 如果是在一个无序数组上的搜索或者统计，基本上来说需要动用 O(1) 时间复杂度的 hash 数据结构。
3. 在一堆无序的数据中找 top n 的算法，基本上来说，就是使用最大堆或是最小堆的数据结构。
4. 如果是穷举答案相关的题（如八皇后、二叉树等），基本上来说，需要使用深度优先、广度优先或是回溯等递归的思路。

5. 动态规划要重点准备一下，这样的题很多，如最大和子数组、买卖股票、背包问题、爬楼梯、改字符……这里有一个 Top 20 的动态规划题的列表 。
6. 一些经典的数据结构算法也要看一下，比如，二叉树、链表和数组上的经典算法，LRU 算法，Tier 树，字符串子串匹配，回文等，这些常见的题都是经常会被考到的。

基本上来说，算法题主要是考察应聘者是否是计算机专业出身的，对于基本的数据结构和算法有没有相应的认识。你做得多了，就是能感觉得到其中的套路和方法的。所以，本质来说，还是要多练多做。

### [工作项目准备](#table-of-contents)

无论什么公司的面试，都会让你说一个你做过的项目，或是你过去解决过的一个难题。但我很好奇
怪，这种必问的题，为什么很多应聘者都没有好好准备一下。
一般来说，会有下面这样的几个经典的面试问题。
1. 说一个你做过的最自豪的项目，或是最近做过的一个项目。
2. 说一个你解决过的最难的技术问题，或是最有技术含量的问题。
3. 说一个你最痛苦的项目，或最艰难的项目。
4. 说一个犯过的最大的技术错误，或是引发的技术故障。

对于上面这四个问题：第一个问题，主要是想看看你过去工作中做过的最高级的事是什么，还有你的兴趣点和兴奋点是什么；第二和第三个问题，主要是想看看你解决难题的能力，以及面对压力和困难时的心态；第四个问题，主要是想了解一下你面对错误时的态度，还要了解你是否会对错误有所总结和改进。

这些问题都会伴随着对各种细节的不停追问，因为这样的问题太容易造假了。所以，面试官会不停地追问细节，就像审问一样。因为一个谎言需要用更多的谎言来掩盖，如果没有经过高强度和专业的训练的话，最好不要撒谎。因此对于业余的不是做特工或是间谍的人来说，谎言是经不起追问的。

怎样准备这样的题，我这里有几个提示。

- **要有框架**。讲故事要学会使用 STAR 。Situation - 在什么样的环境和背景下，Task - 你要干什么样的事，Action - 你采取了什么样的行动和努力，Result - 最终得到了什么样的效果。这是整个语言组织的框架，不要冗长啰嗦。
- **要有细节**。没有细节的故事听起来就很假，所以，其中要有很多细节。因为是技术方面的，所以，一定要有很多技术细节。
- **要有感情**。讲这些故事一定要带感情。要让面试官感受到你的热情、骄傲、坚韧和顽强。一定要是真实的，只有真实的事才会有真实的感情。
- **要有思考**。只有细节和故事还不够，还要有自己的思考和得失总结，以及后续的改进。

要做到上述，是不容易的。一般来说，你也是需要训练的。首先，你要形成及时总结的习惯，对自己的日常工作和经历做总结，否则难免会有 " 书到用时方恨少 " 的感觉。另外，你还需要训练自己的语言组织能力。最后，你还要有对这些事件的思考，这需要和其他人进行讨论和总结。

对此，如果你想有一个比较好的面试回答效果，这不是你能临时准备出来的，工夫都是花在平时的。而训练这方面能力的最好方式就是在工作中写文档 ，在工作之余写博客。只有写得多了，写得好了，你这样的能力才能训练出来。

## [面试中的技巧](#table-of-contents)

### [形象和谈吐](#table-of-contents)

每个人都喜欢和开朗风趣积极向上的人相处。经常微笑，表现出自己的热情，适当开开玩笑，自嘲一下，会让人觉得你很容易亲近。交谈时千万不要像挤牙膏一样，别人问你一句，你答一句，要把完整的前因后果讲完。别人问你个事，你就多分享一些这个事中的酸甜苦辣，把故事讲得生动有趣点儿，能逗笑 HR 妹子最好（但不要撩）。

说话的时候，要看着对方，一方面这是对对方的尊重和礼貌，另一方面，这也是一种自信。就算没有面好，也不要低着头，又不是做错了什么事。有什么事说不清楚的，不要犹豫，该画图画图。对于比较复杂的面试官听不懂的问题，要变换不同的方式来描述。

面试官问的问题，你要给出充足的细节，千万不要让面试官不断地追问，那样就被动了。你问我解决过的最难的问题是什么，我就把这个问题的来龙去脉和其中的各种细节给你滔滔不绝地讲个遍。当然，也要讲得清楚干净有条理，不要东拉西扯的，也不要云山雾罩的。这些表达和谈吐还是要多练！

### [答不出来](#table-of-contents)

很多时候，面试官并不期待你能在很短的时候内解出一道难题，他只是想看一下你遇到难题时的态度和思维方式。如果你能证明给面试官看，你解决问题的方向和方法是正确的，就算是没有找到答案，也是很不错的。因为只要方向走对了，剩下的就是时间问题了。

如果实在解不出来，或是被问了不懂的知识性问题，那么就直接说不懂就好了。记下来，回去多看多练，下次记住了就好。

另外，对于没有答上来的问题，有的人会在面试后请教一下面试官。但是我觉得更好的方式是，问面试官要个他的邮箱或微信，回去后，努力搞懂，举一反三，然后写个东西再发回去。这样做是有可能让你起死回生的哦。多少可以暗示对方：“你看，我有不懂的，但是我能下工夫很快就搞懂了，你看我的学习能力还不错哦。你就不再考虑一下了吗？”

### [尖锐问题](#table-of-contents)

应聘的时候，你有可能会被问到几个尖锐的问题，这时你要小心做答。一般来说，你会遇到这几个常见的比较尖锐的问题。

- **你为什么要离开现在的公司**？最标准的外交词令是：“我离开现有公司的原因是我太喜欢你们公司了”。当然，你也可以说前公司的问题，比如：自己心爱的项目被公司废弃了、公司转型了、公司业绩下滑了、在现有的公司没有成长空了…… 这些都还是可以说的。

- **说一下你的缺点**？并给出几个例子。我们每个人都应审视一下自己，思考一下自己光明面的后面。而回答这个问题的最佳方法，就是想想附着在正面事件上的阴暗面，那就是你的答案。比如，我对事情的要求太高了，跟我在一起工作人的压力太大。我太内向了，所以别人和我沟通起来有点费劲。我太过关心团队了，所以，有时候会忽略了项目成本和时间进度……

  **最后还要补一句，我知道我的缺点，我也在努力改正，我正在通过什么样的方式改正。这非常关键，因为这基本上是面试官最喜欢看到的答案了，就是你不仅能正视自己的缺点，而且还能不断地改正。**

  另外，与这个问题相对应的是，说一下你的优点。这个问题是比较坑的，你的优点是需要用证据来说明的。比如，我通常的回答是，我的优点就是学习能力强，因为我掌握的技术面很广，而且，我什么样的技术都学，比如最新的 Cloud Native 技术。作为后端人员我还学前端方面的技术如 React.js 和 Vue.js，这一切都来源于我扎实的基础知识……

  回答这个问题的时候，一般都会反衬出你的价值观，HR 就是想了解你的价值观。比如，我比较踏实，我想把技术一直做到老。再比如，我有韧性，我受过哪些挫折、失败、不公、无奈和无助，我没有当逃兵……

### [结尾问题](#table-of-contents)

一般来说，面试结束的时候，都会问你有没有什么问题。不要放弃这个机会。

- **如果你面得比较好**，这个时候可以问几个尖锐的问题，这样有利于后面谈 offer 和岗位（抓住机会反转被动为主动）。比如，我就问过国外某一线公司的面试官下面两组问题：

  - 你们公司有多少一线开发经理还在写代码？你们的一线经理都没有时间来写代码了，不知道细节怎么做好管理？另外是不是说明你们公司有大量的内耗？
  - 任何公司都有好的有不好的，你能不能分享一下你最喜欢这个公司的地方和最不喜欢的地方？

  基本上来说，面试官都会被我问住，然后开始语塞。能让说英语母语的老外在我这个英文一般的人面前说不清话，我还是很满足的。哈哈哈。当然，也不一定是非要像我这么尖锐地问问题，你也可以设计几个柔和一点儿的问题。总之，问这样问题的目的是，暗示一下对方，我来不来还不一定呢，也别想压低我的 offer，你们公司也不是什么都好，要想让我来，得再加点……（嘿嘿嘿）

- **如果你面得一般**，这个时候你也可以问些加分的问题。比如：目前贵公司或是贵团队最需要解决什么样的问题？我能帮贵公司做些什么？能不能给我一些资料我先了解一下，这样我后面如果能进来，就能上手更快一些了。因为你面得一般的话，面试官会比较犹豫和纠结，此时你需要让面试官不要犹豫，所以，你可以表现得更加热情和主动一点。你看，竟然一副通过面试明天就要上班的 " 无耻嘴脸 " 也会为你加点分的……（哈哈哈）

- **如果你面得很不行，基本挂掉了**。这个时候，也要问问题。但最好问一下面试官对你的评价，并且让他指出你的不足和需要改进的地方。面试本来就是一次经历和一次学习，你也可以把其当作是一种受教育的过程。所以，不要放过自己可以成长的机会。通过面试官给你的评价，你日后就知道自己需要努力的地方和方向了。这是多好的一件事儿啊。

## [面试风格](#table-of-contents)

回答完这些知识性的问题，就是项目经历描述了。你可以随便讲你做过的项目，把这个项目用到的一些技术架构都说清楚就好了，还有怎么上线的，怎么运维的，怎么加班的，怎么苦逼的，怎么带人的，怎么管理项目的。面试官也很少追问技术细节，因为可能面试官自己都不懂（哈哈）。

只要你按照我前面说的那个讲项目的方式来，面试官一看你用到的技术栈和我这边的很类似，他就开始想要你了。当然，国内的公司更多的是缺劳动力，所以，只要你能让他们感到你很能吃苦耐劳、任劳任愿，而且能很快上手干活就好了。

然后就是 HR 和老板的面试了，HR 和老板不懂技术，也不会问你技术问题，他们主要是看看你的性格和态度等。只要你表现能吃苦耐劳，踏实肯干，如果还有一点 " 灵性 "（脑子转得快，与人好沟通，一来一回有问有答，性格外向点儿），在国内的面试你是很容易通过的。

基本上来说，国内公司喜欢快进快出，也就是说，不在面试上花太多的精力，进来就干活，不行就开掉，基本上是找工人找劳动力的玩法，也不关心员工的成长。所以，面试过程基本上来说，都是围绕你干什么，我这边这些事你会不会干，你会不会加班、能不能吃苦耐劳，听不听话等这样的内容进行的。

当然，对于架构师或是高级别的技术人员，又是另一种面试方式，这在国内的大公司中得分两种。

- 一种是业务型部门的高级技术人员，基本上来说，不会再问你一些技术的细节，只会问你一些架构方面、项目管理方面，以及技术方面的事，或者一些业务架构上的事情。相对来说，业务或应用方面的架构师和高级工程师需要对业务和行业比较了解，有丰富的业务项目经验就好了，技术上倒不需要有多深的知识。我觉得，在一个行业呆久了，只要你对业务有思考，再加上有技术把持，基本上来说，只要平时多读一些不错的业务上的想法，还是比较好过的（因为不会问及细节问题）。
- 另一种是偏技术部门的架构师和高级工程师，比如核心基础技术，或是云计算之类的。那就会问你很多技术细节上的东西了，而且问得还很深，需要你有相应的项目经验，或是开源社区里的工作经验。你需要有过相当的经历才有可能面过。但是，回过头来说，就算是这样的岗位，本质上还是会回到面知识型问题的方法，所以，无非就是你能钻研的知识深一点儿罢了。知识是死的，只要你努力，你总有一天能学会的。

总体来说，与国外公司相比，国内的公司不管是哪个层级上的面试都是比较好通过的。

## [实力才是王中王](#table-of-contents)

### [程序员练级攻略](#table-of-contents)

对于后端程序员来说，C、C++ 和 Java 是一定要学好的，TCP 网络和 Linux 系统编程也是需要学好的。《练级攻略》中那些资料如果你能全部吃透和掌握的话（也就是“编程语言”和“系统知识”这两个章节），那么，中国的所有公司你都可以进，包括 BAT，职位可以面到一级的高级工程师。年薪至少 30 万左右。

如果你要更为底层的话，那么需要掌握高手篇中的“Linux 系统、内存和网络”、“异步 I/O”、“Lock-Free”，以及“Java 的底层知识”，把里面的那些资料都看懂学透，那么，你可以面过年薪 50 万的职位。这是没有问题的。

如果你要往架构师方面发展，一方面你需要有足够多的经验，以及相关的项目实施经验，这需要在相当的大公司里做过相应的项目和架构。再辅助于高手篇中的分布式架构的三篇：入门、经典图书和论文和工程设计，以及微服务和容器化这些内容，我保证你至少可以拿到年薪 60 万以上的工作。

前端的东西如果要学习好的话，并不难。攻略中也有三篇和前端相关的文章，那三篇文章学习个 3-5 年，你也是一个非常牛逼的前端工程师了，能找到 30 万 - 50 万的工作应该没什么问题。只不过，如果你还想更好的话，你需要走两个方向，一个是设计（不是软件设计，而是 UI/UX 设计），另一个是后端架构技术。

你一定要明白，真正解决用户的问题的不是前端技术，而且是后端的业务逻辑和数据计算。**前端并不是计算机的本质，计算机提升社会运作效率并不是靠前端完成的，而是靠自动化来完成的，前端只是辅助。**

另外，如果你今天还在做支持性的工作，那么你要赶快转到产出性的工作上去，不然的话，你未来也危险了。比如像：测试、运维、项目管理等，这些都是支持性的工作。我个人建议你转到开发工作上，比如开发测试工具，开发运维系统和工具，开发项目管理软件……只有到了开发上，你才会有更好的发展空间。

### [面试的训练](#table-of-contents)

对面试来说，比较好的训练就是要经常出去面试，所以还是应该隔三岔五就出去面试一下的。一方面可以攒攒经验值，可以训练一下自己的语言表达能力和应对各种问题的回答。另一方面更重要，可以了解一下目前市场的需求（技术、技能和业务），同时了解一下自己的身价。

你之所以会紧张，会不知所措，会感到不适，会觉得难，大多数情况下是因为你不熟悉这个环境，你对这个环境还很陌生。只要你面得多了，你就会熟悉这个环境，你也就能驾轻就熟了。“老司机”之所以能成为“老司机”，还不是因为经常跟女孩子聊天交谈，时间长了，就成老司机了。

另外，对于语言组织的训练，除了多多与人交流，还有就是你平时需要多看多写，喜欢看书和写作的人通常在语言表达能力方面也不会差，而反之则通常会比较差。所以，写 blog，表达自己的想法是很重要的。

### [跳槽和升职](#table-of-contents)

有人说，跳槽是升职加薪最好的手段，这么说也有一定道理，因为只有用人单位在竞争你，你的职位和薪资才能提得上去。如果你想靠公司的良心，这是比较难的，除非你非常非常出色。很多人都是会以跳槽来作为升职或加薪的手段的。

我认为，对于一个人来说，适当的跳槽还是很必需的。有些时候，在一个地方做得再好，也要出去看看外面的世界是什么样的。一方面，有了对比后，你才会更明白自己要什么，另一方面，想把握趋势和行业动态，也需要你跳槽。只是跳槽不宜太频繁，最好不要低于两年换一次，而且最好承前启后，不要有太多的过渡。

如果你想在一家公司内从普员工升职到公司高管这个可能还是有点难的，所以，通过跳槽的方式来达到这一目标还是可能的。但是，这需要一定的策略。比如，你需要先去世界顶尖公司，在里面做到高级技术人员的级别，甚至可能你先要去读书深造。总之，你需要先进入国外一流公司（比如微软），然后，在里面升 1 或 2 级，然后可以跳到另一家相当的公司（比如谷歌或亚马逊）。

此时，你的简历会非常亮眼了，只要你的级别是高级程序员（对应于亚马逊的 SDE3），你会成为国内各大公司追捧的人才，你回国到 BAT 这样的公司里做个高级管理人员是没有任何问题的。然而，如果你一开始不是去这些顶尖公司，而是直接到 BAT 里做个程序员，我觉得未来能上到中高层的机会不会多。

总之，如果你决定在职场大展宏图的话，那么在年轻的时候，让自己的简历变得越漂亮越好。最好是先去国外，然后在需要职业成长的时候，被国内公司重金请回来，会比直接在国内的公司里发展要好一些。这是我个人觉得比较好的方式。

### [最重要的事](#table-of-contents)

程序员面试中，最重要的事还是自己技术方面的能力，国内会注重你的项目经验，国外会注重你的基础知识、项目经验、解题思路，以及软件设计能力。所以，要努力提高自己的这些技术技能和见解。

在《程序员练级攻略 2018》这一系列文章中，除了一个大型的地图，以及很多技术的学习资料和资源外，我也给出了很多公司的最佳实践和解题思路。就算你没有实工作经验，通过思考和研究这些前人的经验，站在巨人的肩膀上，会为你开启更大的舞台。当你去到这些大公司后，就可以把你学习到的这些知识立马用上。

当然，计算机软件开发是一件动手能力很强的事，所以，你需要不断地动手。好在这个世界有开源项目，加入开源项目会比加入一个公司的门槛要低得多。你完全可以到开源项目中攒经验，这可能会比在工作中攒到的经验更多。

总之，我想说的是，要应付并通过面试并不难，但是，千万不要应付你的人生，你学技术不是用来面试的，它只是你谋生的技能，要尊重自己的谋生技能，说不定，哪天你还要用这些技能造福社会、改变世界的。
