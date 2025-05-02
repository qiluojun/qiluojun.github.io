---
title: 东京冒险记
date: 2024-08-24 15:20:15
tags: [旅行, 考试, 冒险]
categories: [生活记录]
keywords: [东京, 考试, 日本, 留学]
description: 这是一篇关于我在东京参加东大修士入学考试的经历和冒险的记录，记录了这个夏天难忘的经历。
cover: /images/tokyo_wuya.jpg
comments: true
toc: true
lang: zh-CN
---

2025.5 更新：
本来打算一考完试，就把经验贴写好发知乎。毕竟前辈们的经验贴对我帮助极大，我也想尽一份力。可惜咕咕到了现在！？


# 前言 

本文写于8.24下午。
上午刚刚结束了面试，也算是这个夏天的考试划上了句点（除了还要在紧张中等待最终的放榜🤣）。
活了这么久，第二十一年感觉上仿佛做了比前二十年加在一起还要多的事情。  
趁着记忆犹新，速速写下来吧！🥳

当然，因为这一年来发生的事情太多了，因此本文只记录这个夏天（6-8月）的事情🤣
其他的坑慢慢填~

# 正文！

## 择校、报名！

内容待补充

以及一把辛酸泪啊！

## 备考！！

内容待补充

## 考试！！！ 

### 日本游记 

！为什么贴不了图！

等我回头和hexo再搏斗一下，看看怎么在md文档里插图，再来写这一部分……

### 考试体验

#### 8.19 基础&专门

整体而言，我的感受还是很复杂的😭

感觉整体考得一般，尤其是专门，简直一言难尽……

但是也很开心。因为趁机学到了新东西，比如我这辈子都不会忘记constellation什么意思了(T_T)

##### 基础科 

和以往题型差不多，难度也还好。

其中有一道题是估算：一年里，人工林大概能吸收多少家庭的碳排放。
这题还蛮有意思的，倒不是说计算有多复杂，但是也确实让我感受到了数字上的一点小震撼哈哈哈~
> 以及希望我没有算错……

##### 曲折的专门科！！！😭

这门是我自我感觉发挥最不好的一门……

题型和前两年一模一样，术语看着很眼熟，算法也很简单，于是考场上的我以为：稳啦！

然后十分钟之后就被打脸了……

###### 术语

首先，术语，我很熟悉。要么是见过类似的术语，要么就是知道里面的每一个成分。
这说明我备考的时候，选择的教材还是很好的，也建立了对整个领域不错的理解。

但是里面大部分的原词我都没有见过，或者说只见过片段……所以只能凭借已有的知识进行猜测，拼运气了！

在考完之后，借助gpt的帮助，我成功地发现自己猜得不能说是大差不差，只能说是毫不相关了……〒▽〒

下面是详细的每个术语的考场心路历程&考完后的答案更正：

- Neural network Processing Unit
思路： 我知道啥是network 啥是processing unit 
那么这个要么是 处理network的unit 要么是模仿前者的unit 
我打草稿的时候，猜得是前者。但是写答案的时候，灵机一动，改成了猜测二（果然第一印象往往更可靠……）。
> 实际答案：
	A Neural Network Processing Unit (NPU) is a specialized hardware designed to accelerate machine learning tasks, particularly for deep learning models.
	这类硬件通过并行计算和加速特定操作（如矩阵乘法），可以显著提高机器学习任务的执行效率。和GPU与CPU相比，NPU更加高效，并且更适合处理复杂的神经网络运算任务

- Web Application Firewall
我知道firewall是啥 
但是不太清楚 WAF具体是什么 因此我猜测 是功能包括保护web server的 firewall
实际上这一题没这么简单！因为防火墙也分针对不同layer的类型！新知识get！
> 实际答案：
	security tool that monitors and filters incoming and outgoing HTTP/HTTPS traffic to protect web applications from attacks
	WAFs are specifically designed to secure the application layer, particularly focusing on traffic over the HTTP/HTTPS protocols.
	Traditional firewalls primarily operate at the network layer and transport layer, focusing on filtering IP packets that enter and exit a network

- Traveling Salesman Problem
我知道这是一类寻找最佳路径的问题,然后和多项式类问题有关
以及人类还没有给这类问题找到确定的解，不清楚能否把它转换成一个确定的多项式问题
但问题主要在于，我不记得，多项式这个词怎么拼写了😭…… （于是准备面试的时候反复练习polynomial这个词）
> 实际答案：
	a classic optimization problem where the goal is to find the shortest possible route that visits a set of cities and returns to the starting point 
	ambiguous nondeterministic polynomial 
	Whether all of the NP problems are also in P, however, we still don't know.
	NP-complete problems

