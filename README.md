
##《[一步步搭建物联网系统](http://designiot.phodal.com/)》

在线查看[一步步搭建物联网系统](http://designiot.phodal.com/)

A Document by [Phodal](http://www.phodal.com) & IoT Future Group

##如何编辑

你可能需要一点markdown的知识，别担心这货很简单。

###关于目录

编辑相关的目录

 - src/ 目录下放的是文档相关的markdown
 - src/pre 相当于一些书的前言及简介部分
 - images/ 目录下放的是相应的图片
 
生成文档相关的目录
 
 - template/ 里面放有latex及html的模板
 - build/ 生成PDF版的内容，以及一份毕业设计
 - end/ 毕业设计所在目录
 - css/ html版的css

###其他文件

 - index.html 你懂的
 - Makefile 一个简单的make
 - README.md github上显示的内容。
 - License.md 协议相关
 - CNAME 域名的CNAME
 
##如何编译

如果你不是在类Unix平台上的话——说的是Windows，编译可能会很困难。

###编译所需要的软件

大致有下面三个

 - latex
 - pandoc
 - make
 
如果不需要生成pdf版，就不需要latex。
  
###编译命令
 
只需要在目录执行
 
    make

##源码相关

代码

- HTTP版 [https://github.com/gmszone/iot](https://github.com/gmszone/iot)
- CoAP版 [https://github.com/gmszone/iot-coap](https://github.com/gmszone/iot-coap)

测试网站

- HTTP版 [http://b.phodal.com](http://b.phodal.com)
- CoAP版 [coap://iot-coap.phodal.com](coap://iot-coap.phodal.com) (ps:Firefox下用Copper插件)

## License

© 2014 [Phodal Huang](http://www.phodal.com). This code is distributed under the GNU/GPL license.
