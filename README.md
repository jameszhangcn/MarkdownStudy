# MarkdownStudy
Study of using Markdown.

#Markdown教程
![图片](iconfinder_markdown_298823.png)

Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。
Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。
Markdown 编写的文档后缀为 .md, .markdown。
***
#Markdown的应用
Markdown 能被使用来撰写电子书，如：Gitbook。
当前许多网站都广泛使用 Markdown 来撰写帮助文档或是用于论坛上发表消息。例如：GitHub、简书、reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge等。
Markdown标题
============
Markdown 标题有两种格式。
---
##1.使用 = 和 - 标记一级和二级标题

##2.使用#号标记
使用#号可表示1-6级标题，一级标题对应一个 # 号，二级标题对应两个 # 号，以此类推。

#一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

***
# Markdown的段落
Markdown 段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个以上空格加上回车。

github.com  
google.com  


当然也可以在段落后面使用一个空行来表示重新开始一个段落
gitbub.com
google.com
***
# 字体
Markdown 可以使用以下几种字体：
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___

***
#分隔线

你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

----
----
----
****

#删除线
如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可，实例如下：

google.com
~~baidu.com~~

***

#下划线
下划线可以通过 HTML 的 <u> </u>标签来实现:

<u>带下划线的文本</u>

***
#脚注
脚注是对文本的补充说明。
Markdown 脚注的格式如下: [^要注明的文本]
以下实例演示了脚注的用法：

创建脚注 [^test]。
	[^test]: 我是脚注！！
生成一个脚注1[^footnote].
	[^footnote]: 这里是 **脚注** 的 *内容*.
生成一个脚注2[^foot].
	[^foot]:这里是**脚注2**的*内容*.
***
#Markdown列表
Markdown 支持有序列表和无序列表。
无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记：
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项

有序列表使用数字并加上 . 号来表示，如：
1. 第一项
2. 第二项
3. 第三项

#列表嵌套
列表嵌套只需在子列表中的选项添加四个空格即可：
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素

***
#Markdown 区块
Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：
	> 区块引用
	> 技术学习
	> 区块链

另外区块是可以嵌套的，一个 > 符号是最外层，两个 > 符号是第一层嵌套，以此类推：

> 最外层
>> 第一层嵌套
>>> 第二层嵌套

#区块中使用列表
区块中使用列表实例如下：
> 区块中使用列表
> 1.第一项
> 2.第二项
> + 第一项
> + 第二项
> + 第三项


#列表中使用区块
1.第一项
	>第一个
	>第二个
2.第二项
3.第三项


***

#Markdown代码
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`），例如：
## 代码区块一

'printf()' 函数


## 代码区块使用 4 个空格或者一个制表符（Tab 键）。
实例如下：
## 代码区块二
	shell
    echo 'Hello world!';
    
##你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：
## 代码区块三

``` c
void main(int argc, char* argv[])
{
	printf("Hello world!");
    return;
}
```
***
#Markdown 链接
链接使用方法如下：
[链接名称](链接地址)

或者

<链接地址>

例如：
这里是一个链接[菜鸟教程](https://www.runoob.com)

直接使用链接地址：

<https://www.baidu.com>

#高级链接
我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：

这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）

	[1]: http://www.google.com/
	[runoob]: http://www.runoob.com/

#Markdown 图片 
Markdown 图片语法格式如下：
![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")


* 开头一个感叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。


使用实例：
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

当然，你也可以像网址那样对图片网址使用变量:
这个链接用 1 作为网址变量 [RUNOOB][1].
然后在文档的结尾为变量赋值（网址）

	[1]: http://static.runoob.com/images/runoob-logo.png

markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 <img> <img/>标签。

<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">


#Markdown表格
Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。
语法格式如下的：

|表头|表头|
|----|----|
|单元格|单元格|
|单元格|单元格|


对齐方式 
我们可以设置表格的对齐方式：
-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。

实例如下：
***

| 左对齐| 右对齐| 居中对齐 |
|:----|----:|:----:|
|单元格|单元格|单元格|
|单元格ABC|单元格BCD|单元格5678|


| column | column |
|--------|--------|
|        |        |

#Markdown 高级技巧 
##支持的 HTML 元素
不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。
目前支持的 HTML 元素有：<kbd> <b> <i> <em> <sup> <sub> <br>等 ，如:

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
****


##转义
Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠转义特殊字符：
**文本加粗** 
\*\* 正常显示星号 \*\*


Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

\   反斜线
`   反引号
	\*   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
\#   井字号
\+   加号
\-   减号
.   英文句点
!   感叹号

****

#公式
当你需要在编辑器中插入数学公式时，可以使用两个美元符 $$ 包裹 TeX 或 LaTeX 格式的数学公式来实现。提交后，问答和文章页会根据需要加载 Mathjax 对数学公式进行渲染。如：
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$

# 主标题
## 二级标题
***
## 图片位置--居左/居中/居右
### div align
<img src="tennis.jpg" div align=right/>
***
<img src="tennis.jpg" div align=left/>
***
<img src="tennis.jpg" div align=center/>
***
<img src="tennis.jpg" width = 100% height = 100% div align=center/>

***
##简介
***
##<center>END<center/>

