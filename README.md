# Javascript的执行环境

javascript有一个天然的执行环境--浏览器.但是更多的时候我们使用node.js作为执行环境.js的标准在各个平台实现往往并不同步.
为了保证代码可以在更广的平台上执行,通常我们是先用高级语法写源代码,再通过工具将源代码编译为低级语法的执行代码.而最常见的编译工具就是babel了.

当然了Js也有几个很有人气的方言,coffeescript,以及typescript,他们都各有特点,但本文不会介绍.

本章内容:

+ Javascript执行环境
+ 代码风格
+ api文档自动生成
+ 代码测试工具
+ log工具
+ 性能基准测试