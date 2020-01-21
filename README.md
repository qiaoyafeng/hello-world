# Markdown 教程

* Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
* Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。
* Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。
* Markdown 编写的文档后缀为 .md, .markdown。

## Markdown 应用




## 编辑器
Typora 官网：[https://typora.io/](https://typora.io/)



## Markdown 标题
Markdown 标题有两种格式。 
1. 使用 = 和 - 标记一级和二级标题
= 和 - 标记语法格式如下：
```text
我展示的是一级标题
=================

我展示的是二级标题
-----------------

```



2. 使用 # 号标记
使用 # 号可表示 1-6 级标题，一级标题对应一个 # 号，二级标题对应两个 # 号，以此类推。

```text

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

```

## 字体

Markdown 可以使用以下几种字体：
```text
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___

```

~~删除线~~


## 引用
> 这是引用的内容
>> 李白的诗
>>> 杜甫的诗
>>>> 陆游的诗

## 分割线


------------------------

上下分割线

************************


## 图片

![百度](https://www.baidu.com/img/baidu_jgylogo3.gif "百度Logo" )


## 图片加链接

[![](https://www.mdeditor.com/images/logos/markdown.png)](https://www.mdeditor.com/images/logos/markdown.png "markdown")


## 列表

### 无序列表

* 列表1
* 列表2
* 列表3

#### 无序列表  嵌套
+ 列表1
    + 列表1A
    + 列表1B
    + 列表1C
+ 列表2
    * 列表2A
    * 列表2B
+ 列表3

### 有序列表
1. 列表1
2. 列表2
3. 列表3

#### 有序列表 嵌套
1. 列表1
    1. A
    2. B
    3. C
2. 列表2
    * A
    * B
    * C
3. 列表3
    + A
    + B
4. 列表4
    - A
    - B
    
    
## 任务
- [ ] 任务A
- [x] 任务B
- [ ] 任务C
- [x] 任务D


## 表格

|商品|价格|数量|备注|
|:---:|:---:|:---:|:---:|
|创新|200K|50|斯坦福创新课程|
|双创|400K|100|斯坦福双创课程|
|QP|50K|3000|质量项目|


## 代码
### 单行代码

`helloworld`


### 代码块

```python
from .base import *

DEBUG = False

try:
    from .local import *
except ImportError:
    pass

```


## 公式
$$
 E=mc^2 
$$

## 绘制流程图 Flowchart
```flow

st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op


```



## 绘制时序图

```sequence
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```
