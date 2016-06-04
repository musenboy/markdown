# markdown
title: markdown语法入门
tags: 
    - markdown
---

# 标题
在行首插入1到6个#，对应到标题1到6阶

```
# 标题1   
## 标题2
### 标题3
#### 标题4
##### 标题5
###### 标题6  
```

<!--more-->

效果

# 标题1   
## 标题2
### 标题3
#### 标题4
##### 标题5
###### 标题6 


可以用闭合样式的标题，只是美观用的，在行尾加上#，而行尾的#数量也不用和开头一样（行首的井字符数量决定标题的阶数）

```
# 标题1 #
## 标题2 # 
### 标题3 #
#### 标题4 #
##### 标题5 #
###### 标题6 #
```
建议书写规范在#后加个空格

# 区块引用

区块引用使用尖括号>开头

```
> 整理知识，学习笔记
> 发布日记，杂文，所见所想
> 撰写发布技术文稿（代码支持）
> 撰写发布学术论文（LaTeX 公式支持）
```

区块引用还可以嵌套
用两个或多个尖括号>开头

```
> 整理知识，学习笔记
> 发布日记，杂文，所见所想
> 撰写发布技术文稿（代码支持）
> 撰写发布学术论文（LaTeX 公式支持）
>> 这是内部引用
>>> 第三级内部引用
```
效果
> 整理知识，学习笔记
> 发布日记，杂文，所见所想
> 撰写发布技术文稿（代码支持）
> 撰写发布学术论文（LaTeX 公式支持）
>> 这是内部引用
>>> 第三级内部引用

区块引用里面还可以写其他语法

```
> # 整理知识，学习笔记
> # 发布日记，杂文，所见所想
> 1. 撰写发布技术文稿（代码支持）
> 2. 撰写发布学术论文（LaTeX 公式支持）
```

效果

> # 整理知识，学习笔记
> # 发布日记，杂文，所见所想
> 1. 撰写发布技术文稿（代码支持）
> 2. 撰写发布学术论文（LaTeX 公式支持）

值得注意的是，要想脱离不再使用区块引用，空一行后书写即可。

# 列表

Markdown 支持有序列表和无序列表。

无序列表使用星号、加号或是减号作为列表标记：

    *  无序列表

等同于：

    +  无序列表

也等同于：

    －  无序列表

无序列表

有序列表则使用数字接着一个英文句点：

```
1.  有序列表A

2.  有序列表B

3.  有序列表C
```

效果

1.  有序列表A

2.  有序列表B

3.  有序列表C

# 高亮一段代码 

``` 
```javascript
function myblog() {
    alert("我的个人博客http://www.musenboy.com");
}
```              
```


高亮代码效果

```javascript
function myblog() {
    alert("我的个人博客http://www.musenboy.com");
} 
```


# 分割线

在一行中用三个以上的星号来建立一个分隔线，行内不能有其他东西。你也可以在星号中间插入空格。下面每种写法都可以建立分隔线：

```
    * * *
    ***
    *****
```

效果

* * *
***
*****

# 链接

链接分为文字和图片链接

```
    文字链接为：[]()

    图片为：![]()
```

比如：

```
    [我的博客](http://www.musenboy.com)
    ![图片](http://upload.jianshu.io/daily_images/images/MRopH5jy9co1Kag7CksW.jpg)
```

# 斜体

斜体，两个*包含一段文字，*和文字间不能有空格，比如：

```
*在编辑区任意行首位置输入以下格式的文字可以标签当前文档*
```
效果

*在编辑区任意行首位置输入以下格式的文字可以标签当前文档*

# 表格

```
| 水果 |  重量 |
| ---  | ---  |
| 苹果 | 10KG |
| 桃子 | 5KG |
```

表格效果

| 水果 | 重量 |
|-----|------|
|苹果  | 10KG | 
|桃子  | 5KG  | 

# Markdown编辑器

## Windows平台

* [markdownpad](http://www.markdownpad.com/)

* [markpad](http://code52.org/DownmarkerWPF/)

* [Writemonkey](http://writemonkey.com/index.php)

## Mac平台

* [Mou](http://25.io/mou/)

* [Markdown](http://zgrubby.wix.com/touchdreamapp)

## 在线编辑器

* [CmdMarkdown](https://www.zybuluo.com/mdeditor)

* [MuHua](http://mahua.jser.me/)

* [stackedit](https://stackedit.io/editor)

* [Epiceditor](http://epiceditor.com/)

* [Markable](https://markable.in/)

* [Dillinger](http://dillinger.io/)

* [Instantmark](http://jrham.es/instantmark/)

* [Backpager](http://backpager.amasan.co.uk/)
