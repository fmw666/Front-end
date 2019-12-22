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
  - [1.2](#1.2) **`<!DOCTYPE html>` 声明为 HTML5 文档**
  
    + 🎲 [\<!DOCTYPE\>]((#no-jump)) 声明必须是 HTML 文档的第一行，位于 [\<html\>](#no-jump) 标签之前。
    
    + 🎲 向 HTML 文档添加 [\<!DOCTYPE\>](#no-jump) 声明，这样浏览器才能获知文档类型。
    
    + 🎲 [\<!DOCTYPE\>](#no-jump) 声明没有结束标签，并且对大小写不敏感。
    
    + 🎲 HTML5 中只有一种 [\<!DOCTYPE\>](#no-jump) 声明（在 HTML 4.01 中有三种），即：
      ```sass
      <!DOCTYPE html>
      ```
  
  <a name="1.3"></a>
  - [1.3](#1.3) **`<html>` 元素是 HTML 页面的根元素**
  
    + 🕹 [\<html\>](#no-jump) 与 [\</html\>](#no-jump) 标签限定了文档的开始点和结束点。
    
    + 🕹 它们之间是文档的头部和主体，即 [\<head\>](#no-jump) 和 [\<body\>](#no-jump) 标签里的内容。
    
    <div align="center">
      <img src="https://github.com/fmw666/Python/blob/master/pics/cute-fly-pink.png" width="150">
    </div>