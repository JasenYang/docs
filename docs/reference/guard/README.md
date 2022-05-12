# 登录组件（Guard）

<LastUpdated/>

Authing 登录组件（Guard）是一种可嵌入的登录表单，可根据你的需求进行配置，建议用于单页面应用程序。它使你可以轻松添加各种社会化登录方式，以便你的用户可以无缝登录，并且在不同平台拥有一致的登录体验。Guard 为开发者屏蔽了很多底层认证的实现细节，同时也包括繁琐的 UI 开发。

Guard 可以集成到你的 React、Vue.js、Angular 以及原生 JavaScript 项目中，你可以借助此组件快速实现登录认证流程。

![Guard Demo](./images/Guard_demo.png)

## 功能列表

#### 丰富的登录注册方式

内置丰富的登录注册方式供开发者选择：

- 账号密码登录（包括手机号 + 密码、邮箱 + 密码、用户名 + 密码）；
- 手机验证码登录；
- APP 扫码登录（[需先接入 APP 扫码登录](/guides/authentication/qrcode/use-self-build-app/)）；
- 小程序扫码登录（[需先在后台配置](/guides/authentication/qrcode/use-wechat-miniprogram/)）；
- 社会化登录，如 GitHub 登录（[需先在后台配置](/guides/connections/social.md)）；
- 企业身份源登录（[需要配置企业身份源](/guides/connections/enterprise.md)）；

#### 内置忘记密码流程

Guard 内置了忘记密码的交互 UI，你无需编写任何额外代码。

#### 内置多因素认证（MFA）能力

Guard 内置了多因素认证（MFA）功能，当你的应用开启了[多因素认证](/guides/app/mfa.md)之后，用户可以使用该组件完成多因素认证。你无需编写任何额外代码。

#### 响应式布局

采用响应式布局，自动适应所展示的页面比例，完美兼容移动端和 PC 端。

#### 支持个性化登录框样式配置

- 两种样式，自由选用：[从 Guard V1 迁移](./migration.md)
- 自定义背景
- 自定义加载图标
- 自定义 CSS：实现更精细的配置

#### 兼容前端所有主流框架

更加详细的内容可以跳转到，Guard 快速开始，可以帮助你更快的上手使用。[Guard-快速开始](/reference/guard/quick-start/)

## 获取帮助

Join us on forum: [#authing-chat](https://forum.authing.cn/)