- Satellite Constellation
我知道 satellite，知道卫星通信 
但是死活只觉得Constellation眼熟，就是想不起来什么意思……
所以只能努力写了卫星通信的特点和适用场景……
> 实际答案：
	A Satellite Constellation is a group of satellites working together in a coordinated manner to provide global or regional coverage for communication, navigation, or earth observation.

我想我这辈子都不会忘记Constellation的含义了……

- OS   
这个比较清楚!！我见过这个词！（也确实非常非常基础的一个术语）
我写了 属于 system app ,然后分为 user interface & kernel  ，功能上 有一些最基础的功能（e.g. retrieve files ）, respond to user's request to execute programs, and provide environment to the programs 
generally, coordinate the computer's activities and resources for the benefit of the programs running on it  
> 实际答案
	system software that manages computer hardware and software resources and provides common services for computer programs.

###### 算法 

题目：
```
init m=4 
init v = 1 
for i = 1 to i <= m 
v = v * i
display the value of v
```

和术语一样，也是一眼看下来以为：稳啦！

结果，题目确实很简单，但是最后一问分析时间复杂度，难住了我。

考场上，我一开始的想法，就是O(N)嘛！不过这也太简单了吧？？？

不可能这么简单！主要是 v * i 这一步，耗时应该会随着数字的增大而越来越久才对！

然而我并不清楚计算机实际上是如何处理正整数的乘法的。

于是我进行了简单的假设： 把v * i 拆成 i个v相加！然后加法可以视作耗时不变！

最后得到复杂度是o(N²) 🥳

考场上觉得蛮有道理的？等我回去和gpt一讨论：尴尬了……

原来计算机实际采用的算法这么复杂精妙的吗？
> 有好几种算法，针对不同的情况，反正比我天真的想法复杂多了哈哈哈（佩服设计算法的人的奇思妙想）  
因为公式不好打，这里就不贴了。但是建议去查一查，真的蛮有意思的


最后一边哀嚎自己的笔试之惨淡，一边接受GPT的谆谆教诲……



#### 8.20 英语ITP 

感觉像是砍掉写作和口语，然后听力、阅读统统弱化版的托福IBT。
年初才考了托福机考，所以这里没做太多准备，只提前感受了一下题目难度，然后前一晚来了一套题目模拟。 

但是也不能过于掉以轻心，否则容易在阴沟里翻船：比如我怎么也想不到，自己涂答题卡就花了将近5min！！！（所以最好每写一题就涂好一题，别学我攒到最后😭）害得我都没时间检查了……



#### 8.24 面试 

8.22下午，在网站上看到了自己的编号。

我并不因为自己的入围而吃惊，但是却被总人数吓了一跳！

根据前辈的经验贴，往年都是笔试筛掉10-20人（哪怕是140+人的大年，也有110+的人进了笔试），然后面试再狠筛一波。

但没想到今年只有72人（122人报名）进了面试……

得亏我英语和基础都答得不错……如果都像专门一样拉跨，我就提前说再见了……

然后就是紧张又刺激的准备环节哈哈哈……现在想想还是有点虚弱〒▽〒

最后所有担心的事情都没有出现（什么掉线啊，声音听不清啊）

有趣的是，即使我提前一小时就坐在了电脑前，但是最后还是差点迟到（指要求提前十分钟进场等待，我实际只提前了8分钟，惊险……）

以及一开始的时候，没看到一志愿老师在哪里(っ °Д °;)っ

我还以为一志愿老师没来！内心已经在开始哀嚎了……直到老师开麦，才发现自己眼神不好……

最后，很感谢几位提问的老师，都没有问太多刁钻的问题（如果是

我理解错了问题的话就尴尬了……），也没有遭受什么传说中的压力面试的拷打哈哈哈，还算是比较顺利？（希望我的口语能够让人听清楚😭）

稍微有些遗憾的是，感觉因为紧张，声音在抖，疯狂眨眼……以及绝大部分准备的问题都没有用上🤣

下面就是等待26号放榜了，心里实在没数啊！

但是事已至此，我已尽力！剩下的就交给概率吧！

> 以及等待的时间太过难熬，所以决定写本文抒发一下紧张的情绪！
> 以及希望看到的小伙伴不要模仿我单冲！只报一个项目的话，太刺激了，对心脏不好……



