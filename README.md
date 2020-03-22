
## 简介

> MarkDown是一种轻量级标记语言，以纯文本格式编写文档，然后转换成有效的XHTML/HTML内容

- 语法简洁明了、易读易写
- 轻量、纯文本、跨平台、兼容性极强
- 可以转换为HTML/XHTML、EPUB、PDF、Word、纂写Gitbook
- 广泛使用：
  - Github
  - 简书
  - Typecho
  - WordPress（需编辑器插件）
  - Reddit
  - Diaspora
  - Apollo
  - Moodle
  - more ......
- 创造者：[**Aaron Swartz**](http://www.aaronsw.com/)和[**John Gruber**](https://daringfireball.net/)共同设计

**Aaron Swartz**（1986年11月8日－2013年1月11日）

MarkDown主要贡献者，Aaron Hillel Swartz（全名）的维基百科介绍为：美国程序员、企业家、作者、政治活动者、互联网黑客主义者，点击查看更多关于这位天才的[完整生平]([https://zh.wikipedia.org/zh-hans/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8#](https://zh.wikipedia.org/zh-hans/亚伦·斯沃茨#))

## 开始使用

- 编辑器：Typora、Sublime Text、VS code...
- 首推跨平台、所见即所得的[Typora](https://typora.io/)编辑器

#### 标题

一般的，MarkDown使用`#`可以表示1-6级标题

>\# 这是一级标题
>\## 这是二级标题
>\### 这是三级标题
>\#### 这是四级标题
>\##### 这是五级标题
>\###### 这是六级标题

显示效果：

># 这是一级标题
>## 这是二级标题
>### 这是三级标题
>#### 这是四级标题
>##### 这是五级标题
>###### 这是六级标题

对于一级和二级标题，还可以使用`-`和·`=`来标记
```MarkDown
这是一级标题
==========
这是二级标题
----------
```
显示效果：

>这是一级标题
>==========
>这是二级标题
>----------

#### 列表

##### 无序列表

使用`-`、`*`、`+`来标记无序列表，下面以`-`为例
```MarkDown
- 这是第一项
- 这是第二项
- 这是第三项
```
显示效果：

>- 这是第一项
>- 这是第二项
>- 这是第三项

##### 有序列表

在阿拉伯数字后面加上`.`来标记
```MarkDown
1. 这是第一项
2. 这是第二项
3. 这是第三项
```

显示效果：

>1. 这是第一项
>2. 这是第二项
>3. 这是第三项

##### 列表嵌套

在子级列表前加4个<kbd>空格</kbd>来标记

```MarkDown
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
    - 第一项嵌套的第三个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
    - 第二项嵌套的第三个元素
3. 第三项：
    - 第三项嵌套的第一个元素
    - 第三项嵌套的第二个元素
    - 第三项嵌套的第三个元素
```

显示效果：

>1. 第一项：
>    - 第一项嵌套的第一个元素
>    - 第一项嵌套的第二个元素
>    - 第一项嵌套的第三个元素
>2. 第二项：
>    - 第二项嵌套的第一个元素
>    - 第二项嵌套的第二个元素
>    - 第二项嵌套的第三个元素
>3. 第三项：
>    - 第三项嵌套的第一个元素
>    - 第三项嵌套的第二个元素
>    - 第三项嵌套的第三个元素

#### 段落

一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行，对于大部分现代的MarkDown编辑器（比如Typora），你完全不用关心，写作怎么换行就这么换行就好

#### 反转义

使用反斜杠`\`使标记符号成为普通符号

可以在以下符号前加上`\`来标识

- \   反斜线 
- ` 反引号 
- \* 星号 
- _  底线
- {}  花括号
- []  方括号 
- ()  括弧 
- \#   井字号 
- \+ 加号
- \- 减号
- .  英文句点
- !   惊叹号

#### 字体格式

##### 粗体

使用`**`或`__`来标记被加粗的文本

>\*\*这是被加粗的文本\*\*
>\_\_这也是被加粗的文本\_\_

显示效果：

>**这是被加粗的文本**
>__这也是被加粗的文本__

##### 斜体

使用`*`或`_`来标记倾斜的文本

>\*这是倾斜的文本*
>\_这也是倾斜的文本_

显示效果：

>*这是倾斜的文本*
>_这也是倾斜的文本_

##### 粗斜体

使用`***`或`___`来标记粗斜体文本

>\*\*\*这是一段粗斜体\*\*\*
>\_\_\_这也是一段粗斜体\_\_\_


显示效果：

>***这是一段粗斜体***
>___这也是一段粗斜体___

#### 删除线

使用两个`~`来标记删除线文本

>\~~这是加删除线的文本~~

显示效果：

>~~这是加删除线的文本~~

#### 分割线

在单独的一行使用三个或三个以上的`*`或`-`来标记分割线

> \***
> 我被夹在分割线里
> \***
> \---
> 我被夹在另一条分割线里
> \---

显示效果：

> ***
> 我被夹在分割线里
> ***
> ---
> 我被夹在另一条分割线里
> ---

#### 下划线

使用两个`<u>`标记添加下划线的文本

> \<u>这是被下划线标记的文本\</u>

显示效果：

> <u>这是被下划线标记的文本</u>

#### 脚注

使用`[^这是注明的信息]`来标记脚注

比如：

> 这是一段文字[^注1]
>

#### 区块引用

Markdown 标记区块引用是使用类似 email 中用 `>` 的引用方式

```MarkDown
>这是一段被引用的内容
```

显示效果：

> 这是一段被引用的内容

**嵌套引用**

> \> 最外层
> \> \> 第一层嵌套
> \> \> \> 第二层嵌套

显示效果：

> 最外层
> > 第一层嵌套
> >
> > > 第二层嵌套

#### 代码区块

**短代码**

对于短代码，使用<kbd>`</kbd>包裹住

比如：`printf`、`scanf`

**代码块**

一般的在代码块前使用4个空格或者一个TAB键：

<kbd>Space</kbd><kbd>Space</kbd><kbd>Space</kbd><kbd>Space</kbd>或者<kbd>TAB</kbd>

但是比较常用的是使用\```包住代码块，在开头的\```后还可以标记代码的语言类型，比如：

> \```JavaScript
> $(document).ready(function () {
> alert('RUNOOB');
> });
> \```

显示效果为

```JavaScript
$(document).ready(function () {
    alert('RUNOOB');
});
```

#### 链接

一般的，MarkDown链接有两种：

> \[这是链接名称](这是链接地址)
>
> <这是自动链接>

比如：

> 这是我的博客[Spoience的小栈](https://spoience.top)
>
> 这是Spoience的小栈<https://spoience.top>
>
> 这是邮箱：<example@mail.com>

稍微复杂一点的高级链接有点类似于MarkDown的脚注,实际注明的链接类似于脚注在文末引用，比如：

> 这是\[谷歌][2]
>
> 这是\[百度][3]

显示效果为：

> 这是[谷歌][2]
>
> 这是[百度][3]

#### 图片

一般的，引用图片，其中`图片标题`跟`alt属性文本`可以不写

> \![alt 属性文本]\(图片地址 "图片标题")

比如：

> \![](图片地址)

显示为：

​    ![](https://uploadbeta.com/api/pictures/random/?key=BingEverydayWallpaperPicture)

#### 表格

对于最基础的表格，仅仅用到`|`和`-`来标记表格的基本结构

比如：

>\|表头1\|表头2|<br>
>\|--------\|--------|<br>
>\|单元格1\|单元格2\|<br>
>\|单元格3\|单元格4\|

显示为：

> | 表头1   | 表头2   |
> | ------- | ------- |
> | 单元格1 | 单元格2 |
> |单元格3  | 单元格4 |
在基础的表格功能上，我们还可以使用`:`和`-`来设置表格的对齐方式

- **-:** 设置内容和标题栏居右对齐
- **:-** 设置内容和标题栏居左对齐
- **:-:** 设置内容和标题栏居中对齐

下面以表格居中为例，比如：
>\|表头1\|表头2|<br>
>\|:--------:\|:--------:|<br>
>\|单元格1\|单元格2\|<br>
>\|单元格3\|单元格4\|<br>

显示为：

> |表头1|表头2|
> |:--------:|:--------:|
> |单元格1|单元格2|
> |单元格3|单元格4|

#### 更多姿势

其实，上面就是MarkDown一般技巧，也是最常使用的。一般的，MarkDown写作最直接转换的就是HTML文本，所以，MarkDown显然也可以支援一些HTML属性，比如：

> \<kdb> \<b> \<i> \<em> \<sup> \<sub> \<br>

像有些网站的`html`嵌入代码，有些在MarkDown也是支持的，但不是全部，具体还要看MarkDown的编辑器和渲染器是否支持，像网易云音乐的`HTML`嵌入代码大部分使用MD解析的程序可以支持，比如：

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=29717271&auto=1&height=66"></iframe>

对于数学公式，MarkDown支持使用两个`$$`包裹`TeX`、`LateX`或`Mathjax`的数学公式，因为个人使用不是很多，这里不做叙述😛

### 参考资料

- [MarkDown基本语法](http://younghz.github.io/Markdown/)
- [简书-献给写作者的 Markdown 新手指南](https://www.jianshu.com/p/q81RER)
- [菜鸟教程-MarkDown教程](https://www.runoob.com/markdown/md-tutorial.html)
- [维基百科-MarkDown](https://zh.wikipedia.org/wiki/Markdown)
- [Markdown 语法说明 (简体中文版)](https://www.appinn.com/markdown/)

[^注1]: 看文末，这是一段注释

[2]:https://www.google.com/
[3]:https://www.baidu.com/
