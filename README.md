# Markdown
  
  
# 概述
## 编写目的 
啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊
## 团队
不不不不不不不不不不不不不不不不不不不不不不不不不不不不不不不不不不
# 项目前景与范围
## 项目范围
**客户端**  
不不不  
啊啊啊  
  
**服务器**  
啊啊啊  
bbb  
# 需求描述
## 需求分析
![md](http://pic6.huitu.com/res/20130116/84481_20130116142820494200_1.jpg)
# 功能性需求
1. 用户输入账号与密码
2. 点击登陆
2. login in
  
- 用户输入账号与密码
- 点击登陆
- login in
  
+ 用户输入账号与密码
+ 点击登陆
+ login in
  
  
  
  
 
### 斜体
我不是斜体  
*我是斜体*
  
  
  
### 链接
<http://www.baidu.com>
  
  
[百度首页](http://www.baidu.com)
  
  
  
### 表格
版本|修改内容|修改时间
----|---|---
v0.1| 需求描述|2017.5.6
v0.1| 需求描述|2017.5.6
v0.1| 需求描述|2017.5.6
v0.1| 需求描述|2017.5.6
  
  
  
### TaskList
- [ ] 需求分析
- [ ] 一定注意空格
- [x] 换行用两个空格
  
  
  
### 代码块
```java
package hello-world

import static java.lang.System.*;

public class HelloWorld{

static
{
    out.println("Hello World!");
    exit(0);
}

}
```
  
  
```html
<body>
    <div id="aa">
        hehe
    </div>
    <img src="aaaaaaaaa" class="pic"/>
</body>
```
  
  
  
### 引用
> 德媒称，在台裔美国海军少校林介良承认部分罪名后，美国海军撤回了对他的间谍指控。林介良5月4日在法庭上承认撒谎和泄密，但他声称，自己所为只是因为傲慢和为了赢得女性的好感。
>> 据德国之声电台网站5月5日报道，现役美国海军少校林介良（Edward C. Lin）涉嫌军事间谍案在5月4日开始了审理。林介良被指向外国出卖美国国防机密情报、没有诚实汇报同外国机构的关系等。
>>> 不过在庭审前，检方与被告达成了辩诉交易（美国一项司法制度，指在开庭审理前双方协商，达成双方均可接受的协议，可以被通俗看作“认罪讨价还价”）。达成认罪协议后，美国海军撤回了对林的间谍指控。

  
  
  
### 流程图
```
graph LR
S[开始]-->A
A[用户管理]-->B{是否注册}
B-->|是|B1(输入用户名密码)
B-->|否|B2(注册)
B1-->C[登陆]
C-->D[完善个人信息]
B2-->E[注册完成]
E-->B
D-->END[完成]
```
![md](https://github.com/jacket12356/Markdown/blob/master/a/1.png)  
**看样子是github并不支持流程图和甘特图**  
  
  
### 甘特图
```
gantt
title 任务计划表
dateformat YYYY-MM-DD
section 前期
需求分析:2016-11-11,8d
section 中期
编码开发:2016-11-19,15d
section 后期
系统测试:2016-11-26,26d
```
![md](https://github.com/jacket12356/Markdown/blob/master/a/2.png) 
