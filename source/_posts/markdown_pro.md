---
title: md语法
date: 2018-10-30 00:54:24
categories: web基础
tags:
    -语法
---

### 标题语法

    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题
    一级标题
    ===================
    二级标题
    --------------------

<!-- more -->
### 强调

Markdown 使用星号`（）`和底线`（_）`作为标记强调字词的符号，被 或 包围的字词会被转成用 `<em> `标签包围，用两个` *` 或 包起来的话，则会被转成 `<strong>`, 例如：
    一个强调字符, 即斜体, 可用 *asterisks* 或 _underscores_.

    两个强调字符, 即粗体, 可用 **asterisks** 或 __underscores__.

    也可以组合使用, 可用 **asterisks and _underscores_**.

    而想展现删除线, 可用两条波浪线. ~~Scratch this.~~

### 区块

    要在 Markdown 中建立代码区块很简单，有两种方法：
    第一种，只要简单地缩进 4 个空格或是 1 个制表符就可以.
    第二种，在代码段落的头部和尾部用包围起来（更建议用这种方式）。

### 图片

    一个惊叹号『!』
    接着一个方括号，里面是图片的替代文字
    接着一个普通括号，里面是图片的网址，最后还可以用引号包住并加上 选择性的『title’』文字。

    行内式(外链)的图片语法看起来像是：
    ![Alt text](/path/to/img.jpg)
    或
    ![Alt text](/path/to/img.jpg "Optional title")

详细叙述如下：
    1.一个惊叹号 !
    2.接着一个方括号，里面放上图片的替代文字
    3.接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。
**到目前为止，Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的标签。**

### 表格示例

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
    第一行为定义表格头部标题，而第二行是区分头部和设置对齐方式, 减号(-)至少有3个.  
    表格外围的管道的可选的, 也不需要让每行的每个TD的管道对齐.  
    最简单的写法也可以像下面那样，但是看代码就没上面的那么好看了，尽管最后的显示效果都一样.  
    在减号的两侧定义冒号":" 可设置该竖行的对齐方式, 左边加等于左对齐，两边都加等于居中对齐.


    Markdown | Less | Pretty
    --- | --- | ---
    *Still* | `renders` | **nicely**
    1 | 2 | 3

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

### 自动链接

[梦舞银雪的博客](http://setloser.github.io)

    [梦舞银雪的博客](http://setloser.github.io)

### 分割线

    这是分隔线上部分内容
    ---
    这是分隔线下部分内容

### 流程图
Markdown 编辑器已支持绘制流程图、时序图和甘特图。通过 mermaid 实现图形的插入，
点击查看[语法详情](https://mermaidjs.github.io/)。
### 列表

    - Red
    - Green
    - Blue

- Red
- Green
- Blue

<center> 参考来自：[CODIN Markdown 语法介绍](https://coding.net/help/doc/project/markdown.html)</center>
<center>**首次博文,不足之处多多包涵**</center>
