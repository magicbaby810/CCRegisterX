# CCRegisterX

https://github.com/luckybilly/CC/issues/197 
建议大家别折腾cc插件了，直接去掉把，它的作用也没那么大。

fork自[CC路由的cc-register](https://github.com/luckybilly/CC/tree/master/cc-register)

因大佬暂时不更新此插件，而项目gradle版本升级后，出现插件报错的问题。所以就踩在大佬的肩膀上，继续优化升级此插件。
### 使用
`classpath 'com.billy.android:cc-register:1.1.2'` 替换为 `classpath 'com.github.magicbaby810:CCRegisterX:0.1.2'`
### 排除jar包
在 cc-settings-2.gradle 文件内增加（判断条件是包含关系）

`ccregister.excludeJarNames = [ 'xxx1.jar','xxx2.jar' ]`

## v0.1.2
1. 支持最高gradle 7.5和gradle plugin 7.4.0
2. 增加排除jar包的配置项
