#移动端前端实践
----------
>给有前端基础的童鞋们希望接触或者研究移动端的一些东西。

##基础知识
###1.理论知识
>这部分用于基本理论知识，了解手机端开发和pc端屏幕上的区别，熟悉手机上的浏览器。

1.手机端视网膜屏基础
[视网膜New iPad与普通分辨率iPad页面的兼容处理](http://www.zhangxinxu.com/wordpress/2012/10/new-pad-retina-devicepixelratio-css-page/)
[Towards A Retina Web(英)](http://www.smashingmagazine.com/2012/08/20/towards-retina-web/)

2.手机设备分辨率（[点我](http://screensiz.es/phone)）

###2.前端知识
>这部分为移动端使用的一些基本html、css知识。

1.移动端meta

[常用meta整理](http://segmentfault.com/blog/ciaocc/1190000002407912)

2.iconfont
[图标字体化浅谈](http://isux.tencent.com/icon-font.html)
[阿里妈妈矢量字库](http://www.iconfont.cn/)
[Illustrator+FontLab 进行字体设计教程](http://www.jb51.net/Illustrator/24482.html)

3.css3基础
[w3school-css3](http://www.w3school.com.cn/css3/)
[css3-animation](http://www.w3cplus.com/content/css3-animation/)
[css3-transition](http://www.w3cplus.com/content/css3-transition/)

4.css3兼容性!important
[caniuse](http://caniuse.com/)

5.Media Queries
[Media Queries](http://www.w3cplus.com/content/css3-media-queries)

6.移动端事件处理
[移动开发事件](https://github.com/jtyjty99999/mobileTech#%E7%A7%BB%E5%8A%A8%E5%BC%80%E5%8F%91%E4%BA%8B%E4%BB%B6)

7.flex布局
[flex标准](http://www.w3.org/TR/css-flexbox-1/)
[Flexbox——快速布局神器](http://www.w3cplus.com/css3/flexbox-basics.html)

8.移动端调试
[移动端前端开发调试](http://yujiangshui.com/multidevice-frontend-debug/)

###3.移动端进阶
>这部分是一些稍微进阶的东西。。

1.webkit渲染
[How Rendering Work (in WebKit and Blink 中文的)](https://www.zybuluo.com/rogeryi/note/18709)

2.css工作流
[css工作流-一丝](http://yisibl.github.io/share/css-workflow.html#/1)
[postcss](https://github.com/postcss/postcss)&[autoprefixer](https://github.com/postcss/autoprefixer)

3.叶小钗的一些文章。。
[【webapp的优化整理】要做移动前端优化的朋友进来看看吧](http://www.cnblogs.com/yexiaochai/p/3759959.html)
[【移动端兼容问题研究】javascript事件机制详解（涉及移动兼容）](http://www.cnblogs.com/yexiaochai/p/3462657.html)
[浅谈移动前端的最佳实践](http://www.cnblogs.com/yexiaochai/p/4219523.html)

##目前开发模式
>总的来说目前开发模式是前后端未分离，前端通过假数据写好静态页面，调试好后转移到后端平台进行联调

###基础库-only [zepto](http://www.html-5.cn/Manual/Zepto/)
>经历了`jquery mobile` 》`jquery` 》`zepto` ，主要目的为了移动端可怜的性能和网速。目前没有但是希望不过因为找不到暂时还是自己些的ui库。有考虑使用`iscroll`。下个迭代中会尝试使用zepto+fastclick+iscroll

**数据操作和模板引擎使用**--`underscore`

**css后处理使用**--`grunt-autoprefixer`

**字体处理**--`Fontlab Studio`

###基础技术选型
>主要是如何使用一些技术选型实现需求
ps.`》`为降级方案

**基础图标**--`iconfont` 》图片

**基础动画（移动，缩放，旋转等）**--`animation/transition`》`js动画`》`gif`

**基础布局**--个人喜好

>**待补充**