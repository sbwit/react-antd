# react-antd(新版后台很快就与大家见面了)
[![React Native](https://img.shields.io/badge/react-^15.3.2-brightgreen.svg?style=flat-square)](https://github.com/facebook/react)
[![Redux](https://img.shields.io/badge/redux-^4.4.5-yellowgreen.svg?style=flat-square)](https://github.com/reactjs/redux)
[![Redux Immutablejs](https://img.shields.io/badge/immutablejs-^0.0.8-orange.svg?style=flat-square)](https://github.com/indexiatech/redux-immutablejs)
[![Ant Design](https://img.shields.io/badge/ant--design-^2.7.2-yellowgreen.svg?style=flat-square)](https://github.com/ant-design/ant-design)

[![MIT](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](http://opensource.org/licenses/MIT)

## 最新更新
>  webpack版本升级2，同时引入Yarn缓存下载的每个包以及happypack利用了多进程，同时还利用缓存来使得rebuild 更快等

>  Redux使用调整

> 路由模式更改为浏览器模式

## 前言
>  本工程主要基于react + redux + immutable + less + ES6/7 + webpack2.0 + fetch + react-router + antd(1.x)实现的SPA后台管理系统模板。

>  如果觉得不错的话，请star一下吧 😊

>  编码时间：8:00——9:30, 下班时间——24:00，其他时间要工作。代码未优化，处女座代码必须要优化。由于代码延后，先向大家说声抱歉。您有什么问题可以私信我segmentfault。

[线上demo](http://antd.sosout.com/)

## 关于我自己
>  使用技术： react + redux + immutable + less + ES6/7 + webpack2.0 + fetch + react-router + antd(1.x)

>  项目说明： 此项目是本人空余时间搭建的。希望大家提供宝贵的意见和建议，谢谢。

>  邮&emsp;&emsp;箱： sosout@yeah.net

>  个人网站： http://www.sosout.com/

>  个人博客： http://blog.sosout.com/

>  个人简书： http://www.jianshu.com/users/23b9a23b8849/latest_articles

>  segmentfault：https://segmentfault.com/u/sosout

### 下载

```
# git clone

git clone https://github.com/sosout/react-antd.git

cd react-antd
```

### 安装
```bush

// 安装前请先确保已安装node和npm

// 安装成功后,再安装依赖，如果之前有用npm安装过，请先删掉node_modules
yarn install
```
### 运行
```bush
yarn run dev （正常编译模式，注意：index.html里必须手动引用app.css，<link href="/antd/dist/app.css" rel="stylesheet" />，否则没有样式）

yarn run hot （热替换编译模式，注意：热替换模式下index.html里去掉引用app.css）
  
yarn run dist （发布生产版本，对代码进行混淆压缩，提取公共代码，分离css文件）
```

### 访问
在浏览器地址栏输入[http://127.0.0.1:8888](http://127.0.0.1:8888)

### 目标功能
- [x] 登录页面
- [x] 全站布局
- [x] 全站路由
- [ ] 对接接口，优化代码(冗余代码，不规则写法，界面样式)
- [ ] 后台系统常用场景会逐个完善

####历史更新
  *2017.02.20*

  	1. 初始化项目目录;

  	2. webpack版本升级(webpack2.0)，并加上yarn，happypack等(最新迭代)；

  	3. 登录退出;

  	4. 整体布局;

  	5. 菜单映射路由(路由模式更改为浏览器模式);
