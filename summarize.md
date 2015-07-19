# 综述  
  
大家好哈，最近博主在学习 Python，学习期间也遇到一些问题，获得了一些经验，在此将自己的学习系统地整理下来，如果大家有兴趣学习爬虫的话，可以将这些文章作为参考，也欢迎大家一共分享学习经验。

Python 版本:2.7，Python 3 请另寻其他博文。

首先爬虫是什么？

>网络爬虫（又被称为网页蜘蛛，网络机器人，在 FOAF 社区中间，更经常的称为网页追逐者），是一种按照一定的规则，自动的抓取万维网信息的程序或者脚本。
根据我的经验，要学习 Python 爬虫，我们要学习的共有以下几点：

- Python 基础知识
- Python 中 urllib 和 urllib2 库的用法
- Python 正则表达式
- Python 爬虫框架 Scrapy
- Python 爬虫更高级的功能  

## Python 基础学习

首先，我们要用 Python 写爬虫，肯定要了解 Python 的基础吧，万丈高楼平地起，不能忘啦那地基，哈哈，那么我就分享一下自己曾经看过的一些 Python 教程，小伙伴们可以作为参考。

### 慕课网 Python 教程  

曾经有一些基础的语法是在慕课网上看的，上面附有一些练习，学习完之后可以作为练习，感觉效果还是蛮不错的，不过稍微遗憾的是内容基本上都是最基础的，入门开始的话，就这个吧

学习网址：[慕课网Python教程](http://www.imooc.com/view/177)

### 廖雪峰 Python 教程  

后来，我发现了廖老师的 Python 教程，讲的那是非常通俗易懂哪，感觉也是非常不错，大家如果想进一步了解 Python 就看一下这个吧。

学习网址：[廖雪峰Python教程](http://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000)

### 简明 Python 教程  

还有一个我看过的，简明 Python 教程，感觉讲的也不错

学习网址：[简明Python教程](http://woodpecker.org.cn/abyteofpython_cn/chinese/pr01.html#s01)

## Python urllib 和 urllib2 库的用法

urllib 和 urllib2 库是学习 Python 爬虫最基本的库，利用这个库我们可以得到网页的内容，并对内容用正则表达式提取分析，得到我们想要的结果。这个在学习过程中我会和大家分享的。

## Python 正则表达式

Python 正则表达式是一种用来匹配字符串的强有力的武器。它的设计思想是用一种描述性的语言来给字符串定义一个规则，凡是符合规则的字符串，我们就认为它“匹配”了，否则，该字符串就是不合法的。这个在后面的博文会分享的。

## 爬虫框架 Scrapy

如果你是一个 Python 高手，基本的爬虫知识都已经掌握了，那么就寻觅一下 Python 框架吧，我选择的框架是 Scrapy 框架。这个框架有什么强大的功能呢？下面是它的官方介绍：

>HTML, XML 源数据 选择及提取 的内置支持
提供了一系列在 spider 之间共享的可复用的过滤器(即 Item Loaders)，对智能处理爬取数据提供了内置支持。
通过 feed 导出 提供了多格式(JSON、CSV、XML)，多存储后端(FTP、S3、本地文件系统)的内置支持
提供了 media pipeline，可以 自动下载 爬取到的数据中的图片(或者其他资源)。
高扩展性。您可以通过使用 signals ，设计好的 API(中间件, extensions, pipelines)来定制实现您的功能。
内置的中间件及扩展为下列功能提供了支持:
cookies and session 处理
HTTP 压缩
HTTP 认证
HTTP 缓存
user-agent模拟
robots.txt
爬取深度限制
针对非英语语系中不标准或者错误的编码声明, 提供了自动检测以及健壮的编码支持。
支持根据模板生成爬虫。在加速爬虫创建的同时，保持在大型项目中的代码更为一致。详细内容请参阅 genspider 命令。
针对多爬虫下性能评估、失败检测，提供了可扩展的 状态收集工具 。
提供 交互式 shell 终端 , 为您测试 XPath 表达式，编写和调试爬虫提供了极大的方便
提供 System service, 简化在生产环境的部署及运行
内置 Web service, 使您可以监视及控制您的机器
内置 Telnet 终端 ，通过在 Scrapy 进程中钩入 Python 终端，使您可以查看并且调试爬虫
Logging 为您在爬取过程中捕捉错误提供了方便
支持 Sitemaps 爬取
具有缓存的 DNS 解析器  

官方文档：[http://doc.scrapy.org/en/latest/](http://doc.scrapy.org/en/latest/)

等我们掌握了基础的知识，再用这个 Scrapy 框架吧！