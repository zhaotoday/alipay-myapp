## 蚂蚁应用
- 使用HTML相关技术，灵活构建移动端App
- 通过和Native协同（jsBridge)，提升页面拥有的能力
- 缓存HTML/JS/CSS/图片等资源，运行时只传输必要的动态数据，降低对网络的依赖

## 优秀案例
支付宝App中，已有大量功能采用Hybrid模式开发，用户体验并不亚于原生应用，例如：游戏中心、我的快递、蚂蚁森林。

## 应用离线包
- 应用资源打包后，称为“应用离线包”
- 包大小限制为200kb，可以放置html / js / css / 图片等静态资源
- 页面运行时会挂在一个虚拟域名下。如配置了域名为 [https://a.sample.com](https://a.sample.com)，入口页面为 /page/index.html ，那么页面所在的url就是https://a.sample.com/page/index.html ， location.href 获取也是这个结果。
- 应用离线包有可靠的更新机制，发布后10分钟可以覆盖99%以上的用户。

## 开发原则
- 页面运行时，除了必要的数据和图片，不应有其他请求（如外部js/css)
- 业务内容应该符合相关法律法规规定

## 生态
- [支付宝通用UI库](http://am-team.github.io/antui/nav.html#info)
- [表单类应用建议使用Ant Design Mobile](https://mobile.ant.design/)
- [支付宝开放平台文档中心](https://doc.open.alipay.com/)

