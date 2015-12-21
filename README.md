# -Future-visions-in-Chinese
前不久微软邀请了 9 位世界顶级科幻小说家参观了微软在全球各地的研究院。这些作家们从微软研究院超过 55个研究方向中选择了各自想要探索的领域，如量子计算、预测分析、机器学习、人工智能、虚拟传送以及与情感计算等，与研究员面对面深入交流。
最终他们从微软研究院的科研项目中汲取灵感和启发，创作了一本长达 239 页的科幻小说集《FutureVisions》。
[Future Visions英文版](http://news.microsoft.com/futurevisions/?from=singlemessage&isappinstalled=0)

如果想帮忙翻译或者校对，请加QQ群：145817834 ，谢谢！

#当前阶段
#1.0译者记录 (没有名字的就是还没有认领的)
###第一章 前言
###第二章 简介
###第三章 hello,hello by Seanan McGuire
###第四章 The Machine Starts by Greg Bear
###第五章 Skin in the Game by Elizabeth Bear
###第六章 Machine Learning by Nancy Kress
###第七章 Riding With the Duke by Jack McDevitt
###第八章 A cop's Eye by Blue Delliquanti& Michele Rosenthal
###第九章 Looking For Gordo by Robert J.Sawyer
###第十章 The Tell by David Brin
###第十一章 Another word for word by Ann Leckie

#贡献力量
如果想做出贡献的话，你可以：

* 帮忙校对，挑错别字、病句等等
* 提出修改建议
* 提出术语翻译建议

#翻译建议
1. 整书共11章节：介绍2个章节，主要内容9个章节。总单词数是71552，大概翻译后的中文字数是13万字。
2. 如果你愿意一起校对的话，请仔细阅读：
* 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
* 翻译后的文档请放到source文件夹下的对应章节中，然后pull request即可，我会用gitbook编译成网页
* 工作分支为gh-pages，用于GitHub的pages服务
* fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到gh-pages分支中
* 有其他任何问题都欢迎发issue，我看到了会尽快回复
谢谢！
#关于术语
翻译术语的时候请参考这个流程：
* 尽量保证和已翻译的内容一致
* 尽量先搜索，一般来说大部分术语是一样的，
* 如果以上两条都没有找到合适的结果，请自己决定一个合适的翻译或者直接使用英文原文，后期校对的时候会进行统一

#参考流程
有些朋友可能不太清楚如何帮忙翻译，我这里写一个简单的流程，大家可以参考一下：
###方案一
1. 首先fork我的项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 在命令行运行 git branch develop 来创建一个新分支
4. 运行 git checkout develop 来切换到新分支
5. 运行 git remote add upstream https://github.com/nicolechow/-Future-visions-in-Chinese.git 把我的库添加为远端库
6. 运行 git remote update更新
7. 运行 git fetch upstream gh-pages 拉取我的库的更新到本地
8. 运行 git rebase upstream/gh-pages 将我的更新合并到你的分支
9. 这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。
10. 如果修改过程中我的库有了更新，请重复6、7、8步。
11. 修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 pull request 按钮，点击它，填写一些说明信息，然后提交即可。

###方案二

翻译工具： [TitanPad](https://titanpad.com/)

我们的翻译是大家一起同时进行，使用的工具叫做 TitanPad。这是一个网站，无需注册，可以多人在线，同时工作，大家能够看到彼此的进展，相互帮助，聊天，勾搭，等等。点击链接后，直接就可以加入的，很很很简单的

协作翻译流程：

简单地讲，协作分为初稿、校对、终稿、统稿。 
进行两轮校对，也可以根据具体时间和精力做相应的调整，比如时间多的可以再加几轮；
每次校对后紧接着是译者对自己翻译部分的修改，要注意与校对及时沟通；最后是对全文的统稿，是集体活动。 从头到尾完整地做完一期协作的同学，将加入协作名单，记为一次。
因此，自组队之初起，每位同学都要求对全文负责。同时，负责人要做好组织协调工作。

1. 确定负责人，负责人负责招募译者、制定时间表、给文章分段、分配任务、全程跟进、整理发文。首先，负责人新建协作页面注意保存好页面地址，分享给协作小伙伴。其次，分配任务，按流程完成协作。 附. [说明 | 一起来认识下TitanPad协作编辑器吧](http://article.yeeyan.org/view/199302/390523)

2.初稿：译者各自完成自己认领的部分，一定要自校；格式，一段原文对应一段译文，译文前加【初稿】，过短的段落可合译，格式与原文同。

3. 一校：轮流校对，译者一校对part 2，译者二校对part 3，以此类推；注意，一校在初稿上进行，校对意见请加【】，不要直接改动初稿。
4. 二稿：译者根据校对意见修改自己的初稿；遇到问题及时沟通；格式，在初稿上方另起一段，前面加【二稿】。
5. 二校：轮流校对，译者一校对part 3，译者二校对part 4，以此类推；注意，二校在二稿上进行，校对意见请加【】，不要直接改动二稿。
6. 终稿：译者根据校对意见修改自己的二稿；遇到问题及时沟通；格式，在二稿上方另起一段，前面加【终稿】。
7. 讨论： q 群或微信群
8. 发文：负责人（或指定代表）整理发文；格式，标题前加【协作】，标签中加 协作，文末注明各译者id并加译者个人页面链接。

注意： 负责人任务，协调组织、整理统词表及译注、发文或指定代表发文、负责人可兼任译者； 译者在完成前一步后，请及时通知下一步的译者，如果联系不上，可以联系负责人；认领的任务请按时认真完成，如临时有事，要及时通知负责人！
