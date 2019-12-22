<div align="center">
  <h2><a name="head"></a>📖</h2>
</div>  
<div align="center">
  <a href="https://github.com/fmw666/Front-end/blob/master/HTML/README.md#head">HTML</a> 
  / 
  CSS
  / 
  <a href="https://github.com/fmw666/Front-end/blob/master/JavaScript/README.md#head">JavaScript</a> 
  /
  <a href="https://github.com/fmw666/Front-end/blob/master/Semantic-UI/README.md#head">Semantic-UI</a>
  /
  <a href="https://github.com/fmw666/Front-end/blob/master/jQuery/README.md#head">jQuery</a>
  / 
  <a href="https://github.com/fmw666/Front-end/blob/master/Bootstrap/README.md#head">Bootstrap</a> 
  /
  <a href="https://github.com/fmw666/Front-end/blob/master/Animate%2BWOW/README.md#head">Animate+WOW</a>
</div>

<br>

# CSS 指南

>> 文档为本人所有，如需要转载请先[联系我](https://github.com/fmw666)，⚡特此说明！
<hr/>

*"CSS(Cascading Style Sheets)--层叠样式表，一种用来表现 HTML 或 XML 等文件样式的计算机语言。"*

<img src="../HTML/pics/cute.jpg" width="100">

🏷CSS学习参考网站
 - [30秒 CSS 中文版](http://caibaojian.com/30-seconds-of-css/)
 - [HTML中文网--CSS 教程手册](https://www.html.cn/book/css/)
 - [CSS 中文参考文档](http://css.cuishifeng.cn/)

## 目录

1. [在网页中添加样式](#在网页中添加样式)
1. [xx](#xx)

## 在网页中添加样式

> 共有三种方式在网页中添加样式的方式。

<a name="1.1"></a>
  - [1.1](#1.1) **直接把样式信息嵌入到标签元素**
  
    ```css
    <h1 style="color: green">样式信息使我变绿</h1>
    ```

    + 🎲 直接使用标签元素的 [style](#no-jump) 属性来进行样式信息描述

    + 🎲 这种方法非常方便，但是会令整个 html 文档杂乱无章，一个样式只能适用于一个标签元素。
    
  <a name="1.2"></a>
  - [1.2](#1.2) **全部样式嵌入到 `<style>` 元素**
  
    ```css
    <head>
		<title>style 元素嵌入样式</title>
		<style>
			...
			h1 {
				color: green;
			}
			...
		</style>
    </head>
    ```
        
    + 📚 这种方式样式和标记能分开，但是最终它们还是在一个文件里。
    
    + 🎲 这种方式仅适用于一次性简单测试 demo 网页。
    
    + 🎲 这种方式并不提倡，因为会使代码页面冗余繁杂。
  
  <a name="1.3"></a>
  - [1.3](#1.3) **使用 `<link>` 元素在 `<head>` 部分链接外部样式表文件**
  
	```css
	<head>
		<title>link 链接外部样式表文件</title>
		<link rel="stylesheet" href="demo.css">
	</head>
	```
    
    + 🕹 它们之间是文档的头部和主体，即 [\<head\>](#no-jump) 和 [\<body\>](#no-jump) 标签里的内容。
    
    