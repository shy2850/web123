HTML
====
超文本 __标记语言__ (Hyper Text Markup Language)

第一讲(6课时)
-------------
* HTML基础结构
* HTML标签    ``/<(\w+)>(.*?)(<\/\1>)?/``
    * 常用标签
    * 布局标签
    * 表单标签
* HTML属性    ``/<(\w+)\s*([\w-]+\="[^"]*"\s*)*>(.*?)(<\/\1>)?/i``
    * 4个通用属性
    * 表单标签属性
    * 特殊功能属性
    * 自定义属性
* HTML[实体](http://w3school.com.cn/tags/html_ref_entities.html)、[符号](http://w3school.com.cn/tags/html_ref_symbols.html)
* XHTML和HTML    ``/<(\w+)\s*([\w-]+\="[^"]*"\s*)*>(.*?)(<\/\1>)/``
    * no html, but xhtml
    * HTML验证: [http://validator.w3.org/](http://validator.w3.org/)
* HTML和XML      ``/<([:\w\-]+)>(.*?)(<\/\1>)/``
    * 从超文本的标记 到 可扩展标记语言
    * 可以做网页的 __数据传输格式__ ( ? )

第二讲(6课时)
-------------
* HTML之"偷懒的HTML-coder"
    * zencoding/emmet
    * markdown
    * jade
    * Server Page (JSP/ASP/PHP)
* HTML的"旅行"
    * 从服务端创建到客户端展现的过程
    * [HTTP Code](http://w3school.com.cn/tags/html_ref_httpmessages.asp)
    * GET & POST
    * [URL编码](http://w3school.com.cn/tags/html_ref_urlencode.html)
    * 浏览器工作原理

CSS
===
层叠__样式表__ (Cascading Style Sheets) 

第三讲(4课时)
------------
* CSS基础语法和引入格式  ``/[.#*\s,+:\-\w]+\{([\w-]+\:[^;]+;+)*\}/``
* CSS样式定义   
* CSS定位
* CSS选择器
* CSS层叠次序和优先级
* IE滤镜基础知识
* IE浏览器使用css表达式引入脚本( expression && behavior )
* #实例( css多级联动菜单 )

第四讲(8课时)
---------------
* 更多的CSS功能: CSS3
    * 扩展选择器
    * media-query
    * transform
    * animation
* CSS关联HTML优化验证: [http://jigsaw.w3.org/css-validator/](http://jigsaw.w3.org/css-validator/)
* LESS、SASS
* 压缩, 编码
* #实例( 响应式动态页面 )


JavaScript
==========
JavaScript 是一种__轻量级__的__编程语言__。

第五讲(12课时)
-------------
* ECMAScript    [http://w3school.com.cn/js/pro_js_syntax.asp](http://w3school.com.cn/js/pro_js_syntax.asp)
    * 基本语法 (任何编程语言的基本语法，都是不涉及平台和实际应用功能的)
        * 变量定义和表达式
        * 数值运算、字符串运算、比较运算、逻辑运算等
        * 各种全局对象的显式定义
        * 条件、循环和分支
        * 递归典型案例以及实现要素( 结束标志 + 可递归算法 )
        * 关键字和保留字
        * #练习( [简单排序算法的原理及实现](http://runjs.cn/detail/m1pgexjv) )
        * JSON
        * [JS秘密花园](http://bonsaiden.github.io/JavaScript-Garden/zh/)
    * [全局对象](http://w3school.com.cn/jsref/index.asp)
    * [全局方法](http://w3school.com.cn/jsref/jsref_obj_global.asp)
    * 面向对象(封装、继承、多态)
    * #实例( 面向对象应用实例 )

第六讲(12课时)
-------------
* BOM
    * Window
    * Navigator
    * Screen
    * History
    * Location
* HTML-DOM && XML-DOM
    * DOM的选择,获取,遍历 (扩展了解:xPath/xQuery)
    * DOM操作: 删除、创建、克隆、替换、改变、添加
    * XML-DOM对象属性的继承( 浏览器差异 )
    * HttpRequest
    * DOM的attributes操作
    * HTML-DOM的css操作
* 浏览器javascript加载/执行基本特点
* #练习( [星级评分☆☆☆☆☆](http://runjs.cn/detail/evsimdcq) )
* #练习( [模拟下拉框](http://runjs.cn/detail/evsimdcq) )
* #实例( [windows计算器](http://runjs.cn/detail/0wgck9pa) )

jQuery
======
浏览器上面最流行的一套javascript方法库

第七讲(8课时)
------------
* jQuery对象
* jQuery的类扩展和原型扩展
* [Sizzle(jQuery选择器)](http://w3school.com.cn/jquery/jquery_ref_selectors.asp)
* jQuery事件绑定和事件代理的实现原理和注意事项
*【this】和【$(this)】
* jQuery的属性操作、css操作 && data数据绑定
* jQuery.ajax
* jQuery.fn.animate
* jQuery基本实现原理讲解 [wfQuery](https://github.com/shy2850/wfQuery)
* #实例( [简单俄罗斯方块](http://runjs.cn/detail/h05vfmrb) )
* #扩展( [基于jQuery的表单验证](http://shy2850.github.io/wfQuery/demo/7.formValid.html) )

nodejs
========
第八讲(12课时)
--------------
* 服务端开发和前端开发差异
* nodejs 环境安装测试
* nodejs 模块查询规范
* npm 常用操作
* 常用nodejs模块
* 发布自己的包到npm仓库
* 构建自己的node服务器: [f2e-server](https://github.com/shy2850/node-server)


模块化和构建
======
第九讲(6课时)
-------------
* 什么是模块化? 为什么需要模块化。
* nodejs的CMD && requirejs的AMD。
* 前端构建解决那些问题？
* 工具化/流程化的前端构建。



============
SVG & canvas
============
第十讲(12课时) 【待定】
--------------
* SVG: 使用 XML 格式定义图形
* canvas vs SVG
* SVG / canvas 在低端浏览器的替代应用
    * [Raphsel.js](http://raphaeljs.com/) ( SVG & VML 兼容类库)
    * [Zrender.js](http://ecomfe.github.io/zrender/) ( canvas & xcanvas 兼容类库 )
