﻿# vue-douban
vue模仿豆瓣
这是基于vue2 + vue-router2 + vuex + axios 仿(豆瓣市集)的一个webapp项目！

### 线上访问地址
https://d-gitlong.github.io/vue-douban/#/


### 项目地址：（`git clone`）

```shell
git clone https://github.com/D-gitlong/vue-douban.git
```

### 安装

```
npm install
```

### 运行

```
npm run dev
```
浏览器输入:(http://localhost:8080)即可看到效果

### 发布

```
npm run build
```

### 技术栈

在此DEMO中使用了一下技术
* vue2
* vue-router2
* vuex
* webpack2
* es6
* axios
* vue-infinite-scroll
* vue-lazyload


### 目录结构

<pre>
.
├── README.md           
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src
│   ├── assets         // css js 和图片资源
│   ├── components     // 各种组件
│   ├── mock           // 模拟数据
│   ├── pages          // 各页面
│   ├── router         // 存放路由的文件夹
│   ├── store	       // 状态管理store
│   ├── App.Vue        // 模板文件入口
│   └── main.js        // Webpack 预编译入口
│	

</pre>
