# grunt-demo

## 本示例目标

这是一份帮助你学习 Grunt 的项目示例代码。仅仅是一份参考，毕竟它运用到正式的项目过。请根据自己的项目对其进行修改。

## 学习的前提

* 了解 Grunt 是做什么用的；
* 了解什么是前端项目的构建，什么是静态文件的打包。

## 构建目标

* 图片优化，雪碧图，图片hash戳；
* sass编译，css压缩合并，css文件hash戳；
* js检错，requirejs打包，js压缩合并，js文件hash戳。

## 示例依赖

* RequireJs
* Sass

## 目录结构与说明

``` bash
└─ src/               # 开发目录
    ├─ html/          # 存放 html 的目录
        ├─ app/       # 可提取复用的页面模块
        └─ page/      # 各页面入口文件
    ├─ images/        # 存放图片的目录
        ├─ single/    # 不需要合并的图片
        └─ sprite/    # 需要合并的图片
    ├─ js/            # 存放 js 的目录
        ├─ app/       # 可提取复用的脚步模块
        ├─ lib/       # 第三方 js 库
        ├─ page/      # 各页面入口脚本文件
        └─ config.js  # RequireJs 的配置文件
    └─ sass/          # 存放 sass 的目录
        ├─ app/       # 可提取复用的样式模块
        └─ page/      # 各页面入口样式文件
```

## 1. 安装 NPM

首先，别忘记安装 ``npm``，一切都是基于它之上进行玩转。

``` bash
$ npm install
```

## 2. 运行命令

运行开发命令：

``` bash
$ grunt dev
```

打包上线命令：

``` bash
$ grunt release
```

## 3. 查看源代码

了解该示例如何实现，根据自身项目需求对其进行更改。
