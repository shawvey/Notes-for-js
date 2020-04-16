#### 当前阅读进度

✅ 第1章 JavaScript简介

✅ 第2章 在HTML中使用JavaScript

✅ 第3章 基本概念

✅ 第4章 变量、作用域和内存问题

✅ 第5章 引用类型

✅ 第6章 面向对象的程序设计

✅ 第7章 函数表达式

✅ 第8章 BOM

✅ 第9章 客户端检测

🎯 第10章 DOM



#### 如何阅读高程书❓

1. 1-5章是语言基础知识，难度小，但是是后面阅读的根基。
2. 4,6,7章是讲解作用域链、JavaScript面向对象、原型-构造函数机制、闭包等该记概念，是JavaScript这门语言的精华（或者说核心）所在，是需要反复咀嚼和理解的难点。

3. BOM、DOM、事件这几章的知识是真正开发中用的最多的部分
4. 如果暂时没有项目需求，XML、Canvas、表单脚本、离线与存储这几章可以押后
5. Ajax这张光阅读和记住是没用的，需要切切实实去实践
6. 高级技巧、最佳实践、新兴API这几章则是掌握好基础之后提升代码质量、改善应用体验的提升之路



#### 几个针对性的小建议🤥：

1. 面向对象的程序设计、函数表达式

   这两部分是JavaScript实现OOP的根基，构造函数用于实例化，原型链用于实现继承，闭包用于实现私有变量（私有成员）。

   如果读完还是无法了解OOP，建议先去看强OOP语言（如：Java）的相关书籍相关章节（例如：《Java核心技术卷1》1-5章），再回过头尝试JavaScript的OOP时便觉得柳暗花明，茅塞顿开。

   而闭包也是你以后将接触到的模块化里处处提及的一个重要概念，如果闭包那一节没法参透，建议再回过头把第四章函数运行的机制给完全弄懂再研究。

   当理解了这些之后，可以自己实现一段JavaScript OOP的snippet了（例如：[一段讲解使用 JS 实现 OOP 的代码实例](https://gist.github.com/yangfch3/24d0eb5293088824d25df4e26856b88d)

2. Ajax

   这一章的学习需要切实地去实践，这里推荐几种数据来源的思路：

   - 可以使用GitHub、和风天气、有道词典这些数据接口进行练习，以及第三方的知乎API（GitHub上一搜一大把）进行练习
   - 也可以使用Mock.js这些拦截Ajax的库进行假数据的请求模拟
   - 如果需要练习Ajax上传操作可以去Google相关公共API或者提问一起探讨

   然后可以自己尝试封装一个Ajax生成器[ajax 请求封装](https://gist.github.com/yangfch3/4ca039fbaa492b1061a22fdbef4ab367)

   至于跨域，大家说是安全限制，你也整天念叨安全限制，那么跨域到底安全问题在哪里？边看边思考，边扩展找资料，这样知识体系才会完整、稳固。

src: [你是怎么看完《JavaScript权威指南》《JavaScript高级程序设计》等这类厚书的?](https://www.zhihu.com/question/32039257/answer/186719859)