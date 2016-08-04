# MarkDown
出处:http://blog.csdn.net/zhaokaiqiang1992

## MarkDown编辑语法的简单学习

###Markdown语言简介
    首先markdown最终装换的格式是XHTML或者是HTML，它是一个轻量级的标记语言，所以在使用它的使用只需要记住少量标记
    语言就可以，使用它的大多数功能了。所以我觉得对于我这种又傻逼，记性又不行的人来说，用MD写日记最好不过了。其实
    markdown的优点很多，总结来说就是轻量级。
###编辑软件
    Mac下的编辑软件可以选择Mou，但是前些日子朋友推荐了Visual studio code。貌似也可以使用。Win下有很多在线编辑
    详情股沟。
###编辑语法
    [全部语法链接](http://wowubuntu.com/markdown/index.html)
####标题
    this is an h1 一阶标题
    =============
    this is an h2 二阶标题
    -------------
    或者是#表示 在最前边插入# 1-6个#表示6个阶级

####块引用 Blockquotes
    在一行的最前面加入> 你可以在一段的最前面或者是一段的每一行前面加> 但是在结束的最后一行必须敲四个空格或者是一个制表符

>this is  a blockquotes
>
>   区块引用也可以嵌套引用
>
>一级块
>>二级块一      

####代码块
    和程序相关的代码，通常不希望用一般的文件格式去排版，而是按照他原来的样子，MarkDown就会建立代码块，
    让他以原来的风格显示。
    在MarkDown中建立代码块很简单，只要简单的缩进4个空格符或者是一个制表符就可以了
####分割线
    你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或
    是减号中间插入空格
####链接
    要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的title
    文字，只要在网址后面，用双引号把 title 文字包起来即可，例如：
This is [an example](http://example.com/ "Title") inline link.
####插入图片
     ![Alt text](/path/to/img.jpg)
    详细叙述如下：
    一个惊叹号 !
    接着一个方括号，里面放上图片的替代文字
    接着一个普通括号，里面放上图片的网址