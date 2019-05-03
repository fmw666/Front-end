<div align="center">
  <h2><a name="head"></a>📖</h2>
</div>  
<div align="center">
  <a href="https://github.com/fmw666/Front-end/blob/master/HTML/README.md#head">HTML(在更)</a> 
  / 
  <a href="https://github.com/fmw666/Front-end/blob/master/CSS/README.md#head">CSS(在更)</a> 
  / 
  <a href="https://github.com/fmw666/Front-end/blob/master/JavaScript/README.md#head">JavaScript(在更)</a> 
  / 
  <a href="#">BootStrap</a> 
  / 
  <a href="#">jQuery</a>
  /
  Animate+WOW
</div>

<br>

# Animate+WOW 指南

>> 文档为作者本人所有，如需要转载请先[联系我](https://github.com/fmw666)，⚡特此说明！
<hr/>

*"Animate.css--一款强大的预设css3动画库，WOW.js--能让页面滚动时显示动画,使页面更有趣。"*

<img src="https://github.com/fmw666/my-image-file/blob/master/images/gif/2.gif" width="100">

🏷Animate 相关网站
 - [官方动画演示网站](https://daneden.github.io/animate.css/)
 - [官方 GitHub](https://github.com/daneden/animate.css)
 - [animate.css 下载](https://raw.githubusercontent.com/daneden/animate.css/master/animate.css)
 
🏷WOW 相关网站
 - [官方演示网站](https://www.delac.io/wow/)
 - [官方 GitHub](https://github.com/matthieua/WOW)
 - [wow.js 下载](https://raw.githubusercontent.com/matthieua/WOW/master/dist/wow.js)

## 引入样式
要在网站中使用 [animate.css](#welcome)，只需将样式表放入 [html](#welcome) 的 [\<head\>](#welcome) 标签中。

```html
<head>
    <!-- 引入Animate的css文件 -->
    <link rel="stylesheet" href="animate.min.css">
</head>
```

要使用 [wow.js](#welcome)，只需在 [html](#welcome) 底部引入 js 文件，并作 `WOW` 的初始化。

```html
<!-- 引入WOW的js文件 -->
<script type="text/javascript" src="js/wow.js"></script>
<!-- 把WOW插件初始化 -->
<script>
    new WOW().init();
</script>
```

## 动画类型
要为元素设置动画，直接在元素的 [class](#welcome) 中添加需要的 [animate](#welcome) 动画类型即可。也可以包含 [infinite](#welcome) 无限循环的 [class](#welcome)。可以添加的 [class](#welcome) 动画有：

|class 名称||||
|:---------|:--|:--|:--|
|bounce|flash|pulse|rubberBand|
|shake|headShake|swing|tada|
|wobble|jello|bounceIn|bounceInDown|
|bounceInLeft|bounceInRight|bounceInUp|bounceOut|
|bounceOutDown|bounceOutLeft|bounceOutRight|bounceOutUp|
|fadeIn|fadeInDown|fadeInDownBig|fadeInLeft|
|fadeInLeftBig|fadeInRight|fadeInRightBig|fadeInUp|
|fadeInUpBig|fadeOut|fadeOutDown|fadeOutDownBig|
|fadeOutLeft|fadeOutLeftBig|fadeOutRight|fadeOutRightBig|
|fadeOutUp|fadeOutUpBig|flipInX|flipInY|
|flipOutX|flipOutY|lightSpeedIn|lightSpeedOut|
|rotateIn|rotateInDownLeft|rotateInDownRight|rotateInUpLeft|
|rotateInUpRight|rotateOut|rotateOutDownLeft|rotateOutDownRight|
|rotateOutUpLeft|rotateOutUpRight|hinge|jackInTheBox|
|rollIn|rollOut|zoomIn|zoomInDown|
|zoomInLeft|zoomInRight|zoomInUp|zoomOut|
|zoomOutDown|zoomOutLeft|zoomOutRight|zoomOutUp|
|slideInDown|slideInLeft|slideInRight|slideInUp|
|slideOutDown|slideOutLeft|slideOutRight|slideOutUp|
|heartBeat|
