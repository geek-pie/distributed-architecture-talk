# Distributed-Systems
分布式系统学习

# Guide-如何拓宽知识边界

## 搜索最新计算机论文方法

* [DBLP](https://dblp.org/search/)
  
  DBLP是德国大学Universität Trier设立的计算机论文数据库，界面简洁，速度快，特别注意的是，非常非常的用户友好，提供各种引用格式，提供到IEEE或者ACM数据库的链接，支持对各种字段（会议、作者、时间）的AJAX搜索。
  比如搜索AAAI的最新论文。

* [semanticscholar](https://www.semanticscholar.org/)
   
   一个2015年出现的学术搜索引擎，优势是能尽量凸显出论文中最重要和最有影响力的元素
  
* 大名鼎鼎的[arxiv](https://arxiv.org/)
  
   arxiv是什么就不说了吧？
  
* [谷歌学术](https://scholar.google.com.hk/?hl=zh-CN)
* [Microsoft学术搜索](https://www.microsoft.com/en-us/research/search/)

PPT搜索： https://www.slideshare.net/

书籍搜索：https://books.google.com/?hl=zh-CN

## 论文期刊排名
[Wikipedia的协作排名](https://en.wikipedia.org/wiki/List_of_computer_science_conferences)

[CORE的排名](http://portal.core.edu.au/conf-ranks/?search=&by=all&source=CORE2014&sort=arank&page=1)

分布式系统重点关注：[ACM SIGMOD](http://www.sigmod.org/) 、[VLDB](http://www.vldb.org/) 、  [ICDE](http://www.icde.org/) 。但是还是有很多对于分布式系统或者算法没有在这上面发表。善用上面的搜索工具就很重要。
#学术界VS工业界
仔细一想，计算机科学里学术界和工业界其实隔得还挺远，虽然大家都在说两者在统一，有大牛横跨两界，其实不过是工业界大公司来学术界发了几篇论文，学术界用了工业界的数据来验证自己的idea罢了。
本质上两个圈子的工作方式完全不同。在方法论上，两者的区别在于：学术界讲究的是形式化的证明，因果律，实验科学发现新的insight；而工业界在乎运行效率，可靠性，成本，扩大规模。
在面向的目标上，两者的区别又在于：学术界需要通过在会议和期刊上发表论文，促进个人的学术成就（职称和学会荣誉），推动学科的发展，申请更多的项目经费；而工业界是通过市场来验证自己的技术方案，技术对产品和业务做更灵活可靠的支撑和创新。
通常大部分IEEE和ACM的论文数据库都是收费的，学校是肯定会购买相关数据库的。但是对于工业界来说，一来是难以购买下载；二来这些论文是给学术圈子内同行交流的，下下来也不一定看得明白。

下面就要推荐这样一个组织：USENIX，他们是早期（75成立）的Unix用户群，现在已经发展成一个紧密联合工业界的学术组织。
关键是：从2008年起，由USENIX发起的会议全程提供论文、演讲幻灯片和演讲视频的免费下载！

而这其中包含OSDI、NSDI、FAST这种重磅会议，通常工业界也会把他们的经验总结成论文发布在这里，例如Google的MapReduce、BigTable，Facebook的照片存储方案。我想纯学术圈的论文对于业界软件工程师的意义并不大，但是这些大厂发的工程经验就很有借鉴意义了，论文中有许多系统设计时可以借鉴的方案。

USENIX会议的网站：https://www.usenix.org/publications




## 形式化的证明
什么是形式化验证？
形式化验证是用数学方法去证明我们的系统是无Bug的，首要的一步是用数学语言描述清楚我们要解决的问题。
通过对问题建立数学模型，限定系统在不同时刻应该有的状态，以及不应该有的状态，然后用这些数学规则去限定系统的设计以及实现。**因此，如果想要看懂论文，了解这部分知识是非常有必要。**

当然了，如果是分布式的业务系统，测试都是可以覆盖的，肯定用不到。
但是如果是一个稳定的、长期的底层框架，肯定需要去数学证明合理性，测试用例是无法证明其完全正确的。

### Reference
* https://ying-zhang.github.io/misc/2016-we-love-paper/
* https://www.zhihu.com/question/20643420
* https://zhuanlan.zhihu.com/p/56369013
* 书籍：[形式化方法导论](https://book.douban.com/subject/26928529/)

# 目录说明

**持续更新中，欢迎Star！** 