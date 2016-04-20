# GooFlow
============

一个基于 Jquery/FontAwesome 的流程图/架构图画图插件<br>

###版本
V1.0<br>

###依赖
* jquery1.11+<br>
* fontawesome4.4.0+<br>

###浏览器支持
* IE9+<br>
* Firefox (latest)<br>
* Safari (latest)<br>
* Chrome (latest)<br>
* Opera (latest)<br>
* IE9 不支持CSS变形和动画，此插件的功能都能用，不过，拥有较差的用户体验。<br>

###1. 示例
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/01_Example.jpg)<br>

###2. 使用方法：
2.1. 添加CSS及JS文件<br>
>```html
<link rel="stylesheet" href="dist/GooFlow.min.css">
<link rel="stylesheet" href="fontawesome/css/font-awesome.min.css">
<script src="dist/jquery.min.js"></script>
<script src="dist/GooFlow.min.js"></script>
```

2.2. 书写容器 Dom <br>
>```html
<div id="demo1"></div>
```

2.3. 激活/生成：<br>
>```javascript
var demo1 = $('#demo1').createGooFlow(options);
```

<br>
###3. 参数(options)：
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option1.jpg)<br>
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option2.jpg)<br>
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option3.jpg)<br>
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option4.jpg)<br>
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option5.jpg)<br>

<br>
###3.js方法：
提供了多达36个方法，专门为进行二次开发而使用。<br>

<br>
###5. 二次开发示例：画架构图
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/02_redevelop.jpg)<br>
<br>