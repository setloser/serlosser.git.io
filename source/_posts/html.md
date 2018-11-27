---
title: Html基础
date: 2018-11-27 15:14:42
tags: -web前端
---

## HTML基础
### HTML5声名
	<!DOCTYPE html></html>
### HTML文档可见标签
	<body></body>
<!--more-->
### HTML标题
```
<h1></h1>	一级标题
<h2></h2>	二级标题
<h3></h3>	三级标题
<h4></h4>	四级标题
<h5></h5>	五级标题
<h6></h6>	六级标题
```
### HTML段落
```
<p></p>		使用该标签换行
```
### HTML链接
```
<a href="https://www.setloser.com">梦舞银雪的博客</a>
```
### HTML图像
```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
### HTML按钮
```
<button></button>	按钮标签
（不常用一般以其余标签模拟如：input/a/span等标签居多）
```
### HTML列表
```
无序列表:
<ul>
  <li><?li>
</ul>、
有序列表:
<ol>
  <li></li>
</ol>
```
## HTML元素
HTML标签有开始和结束标签
```
<标记名>内容放在这里...... < /标记名>
```
完整的HTML实例
```
<!DOCTYPE html>
<html>
<body>

<h1>完整的HTML实例h1</h1>
<p>完整的HTML实例p</p>

</body>
</html>
```
<strong>注意：</strong>一些HTML元素将正确显示，即使你忘记了结束标签
### HTML换行标签
```
<br>是一个没有结束标记（在一个空元素<br>标签定义换行）。
```
<strong>注意：</strong>HTML5不需要空元素被关闭。但是如果你想严格的验证，或者如果你需要让你的文档通过读取XML解析器，你必须正确地关闭所有的HTML元素。