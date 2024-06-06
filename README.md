# jmg for Godzilla
Godzilla插件|内存马|Suo5内存代理｜jmg for Godzilla

得益于`pen4uin`的jmg项目开源，可以把payload生成功能集成到插件中了，相比复制过来执行简化了操作

jMG： https://github.com/pen4uin/java-memshell-generator-release

```
支持注入工具："Behinder", "Godzilla", "AntSword", "Suo5", "NeoreGeorg"

支持中间件："Tomcat", "SpringMVC", "Weblogic", "Websphere", "Resin", "Undertow", "Jetty", "JBoss", "Glassfish"

支持注入类型："Listener", "Filter", "Interceptor"
```

部分测试：
```
中间件：Jetty
注入工具：Godzilla 内存马
注入类型：Filter
```
<img width="1012" alt="image" src="https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/7a898df8-29f9-498b-8035-2a98bc7e5efa">

```
中间件：Jetty
注入工具：Suo5 内存代理
注入类型：Filter
```
<img width="1103" alt="image" src="https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/cec48da0-db3f-41dc-a78f-e536eb93c331">

```
中间件：Tomcat
注入工具：Godzilla 内存马
注入类型：Listener
```
<img width="1174" alt="image" src="https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/ea7911bc-591a-4fec-8ea5-d9d95c4db198">

```
中间件：Tomcat
注入工具：Godzilla 内存马
注入类型：Filter
```
<img width="1259" alt="image" src="https://github.com/1ucky7/GodzillaPluge-codeExec/assets/145323730/7dc9efcb-4686-47cd-aec0-0527ee52e3d7">

作者是懒b，简单测试了一下，插件本身就是jmg做了一下适配，感谢`pen4uin`师傅的开源

**免责声明**

该工具仅适用于在授权环境/测试环境进行使用，请勿用于生产环境。


