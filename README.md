
# AIM 即时通讯

> 这是一个完整的即时通讯 APP web 版本。vue-socket.io master分支为 2.0 版本，原来的 1.0 版本请查看分支： old-code-example。
>包括一个web应用，以及一个服务端。前端部分用用socket.io-client 和 vue.js 完成，代码简单易懂。前端显示部分为高仿 腾讯TIM。服务端用 Node.js 和 socket.io-server 完成。

## 项目地址
克隆代码：https://github.com/beautifulBoys/vue-socket.io.git

1.0 版本代码：https://github.com/beautifulBoys/vue-socket.io/tree/old-code-example

2.0 版本代码：https://github.com/beautifulBoys/vue-socket.io

## 写在前面

  本项目是一个即时聊天系统。包括一个前端页面和一个服务端；通过该项目的学习，可以大致了解即时通讯的原理及使用。

  本项目会长期不定时完善，在后期会逐步实现 80% 腾讯 TIM 的功能。目前只实现了一部分最主要的聊天的功能，包括一对一聊天，群组聊天，机器人聊天等，其他的坑在未来一定会慢慢补上。

  前端变化莫测，学无止境。作者本人也在通过学习不断巩固和提高。如果你有极客精神，我们不妨一起进步。

## 技术栈
前端：vue: 2.5 + vuex: 3.0 + vue-router + socket.io-client: 2.0

服务端：node：8.0 + express: 4.1 + mongoose: 4.1 + nodemon: 1.1 + socket.io: 2.0

## 项目在线预览
1.0 版本

[请移步查看](https://github.com/beautifulBoys/vue-socket.io/tree/old-code-example)

2.0 版本

[点击访问](http://47.95.212.47:8888/pc/vue-socket/index.html#/)

[备用地址](https://beautifulboys.github.io/pc/vue-socket/index.html#/)

## 其他说明
本项目共用另一个个人项目：[【旅游圈】](https://github.com/beautifulBoys/tourism-circle) 的账号体系。如没有账号，请先去注册,旅游圈账号体系为首次登录自动创建账号。
或者使用以下账号查看
账号：体验账号  密码：123456
账号：李鑫      密码：123123

## 项目图片预览

<img src="https://raw.githubusercontent.com/beautifulBoys/vue-socket.io/master/source/images/1.png" />
<img src="https://raw.githubusercontent.com/beautifulBoys/vue-socket.io/master/source/images/2.png" />
<img src="https://raw.githubusercontent.com/beautifulBoys/vue-socket.io/master/source/images/3.png"/>
<img src="https://raw.githubusercontent.com/beautifulBoys/vue-socket.io/master/source/images/4.png"/>
<img src="https://raw.githubusercontent.com/beautifulBoys/vue-socket.io/master/source/images/5.png"/>

## 功能实现概况
- [x] 账号登录 --- 完成
- [x] 一对一聊天 --- 完成
- [x] 群组聊天 --- 完成
- [x] 机器人聊天 --- 完成
- [x] 窗口随意拖动 --- 完成
- [ ] 窗体大小拖拉 --- 未全部完成
- [ ] 聊天表情 --- 未完成
- [ ] 聊天配置 --- 未完成
- [ ] 屏幕抖动 --- 未完成
- [ ] 发送地理位置 --- 未完成
- [ ] 发送图片 --- 未完成
- [ ] 窗口的最大化、最小化 --- 未完成
- [ ] 窗口的关闭 --- 未完成
- [ ] 右键菜单功能 --- 未完成
- [ ] 新建群组功能 --- 未完成
- [ ] 自动回收废弃群组 --- 未完成
- [ ] 群组信息留存数据库 --- 未完成
- [ ] 添加好友 --- 未完成
- [ ] 账号功能设置 --- 未完成

## 项目安装及运行

``` bash
# 项目安装
client：client目录下：npm install
server：server目录下：npm install

# 项目运行
client：client目录下：npm run dev & npm run start & npm start
server：server目录下：npm start

# 项目查看：
浏览器：http://localhost:8080/#/

# 服务端说明
 因为这是一个完整的项目，所以需要连接数据库。本项目采用 mongoDb 数据库（非关系型数据库）。
 mongoDb 官网：https://www.mongodb.com/
```

## 如果项目中碰到其他问题不能解决，欢迎向我发邮件（1298947916@qq.com）或者 issues 提问。
