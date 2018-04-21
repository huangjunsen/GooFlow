# GooFlow

一个基于 Jquery/FontAwesome 的流程图/架构图画图插件  

### 版本
V1.0  

### 版权
GPL(GNU GENERAL PUBLIC LICENSE)  
GPL协议最主要的几个原则：  
1、确保软件自始至终都以开放源代码形式发布，保护开发成果不被窃取用作商业发售。任何一套软 件，只要其中使用了受 GPL 协议保护的第三方软件的源程序，并向非开发人员发布时，软件本身也就自动成为受 GPL 保护并且约束的实体。也就是说，此时它必须开放源代码。  
2、GPL 大致就是一个左侧版权（Copyleft，或译为“反版权”、“版权属左”、“版权所无”、“版责”等）的体现。你可以去掉所有原作的版权 信息，只要你保持开源，并且随源代码、二进制版附上 GPL 的许可证就行，让后人可以很明确地得知此软件的授权信息。GPL 精髓就是，只要使软件在完整开源 的情况下，尽可能使使用者得到自由发挥的空间，使软件得到更快更好的发展。  
3、无论软件以何种形式发布，都必须同时附上源代码。例如在 Web 上提供下载，就必须在二进制版本（如果有的话）下载的同一个页面，清楚地提供源代码下载的链接。如果以光盘形式发布，就必须同时附上源文件的光盘。  
4、开发或维护遵循 GPL 协议开发的软件的公司或个人，可以对使用者收取一定的服务费用。但还是一句老话——必须无偿提供软件的完整源代码，不得将源代码与服务做捆绑或任何变相捆绑销售。  
详见：(http://www.oschina.net/question/12_2826)  

### 依赖
* jquery1.11+  
* fontawesome4.4.0+  

### 浏览器支持
* IE9+  
* Firefox (latest)  
* Safari (latest)  
* Chrome (latest)  
* Opera (latest)  
* IE9 不支持CSS变形和动画，此插件的功能都能用，不过，拥有较差的用户体验。  

### 1. 示例
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/01_Example.jpg)  

### 2. 使用方法：
2.1. 添加CSS及JS文件  
```html
<link rel="stylesheet" href="dist/GooFlow.min.css">
<link rel="stylesheet" href="fontawesome/css/font-awesome.min.css">
<script src="dist/jquery.min.js"></script>
<script src="dist/GooFlow.min.js"></script>
```

2.2. 书写容器 Dom   
```html
<div id="demo1"></div> 
```

2.3. 激活/生成：  
```javascript
var demo1 = $('#demo1').createGooFlow(options);
```

  
### 3. 参数(options)：
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option1.jpg)  
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option2.jpg)  
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option3.jpg)  
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option4.jpg)  
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/03_option5.jpg)  

  
### 4. 方法：
提供了多达36个方法，专门为进行二次开发而使用。  
更多内容参见demo.html

  
### 5. 二次开发示例：画架构图
![](https://github.com/huangjunse/GooFlow/raw/master/SnapShot/02_redevelop.jpg)  
  
