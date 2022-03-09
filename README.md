## 内容列表

- [背景](#背景)
- [安装部署](#安装部署)
- [使用说明](#使用说明)
- [开始消息推送](#开始消息推送)
- [维护者](#维护者)
- [贡献者](#贡献者)
- [使用许可](#使用许可)

## 背景

看到市面上有很多公众号版的手机验机服务，由于公众号版需要进行微信认证。于是就写了一个网页版的手机查询、验机的网站，支持安卓查询、苹果GSX查询。

这个仓库的目标是：
* ~

## 安装部署

以宝塔面板部署此项目为例。

步骤如下：

* 第一步：购买服务器并做配置(教程还没写)
* 第二步：安装宝塔面板(教程还没写)
* 第三步：宝塔面板部署此程序(教程还没写)
* 第四步：验机数据接口注册与配置(教程还没写)
* 第五步：站点支付功能申请与配置(教程还没写)
* 第六步：其它网站基础配置(教程还没写)
* 第七步：配置微信内登录网站(教程还没写)

## 系统介绍
>演示地址：[点我查看])(https://gsx-demo.jdwkj233.cn/GlobalServiceExchange/user/login.html?open_id=o-Z_P0XclHJemevBK8U4aMyuhnuU)

1.1 个人中心模块
* 可设置用户退款时的收款人信息和收款人账号；

* 可查看历史订单记录以及历史查询结果。

1.2 购买模块
* 支持微信支付购买；

1.3 登录模块
* 需要自己注册一个公众号，通过用户对于当前公众号的open_id实现

1.4 订单处理模块
* 支付成功回调将订单信息及查询结果写入数据库，方便用户在历史订单中查看
* 通过Redis实现一个延迟队列，处理超时未支付订单。

1.5 前台模块
* 包含商品列表模块、商品详情页模块、客服模块

1.6 验机数据接口

1.7 支付渠道
* 第四方支付

## 维护者

[@zaocanchishenmo](https://github.com/zaocanchishenmo)。

### 贡献者

感谢以下参与项目的人：

## 使用许可

[LGPL-3.0 license](LICENSE) © zaocanchishenmo
