# Git & Github 资料整理


适用人群:任何职业


## 为什么要学习Git?

假如你写了一篇文章，要删除某一个段落，为了防止以后需要找回这个段落，你需要为这个文件备份。  
如果你第一次删除了段落1，第二次修改了段落2，第三次添加了段落4，则需要为每一个版本都建立一个备份。（还有一个办法是注释掉修改的代码，在下面写添加的代码，但是时间久了就弄不清楚了）你的文件可能看上去是这个样子：


![opensuse-laptop](https://www.liaoxuefeng.com/files/attachments/918921393733152/0)


版本多了，你想恢复修改前的段落2，却不记得是那个备份，所以你需要一个一个文件去翻阅查找，非常麻烦.
这时你迫切需要一个帮你记录每次文档变化的工具,并且在你需要找回的时候能随时切换到以前的版本.


**Git是什么？**  
> Git是目前世界上最先进的分布式版本控制系统。
 

**那什么是版本控制系统？**  
版本控制可以记录每次修改的文件及文件内容改动，就像下面这个样子。当你想要查看某次改动，只需要看看每次修改的备注。

| 版本 | 文件名 | 用户 |修改的备注说明 | 日期时间 |
|-|-|-|-|-|
|1|论文.doc|学生|初步完成整篇论文|2019.7.2 10:55|
|2|论文.doc|老师1|删除啰嗦的部分|2019.7.2 12:31|
|3|论文.doc|学生|修改整篇文章用词不当的地方|2019.7.2 15:21|
|4|论文.doc|老师2|增加文章出版的必要格式和信息|2019.7.3 18:17|

现在假设第4个版本有问题(Bug),你可以随时使用Git回滚至之前的版本，这样就不用再手动管理文件的版本了，这就是版本控制带来的好处。  
当然这只是Git最基本的功能,更多的功能需要你深入的了解.
 
 
## Git和GitHub的区别
**Git**是*版本控制工具*,**GitHub**是一个Git*托管服务*(你的代码存储库).  
我们使用Git来**记录版本信息、控制版本、协同工作等**  
我们使用GitHub来**存放我们的代码(数据)、发现好的代码、~同性交友~等**
 
 
## 官网
- [Git 官网](https://git-scm.com/)
- [GitHub 官网](https://github.com)
 
 

## 学习资料
- [廖雪峰的Git教程(推荐阅读)](https://www.liaoxuefeng.com/wiki/896043488029600/896067008724000)
- [GitHub帮助页面](https://help.github.com/cn)
- [Git备忘清单](https://github.github.com/training-kit/downloads/zh_CN/github-git-cheat-sheet/)
- [MarkDown文件的基本撰写格式和语法](https://help.github.com/cn/articles/basic-writing-and-formatting-syntax)
 
 
## 视野拓展 & 指南
- [为什么要用新手要学会用Git来管理自己的代码](https://blog.csdn.net/qq_42403562/article/details/80991716)
- [开源指南](https://opensource.guide/zh-cn/)


## 明星项目
- [Spring源码](https://github.com/spring-projects/spring-framework)
- [Docker源码](https://github.com/moby/moby)
 
 
## 清单进度
- [x] 创建清单
- [x] 初始化学习资料
- [ ] 进阶拓展
- [ ] 联动
- [ ] 多语言
 
 
## 贡献 & 纠错
**任何人都可以向本页面贡献内容,如有问题请至issues板块提出**
