# 写作毕业论文的几点建议

作者：[任涛](https://tomben.me)

邮箱：me@tomben.me

版本：1.0



## 写在前面

[当代大学生难题：又又又又要排版论文了](https://mp.weixin.qq.com/s/iwcbhv75o6RnWAPZpV9U_A)

[毕业论文一次过！这份最全攻略，帮你轻松搞定排版](https://mp.weixin.qq.com/s/Fpya9Y6WZFs9bTDQFQjJWg)

## 一定要使用 Word 样式

Word 很好上手，这应该是接触过 Word 的人都会承认的，但有一句话大家应该也有所耳闻：HR 绝不相信你的简历上写的「精通 Word (Office)」。我们真的会用 Microsoft Word 吗？恐怕大多数人并不会吧。

我现在还清楚记得，一些同学上课或者听讲座的场景：背上自己沉重的电脑，早早来到教室，坐在前排，电脑开机，打开 Microsoft Word 或者 WPS Office，做好了做笔记的一切准备，然后掏出手机开始玩。台上的老师讲得眉飞色舞，台下的同学不停地敲着键盘，将老师讲的内容记在 Word 里面。一节课下来，老师口干舌燥，同学手指酸痛，Word 里密密麻麻。点击笔记文件中的样式窗格，全是「正文」，完全没有结构可言。

可能你说我把标题文字部分字号设置为三号字，字体加粗，前后各空一行，居中对齐，就是一级标题了。可是这是你觉得的标题，并不是 Word 觉得的标题，如果 Word 像黄晓明一样霸道，他一定会要用「明学」里一句经典语录反驳你：我不要你觉得，我要我觉得。

### 各级标题



### 图表标题



## 一定要做好版本控制

按照惯例，先来进行名词解释。

请解释版本控制是什么？（10 分）

Git 官方网站的回答（9 分）：

> 版本控制是一种记录一个或若干文件内容变化，以便将来查阅特定版本修订情况的系统。
>
> ---
>
> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

简单粗暴的回答（8 分）：

>版本控制是一个记录文件的更改过程，便于创建分支进行更改、回到文件历史版本、进行协作等功能的系统。

当你由于误操作，修改了某一个文件的内容，而想要恢复该内容却不能恢复的时候，当你的电脑丢失或出现故障，想要其中的重要数据的时候，当你想要和别人合作完成项目的时候…… 你就会体会到版本控制是多么的重要。

### Git

![](https://i.loli.net/2019/10/04/WBwIeoQxRn7CuDm.png)



![](https://i.loli.net/2019/10/04/2XgIbFD3QYGtv8w.png)

### 网盘

除了 Git 之外，网盘或者云盘也是可以进行版本控制的，这里介绍两个网盘的版本控制，Dropbox 和坚果云，分别作为代表墙外和墙内的网盘代表。

#### Dropbox

程序员之间有很多 [鄙视链](https://mp.weixin.qq.com/s/xdHLZIQGVT5fQzjfazGP_g)，其中关于版本控制的鄙视链是这样的：

> 用 Git 或 Mercurial 的工程师鄙视用 Subversion 的工程师，用 Subversion 的工程师鄙视用 Dropbox 来做版本控制的工程师，用 Dropbox 来做版本控制的工程师鄙视根本不知道什么叫做版本控制的工程师。



#### 坚果云



## 最好实现参考文献自动化

写论文参考文献必不可少，毕业论文当然也不例外，很多童鞋写论文过程中最为头痛的部分可能就是参考文献了。这里我介绍两种实现参考文献自动化的方法，方法一是 EndNote 和 Word 的结合，方法二是在 LaTeX 中使用 BibTeX 生成参考文献，当然你任选其一（绝大多数人应该会选择方法一，但我认为方法二才是更加优雅的方式），都能达到简化我们工作的目的，正如 Kieran Healy 所说：

> Make your computer work for you by automating as many of these steps as you can.

有了以上两种实现参考文献自动化的方法的加持，你再也不用一遍又一遍地复制和粘贴参考文献了，若是文献前后顺序发生了改变，也不再需要一个一个手动调整。

### EndNote

[EndNote](https://endnote.com) 是一款知名的文献管理软件，由科睿唯安[^k]（Clarivate Analytics）开发，至今已有二十余年历史，在学术界具有较高的普及度。实际上，文献管理软件多如牛毛，叫得出名字的就有 [Papers](https://www.papersapp.com)、[Mendeley](https://www.mendeley.com)、[Zotero](https://www.zotero.org)、[Citavi](https://www.citavi.com/en)、[NoteExpress](http://www.inoteexpress.com/aegean/) 等等，为什么这里我只介绍 EndNote 呢？因为：

1. EndNote 最为著名，通用性较强，网上教程很多。
2. 与 Microsoft Word 结合，EndNote 算是比较不错的（我猜你是用 Word 写论文的吧）。
3. 部分高校图书馆购买了 EndNote，在校师生可以免费使用。


[^k]:科睿唯安旗下拥有众多业界知名品牌，如 Web of Science 平台，其中包含著名的科学引文索引 SCI (Science Citation Index) 和社会科学引文索引 SSCI (Social Science Citation Index)。

截止 2019 年 10 月 4 日，EndNote 的最新版本为 `X9.2`，官网售价 249.95 美元（约合人民币 1786.54 元），即使学生享受 5 折优惠购买，售价也将近 900 元人民币。不过幸运的是，很多高校图书馆似乎体贴到了我们的贫穷，购买了机构版 EndNote 供在校师生免费使用，比如 [北京大学图书馆](https://www.lib.pku.edu.cn/portal/cn/zy/dzzy/gjrj/endnote)、[中国科学技术大学图书馆](http://lib.ustc.edu.cn/电子资源/database/9-工具软件/[新增]endnote-x7-文献管理软件/#)、[中山大学图书馆](http://lzcxdj.com/article/599)、[四川大学图书馆](http://202.115.54.22/resourcenov/resourcedetail/SCU04595) 等。

以后当别人问你，你的 EndNote 破解版在哪儿下载的时候，你可以骄傲地对他/她说：**我用的是正版 EndNote！用正版，我骄傲！**然后手把手教他/她怎么在图书馆网站下载和安装 EndNote。

再补充一下，EndNote、NoteExpress、Mendeley 这类文献管理软件大同小异，如果你不喜欢 EndNote，或者因为某些原因无法正常使用 EndNote，尝试使用其他的软件也是完全没有问题的，毕竟有些还是完全免费的，比如 Mendeley、Zotero。

四川大学图书馆在附上下载地址的同时，也贴心地放上了 [EndNote 操作指南](http://202.115.54.39/meta/endnote/win/EndNote_on_Windows.pdf)，如果你不想看这个英文指南，可以看看我的简单使用示例。跟着下面的示例设置一遍，基本就可以无痛解决论文参考文献了。

**1.  设置引文样式**

下载安装后的 EndNote 自带超过 500 种引文样式，但并不包括一般毕业论文要求的 [GB/T 7714-2015 《信息与文献  参考文献著录规则》](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style/files/153951/GBT.7714-2015.pdf)，即中国的参考文献推荐标准，因此需要自行安装，安装的步骤也比较简单：

- 下载 [Chinese Std GBT7714 (author-year)](https://endnote.com/style_download/chinese-standard-gb-t7114-author-year/) 和 [Chinese Standard GB/T7714 (numeric)](https://www.endnote.com/style_download/chinese-standard-gb-t7714-numeric/)
- 双击打开下载的 `.ens` 文件，默认会在 EndNote 中打开
- 点击 `File -> Save As`，在弹出的窗口点击 `Save`
- 打开 EndNote，点击 `Edit -> Output Styles -> Open Style Manager`，找到刚刚安装好的两个国标引文样式，在前面的复选框内打上勾 ✔️

![](https://i.loli.net/2019/10/04/2Qh8g3Mm9FlAw5X.png)

**2.  下载参考文献，导入 EndNote**

在 [Google Scholar](https://scholar.google.com)（[百度学术](http://xueshu.baidu.com) 也还凑合）中搜索文献，点击下方的双引号「”」，在弹出的对话框中点击「EndNote」，然后就会下载扩展名为 `.ris` 的 EndNote 引文格式，此处命名为 `ref.ris`。

![](https://i.loli.net/2019/10/04/V7mGyESNUg4anPZ.png)



常用中文数据库 [中国知网](https://www.cnki.net)、[万方数据](http://www.wanfangdata.com.cn/index.html)、[维普资讯](http://qikan.cqvip.com) 也都提供 EndNote 引文格式的下载，并且支持批量操作。

![](https://i.loli.net/2019/10/04/xYiHJtmqjKF7rT1.png)



容易看出，三大数据库导出的 EndNote 引文格式并不完全一样，特别当导出一些年代久远、数据不全的论文更为明显，需要自己手动修改引文中的内容。而后文用到的 BibTeX 一般就不存在这样的问题。

国外的数据库在引文方面做得更好，比如 [ScienceDirect](https://www.sciencedirect.com) 数据库可以在每篇上方点击「Expert」导出需要的引文格式，同样包括 EndNote 的 `.ris` 格式，也可以批量导出。

![](https://i.loli.net/2019/10/04/Jco2lISCw45Hdsy.png)



**3.  新建 EndNote 数据库**

打开 EndNote，点击上方 `File -> New`，在弹出的对话框（如下图）中命名数据库和更改存储位置。此处命名为 `My EndNote Library`，存储在 `Desktop`。点击 `Save` 之后，桌面上会出现一个文件和一个文件夹，分别是 `My EndNote Library.enl` 和 `My EndNote Library.Data`，这是由 EndNote 自动生成的，写作毕业论文所有的参考文献的数据都会保存在里面。需要注意的是，你的 Word 论文应该和这些 EndNote 数据保存在同一个文件夹中，不要随意移动，避免由于文件路径的改变带来的麻烦。

![](https://i.loli.net/2019/10/04/SCGfR5pJ6aEAs83.png)
**4.  添加引文数据至 EndNote 数据库**

双击前面下载完成的 `ref.ris`，在弹出的窗口中选择 `My EndNote Library.enl`，然后点击 `Open`，就将 `ref.ris` 添加到了 EndNote 数据库 `My EndNote Library.enl` 中了，EndNote 中显示的效果如下图所示。

![](https://i.loli.net/2019/10/04/pxSX9vnudmoHDTC.png)
**5.  在 Word 中引用文献**

下载并安装好 EndNote 后，会自动安装 Word 插件，可以在 Word 上方菜单栏中找到。

![](https://i.loli.net/2019/10/04/FHabuDQvnmPZAe3.png)

前面的准备工作全部完成，下面开始写作，在 Word 中使用 EndNote 引用参考文献：

- 在 EndNote 中选中需要引用的文献（按住 `shift` 键可以选择多个）

![](https://i.loli.net/2019/10/04/nwHmO2sLlUYRhQT.png)

- 光标定位到需要插入引用的位置，依次点击 `EndNote X9 -> Insert Citation -> Insert Selected Citation(s) ` ，即可自动完成引用。

![](https://i.loli.net/2019/10/04/hp8avALus9jBZS6.png)

从上图可以看出，点击参考文献文字部分，文字上会有一层灰色阴影，说明这是 Word 中的宏，从窗口右侧的「样式窗格」也可以发现这部分内容是「EndNote Bibliography Title」，而不是「正文」。

需要注意的是，直接下载安装的 `Chinese Standard GB/T7714 (numeric)` 有一些小问题，比如括号只有一半、作者姓名大小写等问题，需要自行修改，上图中的最终效果是我修改后的结果。修改方法如下：依次点击 `Edit -> Output Styles -> Edit "Chinese Std GBT7714 (numeric)"`，在弹出的窗口中（如下图所示），将 Journal Article 修改为如下格式：

```
Author. Title[J]. Journal, Year, Volume|(Issue)|:Pages.
```

![](https://i.loli.net/2019/10/04/j9BCf2M3iObcVTx.png)

因为测试文档里只包含 Journal，没有 Book、Thesis 等其他种类的文献，这里只修改了 Journal，但其他种类的文献格式也可能有问题，可根据需要自行修改。善于利用搜索引擎，总是能修改正确的。

此外，在 Word 中，参考文献的布局也是可以调整的。点击 `EndNote X9 ->Configure Bibliography `，在弹出的窗口中选择 `Layout`，可以设置字体、缩进、行距等。

![](https://i.loli.net/2019/10/04/w9h8CDaUonIbPBl.png)

Word 原生自带一个引用（References），我没有使用过[^q]，如果你感兴趣，可以参考这篇 [官方说明文章](https://support.office.com/en-ie/article/create-a-bibliography-citations-and-references-17686589-4824-4940-9c69-342c289fa2a5) 以及 Microsoft Academic 的 [示例](https://www.microsoft.com/en-us/research/project/academic/articles/new-feature-cite/)。

[^q]:看上去并不好用

![](https://i.loli.net/2019/10/04/WtbXg3MhSOwaoQ6.png)



### BibTeX




## 字体的一些建议

思源宋体