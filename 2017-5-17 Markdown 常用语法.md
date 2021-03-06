---
title: 2017-5-17 Markdown 常用语法
date: 2017-05-17 21:46:29
categories: [Notes, Markdown]
tags: [Markdown,  速查]
---
## 标题(一)

代码：
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
<!-- more -->
效果：

![](http://ohhmsby4v.bkt.clouddn.com/image/2017-05-18_markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95_%E6%A0%87%E9%A2%981.png)

---
## 标题(二)

代码：
```
标题（#）
==
标题（##）
--
```
效果：

![](http://ohhmsby4v.bkt.clouddn.com/image/2017-05-18_markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95_%E6%A0%87%E9%A2%982.png)

---
## 无序列表

代码：
```
- 文本1
   * 二级文本
- 文本2
- 文本3
```
效果：
> - 文本1
>    * 二级文本
> - 文本2
> - 文本3

---
## 有序列表

代码：
```
1. 文本1
2. 文本2
3. 文本3
```
效果：
>  1. 文本1
>  2. 文本2
>  3. 文本3

---
## 文字链接

代码：
```
[显示文本](链接地址)
[悟の迹](http://chihweihsu.com/)
```
效果：
>  [悟の迹](http://chihweihsu.com/)

---
## 自动链接

代码：
```
<http://chihweihsu.com/>
```
效果：
>  <http://chihweihsu.com/>

---
## 参考式链接

代码：
```
I get 10 times more traffic from [Google] [1] than from [Yahoo] [2] or [MSN] [3],
but most traffic is [悟の迹] [4].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
  [4]: http://chihweihsu.com/    "悟の迹"

```
效果：
> I get 10 times more traffic from [Google] [1] than from [Yahoo] [2] or [MSN] [3], but most traffic is [悟の迹] [4].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
  [4]: http://chihweihsu.com/    "悟の迹"

---
## 插入图片

代码：
```
![alt text](图片链接 "title")
![悟](http://ohhmsby4v.bkt.clouddn.com/image/%E6%82%9F.jpg)

```
效果：
>  ![悟](http://ohhmsby4v.bkt.clouddn.com/image/%E6%82%9F.jpg)

---
## 代码

代码：
```
`code`

```
效果：
>  `code`

---
## 代码块

代码（去空格）：
```
 ` ` `
   code
 ` ` `
```

效果：
```
  code

```

---
## 引用

代码：
```
> 引用文字
>
> > 二级引用文字
>
> 引用文字

```
效果：
> 引用文字
>
> > 二级引用文字
>
> 引用文字

---
## 斜体

代码：
```
*斜体文字*

```
效果：
> *斜体文字*

---
## 粗体

代码：
```
**粗体文字**

```
效果：
> **粗体文字**

---
## 粗斜体

代码：
```
***粗斜体***

```
效果：
> ***粗斜体***

---
## 删除线

代码：
```
~~删除线~~

```
效果：
> ~~删除线~~

---
## 注脚

代码：
```
这是一个注脚[^footnote1]的样例
[^1]: 我就是悟
```
效果：

这是一个注脚[^footnote1]的样例
> [^1]: 我就是悟

---
## 表格(一)

代码：
```
| Tables        | Are            | Cool       |
| -----         | :-----:        | -----:     |
| col 3 is      | right-aligned  | $1600      |
| col 2 is      | center         | $12        |
| zebra stipes  | are neat       | $1         |
```
效果：
> | Tables        | Are            | Cool       |
> | -----         | :-----:        | -----:     |
> | col 3 is      | right-aligned  | $1600      |
> | col 2 is      | center         | $12        |
> | zebra stipes  | are neat       | $1         |

---
## 表格(二)

代码：
```
dog | bird | cat
----|------|-----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz
```
效果：

> dog | bird | cat
> ----|------|-----
> foo | foo  | foo
> bar | bar  | bar
> baz | baz  | baz

---
## 转义

代码：
```
\*悟の迹\*

支持以下符号转义：
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
>   大于号
```
效果：

> \*悟の迹\*

最近访客
<div class="ds-recent-visitors" data-num-items="39" data-avatar-size="40" id="ds-recent-visitors"></div>
