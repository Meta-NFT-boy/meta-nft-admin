# Meta元宇宙 NFT藏品 后台管理系统源码 Meta-Admin

## 支持系统
[元宇宙NFT藏品 前端H5+APP源码 Meta-APP](https://github.com/Meta-NFT-boy/meta-nft-app)

[元宇宙NFT藏品 服务端系统源码 Meta-Server](https://github.com/Meta-NFT-boy/meta-nft-server)


**效果演示**

- [效果演示地址](http://permission.aimdream.com)

**分支说明：**

**master**：前后端统一开发的版本；用nodejs + express + mongodb或者MySql；

**dev**：进行了前后端分离的版本；用户只关注于前端部分，可忽略服务端；下载下来，即可运行；

**dev-permission**：<b color="#87DE75">增加了权限管理(包括页面权限和按钮权限)的功能和顶栏三级菜单显示，完全剥离nodejs后台。</b>

## 提示
<p style="display:flex;align-items:center;">
 如果你觉得该项目对你有帮忙，可以联系我!</p>

## About

本文主要提及项目基础信息：

```bash
  如果对您对此项目有兴趣，可以联系我! 谢谢！ ^_^
   
  开发环境 windows/Mac 、node js 
  
  如有问题请直接联系我们，或者您发现问题并有非常好的解决方案，欢迎提出
```

## 技术栈

**前端技术栈：** vue2 + vuex + vue-router + webpack + ES6/7 + element-ui + Ant Design UI

**服务端技术栈：**  MySQL + Redis

## 参考文档

- [vue](https://vuejs.bootcss.com/v2/guide/)：Vue是一套用于构建用户界面的渐进式框架。

- [vuex](https://vuex.vuejs.org/zh/)：Vuex 是一个专为 Vue.js 应用程序开发的状态管理模式。
 
- [vue-router](https://router.vuejs.org/zh/)：Vue Router 是 Vue.js 官方的路由管理器。
 
- [webpack](https://webpack.js.org/concepts/)：前端模块打包器。
 
- [less](http://lesscss.cn/)：Less 是一门 CSS 预处理语言，它扩展了 CSS 语言，增加了变量、Mixin、函数等特性，使 CSS 更易维护和扩展。
 
- [element-ui](https://element.eleme.io/)：Element,一套为开发者、设计师和产品经理准备的基于 Vue 2.0 的桌面端组件库。
 
- [Ant Design UI](https://ant.design/index-cn)：为Web 应用提供了丰富的基础UI 组件


## 前序准备

**运行前准备：**

   由于此项目是基于node js的前后端结合项目，你需要进行node js的相关准备工作。项目运行之前，请确保系统已经安装以下应用：
   
   (1)、node (16.0 及以上版本)。使用细节，请参考：[node的下载及安装。](https://nodejs.org/en/download/)
        

## 开发：
1. git clone ……

1. cd ……
 
1. npm install

**本地运行：**

**npm run serve** 运行之后，会默认打开本地访问路径：http://localhost:8868

**发布：**

**npm run bulid** (生成打包之后的项目文件,此文件主要用于项目部署)。

## 演示
## 
测试账号:
1. username: admin / password: 654321
2. username: editor / password: 654321

注意：

admin：拥有最高权限，可以查看所有的页面和按钮；

editor：只有被赋予权限的页面和按钮才可以看到；


## [查看更多demo](http://permission.aimdream.com)



## 技术答疑，项目交流
欢迎联系我们：

QQ：287145101

微信：huniuoo

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-admin/blob/main/static/weichat.png">


# 前端支持功能：

> 深、浅两种皮肤可供配置

> 用户中心相关
- [x] 用户互关、藏品收藏
- [x] 用户分享->邀请->奖励完整逻辑
- [x] 用户签到->奖励
- [x] ……

> 支付和安全
- [x] KYC实名
- [x] 绑定银行卡
- [x] 提现申请
- [x] 充值
- [x] 流水记录
- [x] 订单、支付管理
- [x] ……
> 藏品相关
- [x] 赠与管理
- [x] 藏品秒杀购买
1. 最大程度防科学/科技抢购
2. 保证高并发下的用户抢购体验
3. 15分钟内未支付，将重新释放库存，XX分钟后可再捡漏购买
4. ……
- [x] 藏品盲盒
保证概率控制

- [x] 藏品空投（抽签）
保证概率控制
- [x] 更多……

完整整站功能，不一一罗列

# 区块链相关：

另外的服务程序介绍

# 后台支持功能：

> 用户管理

- [x] 用户信息管理
- [x] 用户钱包管理
- [x] 银行卡管理（记录、审核）
- [x] KYC实名认证（记录、审核）
- [x] 用户关注

> 交易充提
- [x] 充值管理（记录、审核、自动对账）
- [x] 提现管理（记录、审核、自动对账）
- [x] 交易流水（自动对账）

> NFT藏品
- [x] NFT藏品管理（藏品上下架）
- [x] 购买黑白名单（过滤设置、优先购买）
- [x] 藏品创造者
- [x] 用户喜欢的藏品

> 藏品流转
- [x] 藏品订单管理
- [x] 藏品流转记录
- [x] 赠与管理
- [x] 用户拥有藏品

> 用户邀请管理
- [x] 邀请记录
- [x] 邀请奖励

> 签到管理（签到奖励）
> 公告管理（平台公告发布管理）
> 区块链管理
> 横幅banner管理
动态配置灵活各banner横幅信息
> 活动弹窗
首页弹窗设置，动态灵活配置弹窗内容和形式

> 其他
- [x] 验证记录
- [x] 用户意见反馈
- [x] 用户操作记录

完整后台功能，不一一罗列

## 演示

测试账号:
1. username: 13800138000 
2. password: 654321


# 部分展示

## 前端展示 APP，H5，小程序

### APP，H5 浅色

<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(2).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(5).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(9).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(10).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(1).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(3).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(4).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(6).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(7).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(8).png" width="400" />

### 深色 演示
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(1).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(2).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(3).png" width="400" />

### 更多的风格可以自行定制

#后台展示

<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/023b5bb5c9ea15ce72b87b2218.png" width="900" />