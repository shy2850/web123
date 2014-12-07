HTML
====
超文本 __标记语言__ (Hyper Text Markup Language)

第一讲(4-6课时)
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

第二讲(4-6课时)
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

CSS
===
层叠__样式表__ (Cascading Style Sheets) 

第三讲(4课时)
------------
* CSS基础语法和引入格式  ``/[.#*\s,+:\-\w]+\{([\w-]+\:[^;]+;+)*\}/``
* CSS样式定义   
* CSS定位
* CSS选择器
* IE滤镜基础知识
* IE浏览器使用css表达式引入脚本( expression && behavior )
* #实例( css多级联动菜单 )

第四讲(4-6课时)
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
JavaScript 是一种__轻量级__的编程语言。

第五讲(8课时)
-------------
* ECMAScript    [http://w3school.com.cn/js/pro_js_syntax.asp](http://w3school.com.cn/js/pro_js_syntax.asp)
    * 基本语法 (任何编程语言的基本语法，都是不涉及平台和实际应用功能的)
        * 变量定义和表达式
        * 数值运算、字符串运算、比较运算、逻辑运算等
        * 各种全局对象的显式定义
        * 条件、循环和分支
        * 关键字和保留字
        * JSON
        * [JS秘密花园](http://bonsaiden.github.io/JavaScript-Garden/zh/)
    * [全局对象](http://w3school.com.cn/jsref/index.asp)
    * [全局方法](http://w3school.com.cn/jsref/jsref_obj_global.asp)
    * 面向对象(封装、继承、多态)
    * #实例( 面向对象应用实例 )

第六讲(8课时)
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

jQuery
======
浏览器上面最流行的一套javascript方法库

[wfQuery](https://github.com/shy2850/wfQuery)
