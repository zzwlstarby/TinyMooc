
[![](http://7xlkoc.com1.z0.glb.clouddn.com/LOGO_BIG.png)](http://taoxiaoran.top)

## 关于Maven下载缺失的Jar包以及数据库SQL文件

使用extra目录。

## 萌课(`tinymooc`)是什么?

`tinymooc` 中文名萌课,是一个轻量级Web网站。它拥有简洁的代码,优雅的设计。
萌课网目前打算实现微课程的点播和直播服务，依托于腾讯云强大的云计算服务给用户带去更好的微课学习体验。

如果你喜欢,欢迎 [Star and Fork](https://github.com/lemonjing/tinymooc), 谢谢!

## 演示地址

~~http://119.29.97.92已失效~~ 请换用本地测试

## 部分页面展示

### 个人课程学习情况
![](http://7xlkoc.com1.z0.glb.clouddn.com/tiny%2Fmooc1.jpg)

### 课程分类
![](http://7xlkoc.com1.z0.glb.clouddn.com/tiny%2Fmooc2.jpg)

### 课程和课时
![](http://7xlkoc.com1.z0.glb.clouddn.com/tiny%2Fmooc3.jpg)

### 课程播放（接入腾讯云视频服务）
![](http://7xlkoc.com1.z0.glb.clouddn.com/tiny%2Fmooc4.jpg)

### 推荐页面
![](http://7xlkoc.com1.z0.glb.clouddn.com/tiny%2Fmooc5.jpg)

## 特性

* [x] 轻量级。代码简洁,结构清晰
* [x] 操作简单,界面美观
* [x] 小组,话题,讨论,留言,根本停不下来
* [x] 腾讯云支持的高效视频管理和点播服务
* [x] 多种配置文件支持(当前支持properties、json和硬编码)
* [x] 内置Jetty服务,模板引擎支持
* [x] 支持JDK1.6或者更高版本

## 概述

* 简洁的：Kiss原则实现,操作简单,maven管理。萌课目标让用户在一天内爱上并使用。
* 强大的：`tinymooc` 依托腾讯强大的云计算服务

## 快速入门

开始之前,首先 [Download或Clone本工程](https://github.com/lemonjing/tinymooc) ：

配置`Maven`：

项目已经启用Jetty插件，默认端口8092

```sh
jetty:run
```
运行项目，然后用浏览器打开 http://localhost:8092 这样就可以看到萌课了！

OK，这一切看起来多么的简单，欢迎查看我的其他项目和相关更新:

+ [JavaSE工程](https://github.com/Lemonjing/myjavase)
+ [Leetcode题解](https://github.com/Lemonjing/leetcode)
+ [版本查询](LAST_VERSION.md)
+ [更新日志](UPDATE_LOG.md)

## 计划

- 1. 开发萌课用户管理
- 2. 接入腾讯云视频点播服务
- 3. 接入腾讯云视频直播服务
- 4. 优化并发能力和更好的UI呈现

## 更新日志

[更新日志](https://github.com/Lemonjing/TinyMooc/blob/master/UPDATE_LOG.md)

### 联系我

- WebSite: [http://taoxiaoran.top][1]
- Mail: xmusaber@163.com
- Linux交流群: [257265338][2]
- 开源技术小组: [521087632][3]

作者 [微博@风屿alter][4]     
2015 年 11月 15日

## 开源协议

```
Copyright 2015 lemonjing

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[1]: http://taoxiaoran.top 
[2]: http://jq.qq.com/?_wv=1027&k=ZKsbKb
[3]: http://jq.qq.com/?_wv=1027&k=26Y8BYN
[4]: http://weibo.com/u/1662536394
