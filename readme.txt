解决的问题：
在用EF6开发的时候，将db table reverse to code的工具是ef power tools，但它不能选择指定的表，而是全库生成，很不友好。
特开发该工具解决之。

原理：
提取ef power tools的源码中reverse的核心代码，改造一下。

备注：
因为该源码只能在vs2015 update3且还需要安装ef powertools插件时才能便宜，所以就没上传源码了。