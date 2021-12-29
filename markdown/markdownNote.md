[TOC]
# 目录
## 标题
------  
名称md      标记md      格式
------  
一级标题     #        # 这是一级标题  
二级标题     ##       ## 这是二级标题  
三级标题     ###      ### 这是三级标题  
四级标题     ####     #### 这是四级标题  
五级标题     #####    ##### H5  
六级标题     ######   ###### H6  

## 文本
名称md 标记md 格式  
加粗    ****   **我是粗体Lemon**  
斜体    __     _我是斜体Lemon_  
斜体    **     *我是斜体Lemon*  
删除线 ~~~~     ~~我是删除的Lemon~~  
高亮    ''      '我是高亮的Lemon'

## 区块引用
名称md     标记md     格式  
引用        >         > 我是引用文字  
嵌套引用   多个>       >>Python 数据之道  
`示例：` 
>我是引用文字：
>>Python数据处理
>>>Python数据处理

## 无序列表
* markdown学习
* Python数据处理
- markdown学习
- Python数据处理
+ 列表项目1
+ 列表项目2

## 有序列表
样式1：
1. Lemon
2. Python 数据之道

样式2：
1. Lemon
1. Python 数据之道

## 链接效果
- 方法1：  
直接输入网址：  
http://163.com

- 方法2：  
[这是网易的连接](http://163.com)

- 方法3：  
[网易的连接][1]  
[我的主页][2]  

这里随便写什么都不影响的。

[1]: http://163.com
[2]: http://liyangbit.com


## 水平分割线
3个及以上 * 或 - 符号，如下
***
* * * 
---
- - ----
----------

## 代码高亮
markdown中输入如下：
```python
def printString(strIn):
    str1 = ' Python I like!'
    print(strIn + str1)
```

## 行内代码
我是行内`print("time can not waiting")`代码

## 目录
目录（Table of Content）可以通过markdown文件开头输入下面的标记实现

[TOC]

## 单个图片
- 通用语法
![这里是图片说明](cat.png)
- 设置图片的尺寸
![这里是图片说明](cat.png#width=10%)
- 直接用html img标签  
<img src="cat.png" width="20%" />

## 文本换行
直接用 \<br/> 或 \<br> 或者连续的两个空格

## 表格
表格的原始标记如下：
名称       |    md标记    |   md格式
:---------------|:------------:|------
引用 | > | 我是引用文字
嵌套引用 | 多个> | 我只是测试一下markdown语法

## html语法
markdown支持原生html语法

## 邮箱
使用一堆<>将你的额邮箱括起来即可：
<leichong2019@126.com>

## 强制分页
在markdown文本中需要分页的地方添加：
<div STYLE="page-break-after: always;"></div>
在Preview窗口不能看出分页的效果，但是在输出pdf时文件会完成分页。

## 数学公式
数学公式有两种，一种是用正文中的，一种是单独显示的。
- 正文中的公式：
$ ... $
- 单独一行显示的公式：
$$ ... $$
其中，$符号中间包含的三个点表示的LaTex的公式命令

举个例子：  
下面是行内公式  
我是行内公式$\sqrt{x^2+y^2}$行内公式  
下面是单独一行显示的公式：
$$ f(x)=\sum_{i=0}^{N} \int_{a}^{b} g(t,i) \text{d}t \tag{a}$$
$$ f(x)=\sum_{i=0}^{N} \int_{a}^{b} g(t,i) \text{d}t\text{AB} \tag{b}$$

## 脚注
markdown中输入如下
这里需要一个脚注[^1].

[^1]: http://anything.you.need

## 复选框
- [x] 这是已经完成的任务
- [] 这是没经完成的任务

## 参考链接
mdnice 网站中支持参考链接的实现，如下：  
什么是[金融](金融很重要"金融")？

## 注音符号
支持平台：微信公众号，用法如下：  
Markdown 这么好用，简直是 { 喜大普奔 |
hē hē hē hē } 呀！

## emoji
在Vs Code、Typora、Github 中支持emoji 表达：  
:+1: :sparkles: :camel: :tada:  
:rocket: :metal: :heart_eyes: :sob:  
可以通过下面这个网站来查看支持哪些emoji表情：  
emoji-cheat-sheet

## 流程图
markdown 支持绘制流程图，将语言标记为”flow“，举个例子如下：  
```flow
st=>start: 开始
op=>operation: 你的操作
cond=>condition: 是 / 否？
e=>end
st->op->cond
cond(yes)->e
cond(no)-op
```

## 文本北京强调
文本背景强调，其功能是想突出强调某些文本，具体的实现方式为：  
用一对== 将文字包裹起来即可，这个功能在Vs Code 可以实现：

  我是==Lemon==哈  

笔者尝试了几个在线的markdown编辑器，这
个功能都是不能实现的
