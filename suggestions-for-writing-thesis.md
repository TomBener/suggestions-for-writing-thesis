# 写毕业论文的几点建议

> 作者：[任涛](https://tomben.me)
>
> 邮箱：me@tomben.me
>
> 版本：1.1
>
> 最近更新：2019 年 10 月 7 日

---

**目录**

[TOC]

## 写在前面

没有一点点防备，毕业论文就这样来了。

几个月前，我本来打算写一个本科毕业论文的 LaTeX 模板，然而由于时间原因和自身水平问题，一直没有完成。于是我就放弃写 LaTeX 模板了，毕竟 LaTeX 受众那么小，写了估计也就我自己用。但是我总得写点什么吧？于是就有了此文。

需要注意的是，本文不是给你关于毕业论文内容写作的建议，不涉及如何写摘要、写文献综述、写结论等问题，而是关于如何「写」论文的建议，换句话说，就是写论文过程中，除文章内容之外，你应该关心的其他问题。

虽然本文是以毕业论文为写作目标，但我认为其对于一般性的学术论文写作也具有借鉴意义。此外，文中用到的所有工具运行系统为 macOS，可能在 Windows 平台的部分操作有所不同，但应该不会有太大的差异。当然，由于个人见识的局限性以及时间的仓促性，错误与疏漏在所难免。如果你有任何建议或问题，欢迎评论，欢迎交流。此文会持续更新，最新的版本可以在 [这里](https://dsc.cloud/TomBen/suggestions-for-writing-thesis.html) 查看。


## 一定要使用 Word 样式

Word 很好上手，这应该是接触过 Word 的人都会承认的，但有一句话大家应该也有所耳闻：HR 绝对不会相信你在简历上写的**精通 Word (Office)**。我们真的会使用 Microsoft Word 吗？恐怕很多人并不会吧，更别说精通了。

我现在还清晰地记得，一些同学上课或者听讲座的场景：背上自己沉重的电脑，早早来到教室，坐在前排，电脑开机，打开 Microsoft Word 或者 WPS Office，做好了一切做笔记的准备，然后从口袋里掏出手机开始玩。台上的老师讲得眉飞色舞，台下的同学键盘敲得毫不停歇，将老师讲的内容记在 Word 里面。一节课下来，老师口干舌燥，同学手指酸痛，Word 里密密麻麻，然而点击 Word 文件中的样式窗格，全是「正文」，完全没有结构可言。

可能你说我把字号设置为三号字，字体加粗，前后各空一行，居中对齐...... 就是一级标题了。但是这是你觉得的标题，并不是 Word 觉得的标题，如果 Word 像黄晓明一样霸道，它一定会要用那句经典「明学」语录驳斥你：我不要你觉得，我要我觉得。

![](https://i.loli.net/2019/10/04/ROnKxp1L2EHm9vX.gif)

让我们来看看各大文字处理软件的简介：

- [Microsoft Word](https://products.office.com/en-us/word) —— Use Microsoft Word for the best word processing and document creation.
- [Google Docs](https://docs.google.com) —— A word processor included as part of a free, online software office suite.
- [Apple Pages](https://www.apple.com/pages/) —— Create and collaborate on documents that are beautiful beyond words.
- [OpenOffice Writer](http://www.openoffice.org) —— The leading open-source office software suite for word processing.
- [LibreOffice Writer](https://www.libreoffice.org) —— With all features you need from a modern, full-featured word processing and desktop publishing tool.
- [WPS Office](https://www.wps.com) —— Complete office suite with better templates.

不难看出，几乎每个文字处理软件都在强调自己的办公（Office）属性，这与 Kieran Healy 提出的 [The Office Model & The Engineering Model](http://plain-text.co) 有异曲同工之处：Word 这类文字处理软件不是为学术而生，而是为办公而生。学术文章往往具有很强的逻辑和一定的结构，Word 诞生之初并不能满足这种需求，好在 Word 2003 开始新增加了样式（Style）功能，能够在一定程度上胜任这项工作。

Word 这类「所见即所得 ([WYSIWG](https://en.wikipedia.org/wiki/WYSIWYG))」的编辑工具经常被拿来和以 LaTeX 为代表的「所想即所得 ([WYWIWYG](https://blogs.sap.com/2007/04/04/wywiwg-what-you-want-is-what-you-get/))」编辑工具相比较。这里我们可以来比较一下二者对于文章结构强调程度的不同。不论什么样的 LaTeX 入门资料，都一定会在入门阶段讲到 `\section`、`\subsection`和`\subsubsection`，分别对应文章中的一级标题、二级标题和三级标题，当然在标准 report 或者 book 文档类中还有 `\chapter`，可见 LaTeX 从一开始就非常强调文档结构。相比较而言，Word 就不太重视了，大多数人打开 Word 就是直接开始写，所有的内容都是「正文」。

不过 Word 上方样式菜单栏所占空间并不小，用过 Word 的人应该都见过这一部分，只是微软并没有把它做得那么显眼或者必不可少。

![](https://i.loli.net/2019/10/05/IaGFvwyhgc9niWR.png)



### 修改默认样式

Word 默认的样式不太友好，与我们日常习惯的用法不同，为了满足毕业论文的要求，需要进行修改。方法很简单：鼠标移到需要修改的样式上，比如上图中的标题 1，右键选择 `修改（M）...` ，弹出如下窗口，可以在其中修改关于标题 1 的所有样式。

![](https://i.loli.net/2019/10/05/HIRErwJqPYLScvF.png)

修改样式的步骤，也可以参考这篇 [微软官方说明](https://support.office.com/zh-cn/article/自定义或在-word-中创建新样式-d38d6e47-f6fc-48eb-a607-1eb120dec563)。关于如何实现标题自动编号，即一、二、三级标题编号类似于 1、1.1、1.1.1 这种形式，可以阅读 [这篇文章](https://zhuanlan.zhihu.com/p/22737822)。

按照 [四川大学本科毕业论文（设计）格式和参考文献著录要求](http://jwc.scu.edu.cn/detail/183/6321.htm)，以修改一级标题为例，进行下列修改：

1. 字号为小 3 号字，字体选用标宋黑体；
2. 文字上下各空一行，居中排；
3. 目录中一级标题用小 3～4 号字。

此外，图表标题也可以用样式来添加，不要手动添加，如果手动的话，老师或者学院突然要求加插图目录和表格目录，不就傻眼了？靠谱的方法是使用「题注」功能为图片和表格添加标题，并且可以实现自动编号。「题注」的样式也是可以在样式窗格中修改的。运用了样式之后，加个目录什么的简直就是 so easy ～

![](https://i.loli.net/2019/10/05/uLxTE3IBJHvRa5Z.png)

使用 Word 写作长篇论文时，建议你始终打开左侧的「导航栏」和右侧的「样式窗格」，这样可以清楚地了解文章结构和当前进行操作的区域，有一种统领全局、运筹帷幄的感觉。

![](https://i.loli.net/2019/10/05/jcPAguJowMEzZ95.png)

上述的操作我是一边在 Word 中设置，一边截图并记录下来。写到这里，我真心觉得 Word 不应该被用来写毕业论文，还是去用我的 LaTeX 吧。然而，绝大多数同学一定会选择 Word 来完成毕业论文，并且四川大学教务处文件中，正文第一句就是「用微软 Word 软件排式」…… 此刻，Kieran Healy 的这句话引起了我的强烈共鸣：

> Very often, because of some unavoidable facts about the world, the final output of this kind of solution is also a `.docx` file.

既然是「这个世界不可避免的事实」，那就再推荐两篇关于用 Word 排版毕业论文的文章吧，希望对你有所帮助：

- [当代大学生难题：又又又又要排版论文了](https://mp.weixin.qq.com/s/iwcbhv75o6RnWAPZpV9U_A)
- [毕业论文一次过！这份最全攻略，帮你轻松搞定排版](https://mp.weixin.qq.com/s/Fpya9Y6WZFs9bTDQFQjJWg)

## 千万要做好版本控制

按照惯例，首先来进行名词解释，这是第 1 道：请解释版本控制是什么？（10 分）

[Git 网站](https://git-scm.com) 的回答（9 分）：

> 版本控制是一种记录一个或若干文件内容变化，以便将来查阅特定版本修订情况的系统。
>
> ---
>
> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

简单粗暴的回答（8 分）：

>版本控制是一个记录文件的更改过程，便于创建分支进行更改、回到文件历史版本、进行协作等功能的系统。
>
>当你由于误操作，修改了某个文件中的内容，而想要撤销却不能做到的时候，当你的电脑丢失或出现故障，想要恢复其中的重要数据的时候，当你想要和别人合作完成项目进行文稿合并的时候…… 你就会体会到版本控制是多么重要。

如果你曾经有过下图这样的经历或者预见自己可能会这样👇，那么你就需要版本控制。

![](https://i.loli.net/2019/10/06/HkE8be5SvlmAZuh.jpg)

从版本控制的定义来看，它也有备份文件的功能，并且是全方位的备份。这学期刚开学，我偶然在 QQ 空间看见一位同学电脑中病毒文件全部消失的遭遇，如果他当初备份过自己电脑中的文件，不至于面临如此惨痛的后果，真是太遗憾了。

![](https://i.loli.net/2019/10/04/R93TC5Kbr2ixEIq.jpg)

那么如何进行版本控制呢？这里介绍两类工具，一是 Git —— 全能型选手，主要用于纯文本文件的版本控制；另一类是网盘工具 —— Dropbox 和坚果云，用于 Word 文件等二进制文件的版本控制。因此，如果你用纯文本`.tex`、`.md`、`.Rmd` 等写论文，那么一定要使用 Git，如果你用 Word 写论文，推荐你使用 Dropbox 或坚果云进行版本控制。

### Git

####  Git 是什么

第 2 道名词解释题目：请解释 Git 是什么？（10 分）

[Wikipedia](https://en.wikipedia.org/wiki/Git) 的回答（9 分）：

> Git is a distributed version-control system for tracking changes in source code during software development.
>
> ---
>
> Git 是一个在软件开发过程中记录源代码变化的分布式版本控制软件。读作 /ɡɪt/，点击 [听 Git 发音](http://t.cn/Aim8qBqw)。

Git 由美籍芬兰裔开发者林纳斯·托瓦兹（Linus Benedict Torvalds）开发，林纳斯·托瓦兹是当今世界最著名的计算机程序员和黑客之一，也是 Linux 内核的最早作者，担任 Linux 内核的首要架构师与项目协调者。Git 最初的目的是为了更好地管理 Linux 内核开发，随着时间的流逝，现如今 Git 已成为全世界最流行、最先进的版本控制系统，全球最大的代码托管网站 [GitHub](https://github.com) 就是一个利用 Git 进行版本控制的软件源代码托管服务平台。

![](https://i.loli.net/2019/10/04/WBwIeoQxRn7CuDm.png)



Git 的工作原理如下图所示。你将文件保存在存储库中，存储库可以在本地，也可以在远程服务器上。在你工作时，你会定期暂存你的更改，然后将它们提交到存储库，并附上一些关于你所做的改变的说明。你或者其他人可以复制、克隆、合并和贡献存储库。

![](https://i.loli.net/2019/10/04/2XgIbFD3QYGtv8w.png)

#### 如何使用 Git

要使用 Git，首先需要在你的电脑上安装 Git，到 Git 官网上选择对应的操作系统 [下载 Git](https://git-scm.com/downloads) 即可。如果你的操作系统是 macOS，推荐你使用 [Homebrew](https://brew.sh) 来安装 Git，只需 2 行命令：

1. 安装 Homebrew：

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

2. 安装 Git：

```sh
brew install git
```

Git 本身是一个命令行工具，通过命令进行一些操作，基本的几个命令如下：

```sh
# 把大象放进冰箱
$ git init  # 在当前目录新建一个 Git 代码库
$ git add  # 添加指定目录到暂存区
$ git commit  # 提交暂存区到仓库区

# 时空穿梭
$ git reset  # 重置暂存区的指定文件，与上一次 commit 保持一致，但工作区不变
$ git revert  # 新建一个 commit，用来撤销指定 commit，后者的所有变化都将被前者抵消，并且应用到当前分支

# 平行宇宙
$ git branch  # 列出所有本地分支
$ git checkout  # 切换到分支
```

我只用过其中的几个命令，因为其他的很多命令我记不住 😂。要掌握好 Git 的操作还是不容易的，毕竟它有很多命令，不亚于一门编程语言的入门级语法。一些常用的 Git 命令，可以查看 GitHub 的这个 [GIT CHEAT SHEET](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)。

可能正是由于 Git 命令太多记不住，有很多图形化软件（GUI, Graphical User Interface）供我们选择，来可视化 Git 操作。你可以在 [这个页面](https://git-scm.com/downloads/guis) 查看各个操作系统的 Git 图形化应用。我在 macOS 上使用 [GitHub Desktop](https://desktop.github.com) 和 [VS Code](https://code.visualstudio.com)，iOS & iPadOS 上（很少）使用 [Working Copy](https://workingcopyapp.com)，推荐在 Windows 上使用 GitHub Desktop 或 [SourceTree](https://www.sourcetreeapp.com)。

**下面我来演示 GitHub Desktop 的操作。**

将文件 `suggestions-for-writing-thesis.md` 及其附属图片放在同一个文件夹里，命名为 `test`，文件夹结构如下：

```sh
test
├── suggestions-for-writing-thesis.md  # 主文档
├── images   # 图片所在文件夹
│   ├── image 1
│   ├── image 2
│   ├── ......
```

将文件夹 `test` 用 GitHub Desktop 打开（没错，打开**文件夹**），然后 GitHub Desktop 会自动检测到这个文件夹不是一个 Git 文件夹，询问你是否需要创建一个新的 Git 仓库（Repository），得到你的肯定回复后，GitHub Desktop 会弹出一个窗口，设置创建新仓库的相关信息，如下图所示。

![](https://i.loli.net/2019/10/05/LbmXSGkdYT4cjw1.png)

Git 仓库创建完成后，点击左上角的 `History`，可以看到一个 `Initial commit`，即首次提交，这是在刚刚创建 Git 仓库时完成的。每一个文件的右边都有一个绿色的加号，表明首次提交添加了 `tset` 文件夹里的所有文件。接下来 `test` 文件夹里任何文件的变化都在 Git 的掌控之下。

![](https://i.loli.net/2019/10/05/T78HwSMzJoKsmnt.png)

然后你可以关闭 GitHub Desktop，接着来修改 `test`文件夹里的文件。修改完成之后，再次打开 GitHub Desktop，你就会看到 Git 记录下了你的修改过程：绿色表示增加的内容，红色表示减少的内容。

![](https://i.loli.net/2019/10/05/XpnOxcdlz9YD8Cj.png)

如果你觉得上图 GitHub Desktop 这种样子不太直观的话，不妨试试用「宇宙最强 IDE」VS Code 打开 `test` 文件夹试试，我觉得这种左右对照的方式看起来更直观。

![](https://i.loli.net/2019/10/05/bXevcyNljAtHCmg.png)

点击 GitHub Desktop 左下角的 `Commit to master`，就完成了本次提交。之后 GitHub Desktop 会提示你将仓库推送到远程服务器上，也就是推送到你的 GitHub 账号去。这一步需要在 GitHub Desktop 中登录你的 GitHub 账号，可前往 [GitHub 主页](https://github.com/join) 免费注册一个 GitHub 账号。

![](https://i.loli.net/2019/10/05/NDMjZCQm4iLa6oV.png)

推送到远程仓库后，你就在 GitHub 服务器上有了一份本地文件的副本，如下图所示。以后每次的修改都提交到远程，这是一个好习惯。你的每次修改，Git 都忠实地记录了下来，方便你回退到之前的任意一个版本。万一你的电脑出现故障或者换了一台电脑，可以从远程服务器拉取文件到本地，为文件安全增加了一道保护锁。如果你不想别人看见你的远程仓库内的内容，你可以将仓库设置为私人仓库 (Private)（微软收购 GitHub 后，免费用户可以创建不限数量的私人仓库。）

![](https://i.loli.net/2019/10/05/sBTVGhMbLQ1Kcjv.png)

### 网盘

Git 虽然很强大，但它主要是针对纯文本文件进行版本控制，遇到二进制文件，它的表现就不尽如人意了。而绝大多数同学是用 Word 写毕业论文的，面对 `.docx` 这种二进制文件，使用 Git 进行版本控制有一种高射炮打蚊子—— 大材小用的感觉。

![](https://i.loli.net/2019/10/06/h9DnGwLjRMxBqIY.png)

因此，网盘或者云盘的版本控制功能（在网盘中叫做「历史记录」）就派上用场了，这足以应付毕业论文的写作。下面介绍两个网盘 —— Dropbox 和坚果云，分别是墙外和墙内的网盘代表。

#### Dropbox

程序员之间有很多 [鄙视链](https://mp.weixin.qq.com/s/xdHLZIQGVT5fQzjfazGP_g)，其中关于版本控制的鄙视链是这样的：

> 用 Git 或 Mercurial 的工程师鄙视用 Subversion 的工程师，用 Subversion 的工程师鄙视用 Dropbox 来做版本控制的工程师，用 Dropbox 来做版本控制的工程师鄙视根本不知道什么叫做版本控制的工程师。

很显然，上述言语流露出对用 Dropbox 做版本控制的不屑。然而，Dropbox 作为鄙视链上唯一一个网盘，足以看出其在网盘界的地位。在网盘界，如果 Dropbox 说自己是老二，绝对没有网盘敢称自己是老大，国内国外皆是如此。由于众所周知的原因，Dropbox 在中国大陆无法正常使用，需要一些特殊的手段才行。如果你能解决科学上网问题，我强烈推荐你试一试 Dropbox。

[注册 Dropbox](https://db.tt/FmhniEsrCa) 后会自动获得 2GB 空间，通过完成任务或邀请好友可扩大空间至 20GB 左右，存储常用文件基本足够了。Dropbox 存储文件历史版本的时间长度取决于账号的套餐：

- Basic（免费）：30 天
- Plus：30 天
- Business（Standard、Advanced、Enterprise 或 Education）：120 天
- Professional：180 天

在 Dropbox 中查看文件的历史版本：

1. 打开并登录 [Dropbox](https://www.dropbox.com/)
2. 单击你想要查看其历史版本的文件
3. 右键选择 `版本历史记录`


![](https://i.loli.net/2019/07/20/5d330871b937f55538.png)

4. 选择某个版本进行预览
5. 要恢复旧版本，单击最右边的 `恢复` 按钮

注意：如果在离线状态下或在 Dropbox 以外的地方编辑文件，系统不会更新版本历史记录。

![](https://i.loli.net/2019/07/20/5d3307d8c07ba47300.png)



假设你的 `my-thesis.docx` 文件存储在 Dropbox 文件夹中，并且 Dropbox 处于打开状态，那么当你用 Word 打开 `my-thesis.docx` 时，Word 窗口右侧会出现一个「Dropbox 标记」，可以很方便地共享、评论或查看版本历史记录。

![](https://i.loli.net/2019/10/06/dPnu98pJhMSzeNL.png)



#### 坚果云

[坚果云](https://www.jianguoyun.com) 和 Dropbox 很类似，优点在于这是一个国内的云盘服务，不需要特殊的网络就可正常使用。安装好坚果云并登录之后，在坚果云同步的文件夹里右击文件，可以看到一个 `查看文件历史` 的选项。

![](https://i.loli.net/2019/07/20/5d3309b5866a242476.png)



点击之后，会在新窗口看见最近的修改历史（坚果云个人免费版用户可以保存一个月的文件历史版本）。

![](https://i.loli.net/2019/07/20/5d330a5e9ed4c61684.png)

点击左下角的 `查看更多` 会跳转至网页版查看更多的历史记录，可以选择 `恢复` 或 `下载` 文件的历史版本。

![](https://i.loli.net/2019/07/21/5d33d8b63517d16452.png)

总结一下版本控制这部分：

- 纯文本写论文，用 Git 做版本控制
- Word 写论文，能够科学上网，用 Dropbox 做版本控制
- Word 写论文，不能科学上网，用坚果云做版本控制
- 不想做版本控制，只想存一个备份，以上工具任选皆可
- 不想写论文…… 请出门右拐

![](https://i.loli.net/2019/10/06/JbTMlf1E3F8Kznq.jpg)

## 最好实现参考文献自动化

写论文参考文献必不可少，毕业论文当然也不例外，很多童鞋写论文过程中最为头痛的部分可能就是参考文献了。这里我介绍两种实现参考文献自动化的方法，方法一是 EndNote 和 Word 的结合，方法二是在 LaTeX 中使用 BibTeX 生成参考文献，当然你任选其一，都能达到简化我们工作的目的，正如 Kieran Healy 所说：

> Make your computer work for you by automating as many of these steps as you can.

有了以上两种实现参考文献自动化方法的加持，你再也不用一遍又一遍地复制和粘贴参考文献了，若是文献前后顺序发生了改变，也不再需要一个一个手动调整。

### EndNote

[EndNote](https://endnote.com) 是一款知名的文献管理软件，由科睿唯安（Clarivate Analytics，著名的科学引文索引 SCI (Science Citation Index) 和社会科学引文索引 SSCI (Social Science Citation Index) 就是其下品牌。）开发，至今已有二十余年历史，在学术界具有较高的普及度。实际上，文献管理软件多如牛毛，叫得出名字的就有 [Papers](https://www.papersapp.com)、[Mendeley](https://www.mendeley.com)、[Zotero](https://www.zotero.org)、[Citavi](https://www.citavi.com/en)、[NoteExpress](http://www.inoteexpress.com/aegean/) 等等，为什么这里我只介绍 EndNote 呢？因为：

1. EndNote 最为著名，通用性较强，网上教程很多。
2. 与 Microsoft Word 结合，EndNote 算是比较不错的（EndNote 甚至可以与 [Apple Pages](https://support.apple.com/kb/DL1916?locale=zh_CN) 结合使用）。
3. 部分高校图书馆购买了 EndNote，在校师生可以免费使用。

截至 2019 年 10 月 6 日，EndNote 的最新版本为 `X9.2`，官网售价 249.95 美元（约合人民币 1786.54 元），即使学生享受 5 折优惠购买，售价也将近 900 元人民币。不过幸运的是，很多高校图书馆似乎体贴到了我们的贫穷，购买了机构版 EndNote 供在校师生免费使用，比如 [北京大学图书馆](https://www.lib.pku.edu.cn/portal/cn/zy/dzzy/gjrj/endnote)、[中国科学技术大学图书馆](http://lib.ustc.edu.cn/电子资源/database/9-工具软件/[新增]endnote-x7-文献管理软件/#)、[中山大学图书馆](http://lzcxdj.com/article/599) 和 [四川大学图书馆](http://202.115.54.22/resourcenov/resourcedetail/SCU04595)。

![](https://i.loli.net/2019/10/06/7D3nhJbjdCksFTH.png)

以后当别人问你，你的 EndNote 破解版在哪儿下载的时候，你可以骄傲地对他/她说：**我用的是正版 EndNote！用正版，我骄傲！**然后手把手教他/她怎么在图书馆网站下载和安装 EndNote。

再补充一下，EndNote、NoteExpress、Mendeley 这类文献管理软件大同小异，如果你不喜欢 EndNote，或者因为某些原因无法正常使用 EndNote，尝试使用其他的软件也是完全没有问题的，毕竟有些还是完全免费的，比如 Mendeley、Zotero。

四川大学图书馆在附上 EndNote 下载地址的同时，也贴心地放上了 [EndNote 操作指南](http://202.115.54.39/meta/endnote/win/EndNote_on_Windows.pdf)，如果你不想看这个英文指南，可以看看我的简单使用示例。跟着下面的示例设置一遍，基本就可以无痛解决 Word 论文中的参考文献了。

#### 设置引文样式

下载安装后的 EndNote 自带超过 500 种引文样式，但并不包括一般毕业论文要求的 [GB/T 7714-2015 《信息与文献  参考文献著录规则》](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style/files/153951/GBT.7714-2015.pdf)，即中国的参考文献推荐标准，因此需要自行安装，安装的步骤也比较简单：

1. 下载 [Chinese Std GBT7714 (author-year)](https://endnote.com/style_download/chinese-standard-gb-t7114-author-year/) 和 [Chinese Standard GB/T7714 (numeric)](https://www.endnote.com/style_download/chinese-standard-gb-t7714-numeric/)
2. 双击打开下载的 `.ens` 文件，默认会在 EndNote 中打开
3. 点击 `File -> Save As`，在弹出的窗口点击 `Save`
4. 打开 EndNote，点击 `Edit -> Output Styles -> Open Style Manager`，找到刚刚安装好的两个国标引文样式，在前面的复选框内打上勾 ✓

![](https://i.loli.net/2019/10/04/2Qh8g3Mm9FlAw5X.png)

#### 下载参考文献，导入 EndNote

在 [Google Scholar](https://scholar.google.com)（[百度学术](http://xueshu.baidu.com) 也还凑合）中搜索文献，点击下方的双引号「”」，在弹出的对话框中点击「EndNote」，然后就会下载扩展名为 `.ris` 的 EndNote 引文格式文件，此处命名为 `ref.ris`。

![](https://i.loli.net/2019/10/04/V7mGyESNUg4anPZ.png)



常用中文数据库 [中国知网](https://www.cnki.net)、[万方数据](http://www.wanfangdata.com.cn/index.html)、[维普资讯](http://qikan.cqvip.com) 也都提供 EndNote 引文格式文件的下载，并且支持批量操作。

![](https://i.loli.net/2019/10/04/xYiHJtmqjKF7rT1.png)



容易看出，三大数据库导出的 EndNote 引文格式并不完全一样，特别当导出一些年代久远、数据不全的论文更为明显，需要手动修改引文中的内容。而后文用到的 BibTeX 一般就不存在这样的问题。

国外的数据库在引文方面做得更好，比如 [ScienceDirect](https://www.sciencedirect.com) 数据库可以在每篇论文上方点击「Export」导出需要的引文格式，同样包括 EndNote 的 `.ris` 格式，也支持批量导出。

![](https://i.loli.net/2019/10/04/Jco2lISCw45Hdsy.png)



#### 新建 EndNote 数据库

打开 EndNote，点击上方 `File -> New`，在弹出的对话框（如下图）中命名数据库和更改存储位置。此处命名为 `My EndNote Library`，存储在 `Desktop`。点击 `Save` 之后，桌面上会出现一个文件和一个文件夹，分别是 `My EndNote Library.enl` 和 `My EndNote Library.Data`，这是由 EndNote 自动生成的，写作毕业论文所需的参考文献数据都会保存在里面。

![](https://i.loli.net/2019/10/04/SCGfR5pJ6aEAs83.png)

需要注意的是，你的 Word 论文应该和这些 EndNote 数据保存在同一个文件夹中，不要随意移动，避免由于文件路径改变带来不必要的麻烦。假设你的所有文件都存储在一个命名为 `my-thesis` 的文件夹里，那么这个文件夹的结构大致是这样的：

```sh
my-thesis
├── my-thesis.docx  # 论文主文档
├── My EndNote Library.enl   # 参考文献数据库
├── My EndNote Library.Data  # 参考文献数据存储目录
│   ├── rdb
│   ├── tdb
│   ├── ...  # 其他
├── ...  # 其他文件
```


#### 添加引文数据至 EndNote 数据库

双击前面下载完成的 `ref.ris`，在弹出的窗口中选择 `My EndNote Library.enl`，然后点击 `Open`，就将 `ref.ris` 添加到 EndNote 数据库 `My EndNote Library.enl` 中了，EndNote 中显示的效果如下图所示。

![](https://i.loli.net/2019/10/05/agkEp1UQGL2t5X4.png)

#### 在 Word 中引用文献

下载并安装好 EndNote 后，会自动安装 Word 插件，可以在 Word 上方菜单栏中找到。

![](https://i.loli.net/2019/10/04/FHabuDQvnmPZAe3.png)

前面的准备工作全部完成，下面开始写作，在 Word 中使用 EndNote 引用参考文献。

- 在 EndNote 中选中需要引用的文献（按住 `shift` 键可以同时选择多个）

![](https://i.loli.net/2019/10/04/nwHmO2sLlUYRhQT.png)

- 光标定位到需要插入引用的位置，依次点击 `EndNote X9 -> Insert Citation -> Insert Selected Citation(s) ` ，即可自动完成引用。

![](https://i.loli.net/2019/10/04/hp8avALus9jBZS6.png)

从上图可以看出，鼠标点击参考文献文字部分，文字上会有一层灰色阴影，说明这是 Word 中的宏，不推荐手动进行修改。从窗口右侧的「样式窗格」也可以发现这部分内容是「EndNote Bibliography Title」，而不是「正文」。

需要注意的是，直接下载安装的 `Chinese Standard GB/T7714 (numeric)` 有一些小问题，比如括号只有一半、作者姓名大小写等问题，需要自行修改，上图中的最终效果是我修改后的结果。修改方法如下：依次点击 `Edit -> Output Styles -> Edit "Chinese Std GBT7714 (numeric)"`，在弹出的窗口中（如下图所示），将 Journal Article 修改为如下格式：

```
Author. Title[J]. Journal, Year, Volume|(Issue)|:Pages.
```

![](https://i.loli.net/2019/10/04/j9BCf2M3iObcVTx.png)

因为测试文档里只包含 Journal，没有 Book、Thesis 等其他种类的文献，这里只修改了 Journal，但其他种类的文献格式也可能有问题，可根据需要自行修改。善于利用搜索引擎，总是能修改正确的。

此外，在 Word 中，参考文献的布局样式也是可以调整的。点击 `EndNote X9 -> Configure Bibliography `，在弹出的窗口中点击 `Layout`，可以设置字体、字号、缩进、行距等。

![](https://i.loli.net/2019/10/04/w9h8CDaUonIbPBl.png)

Word 原生自带一个引用（References），我没有使用过（看上去并不好用），如果你感兴趣，可以参考这篇 [官方说明文章](https://support.office.com/en-ie/article/create-a-bibliography-citations-and-references-17686589-4824-4940-9c69-342c289fa2a5) 以及 Microsoft Academic 的 [示例](https://www.microsoft.com/en-us/research/project/academic/articles/new-feature-cite/)。


![](https://i.loli.net/2019/10/04/WtbXg3MhSOwaoQ6.png)



### BibTeX

第 3 道名词解释题目：请解释 BibTeX 是什么？（10 分）

[BibTeX 网站](http://www.bibtex.org) 的回答（10 分）：

> BibTeX stands for a tool and a file format which are used to describe and process lists of references, mostly in conjunction with LaTeX documents.
>
> ---
>
> BibTeX 是一种用于描述和处理引用列表的工具和文件格式，通常与 LaTeX 文档一起使用。

正如前文提到的，BibTeX 和 LaTeX 天生是一对，通常与 LaTeX 结合使用，因此下面介绍在 LaTeX 中使用 BibTeX 的方法。但是这并不代表 BibTeX 只能和 LaTeX 一起使用，BibTeX 作为一种纯文本，可以作为引文数据的理想存储格式，与多种文件格式一起使用，比如 Markdown、R Markdown，甚至 [Microsoft Word](https://interfacegroup.ch/how-can-i-use-my-bibtex-library-in-ms-word/)。

与在 Word 中利用 EndNote 插入参考文献相比，在 LaTeX 中使用 BibTeX 更为简单，不需要繁复的设置，只需要 2 步：获取 BibTeX 文件和在 LaTeX 文档中引入 BibTeX 文件。

#### 获取 BibTeX 文件

与 EndNote 一样，几乎所有的文献数据库（中国知网不支持 😔）都支持导出为 BibTeX。这里以 ScienceDirect 为例，获取 BibTeX 文件。

如下图所示，点击「Export citation to BibTeX」，就会下载一个扩展名为 `.bib` 的文件。

![](https://i.loli.net/2019/10/05/iSDValgB7yO68QN.png)



下载完成之后打开这个文件，里面的内容如下 👇。百分号后的文字为注释内容，直接下载的 `.bib`文件里没有，是我之后加上的，包裹文字的  `{}` 也可以换成 `""`。

```latex
@article{YANG2019584, % article 表示这是期刊文章，YANG2019584 为键值（bib key），在文中用 \cite{YANG2019584} 进行引用
	title = {{Is mining harmful or beneficial? A survey of local community perspectives in China}},  % 文章标题，BibTeX 默认首字母大写，双层 {} 括号强制 PDF 输出与 .bib 文件中内容完全相同
	journal = {The Extractive Industries and Society},  % 期刊名称
  author = {Xiuyun Yang and Peter Ho},  % 作者名称，多个作者用 and 连接
	volume = {6},  % 卷
	number = {2},  % 期，有的期刊用的是 issue
	pages = {584 - 592},  % 起始页码
	year = {2019},  % 年份
	issn = {2214-790X},  % International Standard Serial Number（国际标准连续出版物号）
	doi = {https://doi.org/10.1016/j.exis.2019.02.006}, % Digital Object Identifier（数字对象识别号）
	url = {https://www.sciencedirect.com/science/article/pii/S2214790X18303228},  % 论文原文链接
	keywords = {Perceived net benefits, Mining, Land expropriation, Land subsidence, Rural China},  % 关键词
	abstract = {Mining activities often have significant impacts - both positive and negative - on local communities. This study shares experiences from China, surveying perspectives from rural communities on the net benefits of mining. Four indicators are identified and used to determine impact: employment opportunities, environmental pollution, land expropriation, land subsidence and associated resettlement. The analysis uses a demographically and economically diversified sample of 352 farmers residing in the vicinity of mines across six provinces. The study found that only a small number of farmers perceive mining to be providing net benefits, and that in such cases, direct employment is the main factor influencing this position. While land expropriation does not affect perceived net benefits, land subsistence does, and although relocation helps peasants minimize risks, it does not significantly change the population's generally negative view of mining. The priority for the Chinese government should be to formulate a sustainable framework to mitigate the risks of mining, particularly displacement and resettlement.},  % 摘要
}
```

需要注意的是，有些数据库不支持直接下载 `.bib` 文件，比如 Google Scholar，需要手动进行复制与粘贴。可以这样操作：复制网站上的 BibTeX 文件内容，用记事本之类的文本编辑器新建一个文件，将复制的内容粘贴进去，保存为 `ref.bib`，如果后缀不是 `.bib`，可手动将 `.txt` 修改为 `.bib`，因为它们都是纯文本。

![](https://i.loli.net/2019/10/05/eZ7iwbF2SnyTmAW.png)

下图中这个 `.bib` 文件是以前我的作业中用到的，用 VS Code 打开后是这个样子。

![](https://i.loli.net/2019/10/05/xvWPAepgMYt34OT.png)

#### LaTeX 中引用文献

LaTeX 有非常多的宏包实现参考文献的相关设置，其中最常用的应该是 [natbib](https://www.ctan.org/pkg/natbib) 了，我们要用到的实现国标参考文献样式的宏包 [gbt7714](https://github.com/CTeX-org/gbt7714-bibtex-style) 也兼容 natbib 宏包，gbt7714 宏包是用 BibTeX 实现国标参考文献样式的最简单方式，由清华大学 [李泽平](https://github.com/zepinglee) 开发。

完整的实现代码如下，百分号为该命令实现的功能或使用方法。

```latex
\documentclass[12pt, a4paper]{ctexart}  % 载入 ctexart 文档类，用于支持中文，同时设置全文正文字体为 12pt，页面为 A4
\usepackage{gbt7714}  % 加载 gbt7714 宏包
\usepackage[pdfborder={0,0,0}, colorlinks=true, citecolor=red]{hyperref}  % 加载 hyperref 宏包，去掉默认的链接边框，链接可跳转且引用角标为红色

\begin{document}  % 开始书写文章内容
\section*{测试 Bib\TeX{} 生成参考文献}  % 不自动编号的一级标题

2019年10月1日，庆祝中华人民共和国成立70周年大会在北京隆重举行\cite{YANG2019584}。在天安门城楼上，习近平总书记发表重要讲话，回顾新中国70年奋进历程，展望民族复兴的光明前景\cite{Yeyaoxian2016}，凝聚团结奋斗的磅礴力量。8分钟800多字的讲话赢得8次雷鸣般的掌声\cite{liu2018}，新时代中国的豪迈宣言激励着全体中华儿女——中国的昨天已经写在人类的史册上，中国的今天正在亿万人民手中创造\cite{cheng2016}，中国的明天必将更加美好！

历史不会忘记\cite{Wang1999The}，人民不会忘记，70年前的今天，正是在这里\cite{Buton}，毛泽东同志向世界庄严宣告\cite{Rkunzmann2013The}：“中华人民共和国中央人民政府今天成立了！”

%\nocite{*}  % 此命令会将 ref.bib 中的所有文献写入 PDF 文件中，无论是否在文中使用了 \cite{} 命令
%\phantomsection  % 该命令使 PDF 文件中参考文献超链接跳转更准确
%\addcontentsline{toc}{section}{参考文献}  % 将参考文献部分添加到目录中，层级为 section
\bibliography{ref} % 引入 ref.bib 文件
\end{document}  % 结束全文
```

生成的 PDF 效果如下图所示，可点击 [这里](https://dsc.cloud/TomBen/BibTeX-Test.pdf) 查看或下载 PDF 文件。

![](https://i.loli.net/2019/10/05/RGBaSJKZwbNfsro.png)


## 写在后面

如果你觉得本文对你有一点儿用，不妨扫描下方二维码小小地赞赏我一下～

![](https://i.loli.net/2019/10/05/nxkIfMliGEFmVyv.jpg)

![](https://i.loli.net/2019/10/05/rZmNT23ApaXqzW9.jpg)

所有的赞赏都将列在下方表格中，我将在 [我的博客](https://tomben.me/post/suggestions-for-writing-thesis) 中持续更新名单。表格已经列好，期待您的赞赏 😜

| 📅 | 👦/🧒  |   💰   |    ✉️     |
| :--: | :--: | :---: | :------: |
| 2019/10/6 | 任涛 | 🥇 10 | 辛苦了 😂 |
| 2019/10/6 | 阿森 |   🥈 5   | 哈哈哈总在图书馆碰见涛哥，辛苦了！ |
| 2019/10/6 | 椰子汁 |   🥈 5   | 涛哥冲冲冲！ |
| 2019/10/6 | Drifting |   🥈 5   |          |
| 2019/10/7 | Lee |   🥉 1.66   |   涛哥🐮 🍺   |


好吧，就写到这里。不多说了，开始准备毕业论文开题了。祝毕业的童鞋们都能顺利拿下毕业论文～

![](https://i.loli.net/2019/10/05/xqJvwWaABXQp2bN.jpg)