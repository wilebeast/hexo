title: 我是如何一个月学会cpp的
date: 2015-10-20 23:13:22
tags:
- cpp
categories:
- 编程
---
------

笔者现在就职于一家棋牌游戏公司，server组的，使用cpp开发。这是我的第二份工作，
这之前我是做了大概3年的嵌入式开发，纯C语言开发,完全没有面向对象的开发经验,但
是再离开之后，我决定做一些其他的东西（互联网server）。这个转型之快，我自己也
没有想到。因此觉得有必要写下来。

### 1.失败的尝试
c++ primer,cpp程序设计，一开始也是狂啃，好书是好书，不过当时没有实践（大忌）,
所以也是囫囵吞枣，看到后面愈发糊涂，继承&多态是难点，网上的帖子也是看得云里
雾里的。

### 2.反汇编解密
因为嵌入式的开发经历，让我有了反汇编的基础（笔者专门学过汇编）。再者，我当时认
为cpp仅是对c的一种封装而已，所以决定尝试反汇编来一探究竟。虽然不能完全看懂所有
的反汇编代码，但是关键的地方还是让笔者抓住了，继承的关键在于隐藏的this指针，而
多态的关键在于虚函数表。

### 反思总结
<ol>
<li>语言的教材，光看是没用的，还要上机实验才行</li>
<li>汇编还是很有用的，能够让程序员看到语言的本质</li>
</ol>