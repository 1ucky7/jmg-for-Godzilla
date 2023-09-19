# GodzillaPluge-codeExec
Godzilla插件|内存马|Suo5内存代理

   之前写了一个注入suo5的哥斯拉插件，在适配其他中间件的时候遇到一些问题，后面看到`pen4uin`师傅写了一个生成各种马以及suo5代理的工具（https://github.com/pen4uin/java-memshell-generator-release），于是直接给哥斯拉加了一个接口执行代码，方便注入其他管理工具内存马，或注入内存代理。

eg：

生成base64格式的注入器直接执行即可

`java-memshell-generator-release最新版本Suo5生成代码有bug，会把网站打崩，请自己写加载器或等待pen4uin师傅更新后使用`

![图片](https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/3ca837b0-cd5d-4b91-a228-7023175393d5)


可以看到filter已经打上了，且代理连接成功

![图片](https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/2c6a6b48-566f-44f6-83d1-fbab4f39977f)


![图片](https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/1482cf04-4fd0-495d-83c5-cab38abeadb6)

**免责声明**
该工具仅适用于在授权环境/测试环境进行使用，请勿用于生产环境。
