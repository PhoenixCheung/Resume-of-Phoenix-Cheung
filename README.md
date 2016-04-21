# Resume-of-Phoenix-Cheung
## <center>**张闽 简历**<center/>
### <center>**iOS 工程师**<center/>

###个人资料

----
**出生年月**　1990年1月　　**手机**　18605025326

**所在城市**　福建厦门　　  **邮箱**　iOSZhangmin@gmail.com

**毕业院校**　仰恩大学 电子信息工程专业（2009-2013)

**GitHub**　[Phoenix Cheung](https://www.github.com/PhoenixCheung)
<!--more-->

###工作经历

----
**2014.03 至今**　　**厦门小鱼网**　　**iOS 工程师**　

***工作内容***

- 负责小鱼网 iOS 3.x 系列,4.x 系列,5.x 系列客户端的开发和维护工作【团队开发】
- 以公司内部外派身份参与 PP车 iOS 客户端的开发【团队开发】
- 负责好店通客户端的完整开发【独立开发】

###项目经历

---
#### **小鱼网 v 3.x 客户端　　团队项目** 
***项目简介:***　

  　　小鱼网 3.x 客户端，即目前 App Store 中供用户下载的版本。负责 3 系列版本的开发和维护，从 3.0 一直到现在的 3.5x 历经数十个小版本迭代。

***技术要点:***

- 使用 `MKNetworkKit` 作为网络请求框架，后改用 `AFNetworking` 框架 。
- 使用 `SDWebImage` 加载网络图片。
- `DTCoreText` 实现富文本展示和交互。
- 微信支付，支付宝支付，银联 POS 通支付等第三方支付平台 SDK 的接入和应用。
- APNs 推送，根据推送信息跳转对应页面或其他处理。
- 地图，包括定位及根据用户所安装的地图提供选择导航（同微信）。

---

#### **PP车 客户端　　团队项目** 
 
***项目简介***　

  　　PP车由厦门建发、小鱼网、日日建安联合推出,针对有车一族提供上门养护服务和车险服务,解决有车一族养车难
的问题。

***技术要点:***

- 使用 `AFNetworking` 作为网络请求框架。
- 使用 `JSONModel` 作 JSON 和 Model 间的转换。
- 封装 PPCRouter 作为统一的跳转中枢。
- 利用自己良好的英语能力，在版本被 reject 之后邮件 Apple 解释以及争取加急上线。

---
#### **小鱼网 v 4.x 客户端　　团队项目**
 
***项目简介***　

  　　小鱼网 4.x 客户端，因为一些作为工程师不能左右的因素此版本没有上线 `:(`。

***技术要点***

- 使用 `AFNetworking` 作为网络请求框架。
- 使用 `Mantle` 作 JSON 和 Model 间的转换。
- `FMDB` 简化数据库存储 。
- MVVM 模式的尝试。
- 通过 `WebViewJavaScriptBridge` 达成 JavaScript 和 Native 的交互。 
- AutoLayout 的运用,含 `Xib/StoryBoard` 构建布局及 `Masonry` 的使用，包括改变 `NSLayoutConstraint` 的 `priority` 及 `constant` 等属性做基于 AutoLayout 的动画等。

---


#### **小鱼网 v 5.x 客户端　　团队项目**
 
***项目简介***　

  　　小鱼网 5.x 客户端，目前在开发中并即将上线。

***技术要点***

- 要点大体同 4.x 客户端。

- 运用 `<objc/runtime>` 拦截系统导航栏返回按钮事件，并做相应操作。

- 使用正则表达式和 `NSPredicate` 解析 URL 链接，实现对任意链接的正确处理。
- 图文混排编辑器，可随意插入文字、表情、静态图片和动态图片等，排版灵活规范，实现真正的图文混排。

---
#### **QY 医世家 客户端　　个人项目** 
 
***项目简介***　

  　　一款关于中医养生、美容，提供月子服务的 App。

  　　App 属性：电商、社区论坛等。

***技术要点***

- 全程独立开发，包括 icon 素材的获取，独立构思大量界面设计及交互。
- 开始全面启用优秀的开源框架 `YYKit` 
- 自学 `ReactiveCocoa` 响应式编程，结合 MVVM 模式，并实践于项目中。
- 使用 `SSKeyChain` 做账号密码的安全存储。
- 运用 `<objc/runtime>` 通过 Method Swizzling 在类的 `+ (void) load;`方法快捷改变系统方法实现。
- 通过 `<objc/runtime>`  Associate Object 给 Category 增加属性。
- `IQKeyboardManager` 管理键盘事件 。
- `CocoaPods` 管理第三方库。
- 即时通讯模块，便于用户和客服人员能够瞬时沟通。

---
#### **好店通 客户端　　个人项目** 
 
***项目简介***　

  　　一款方便餐厅管理和订座的 App。

***技术要点*** 

- 全程独立快速开发。


###阅读书目
---

- **《Effective Objective-C 2.0 : 52 Specific Ways to Improve Your iOS and OSX Programs》**(中文：**《
Effective Objective-C 2.0：编写高质量iOS与OS X代码的52个有效方法》**)
- **《A-GUIDE-TO-iOS-ANIMATION-master》** 
- **《The Swift Programming Language》** 
- **苹果 iOS 官方文档** 　　

###主要浏览网站
---
- [GitHub](https://www.github.com)
- [Ray Wenderlich](https://www.raywenderlich.com)
- [Stack Overflow](http://stackoverflow.com)
- [V2EX](http://www.v2ex.com/)
- [NSHipster](http://nshipster.com/)

###总结和评价
---
 　　两年多时间的开发沉淀，让自己具备了完成各种需求、解决各种问题的方法和能力。积累了不少自己的 Category 和 Utility 等 Convenience Code ，这些都让自己的开发过程变得更加的高效和便捷。　　

 　　拥有对技术社区满满的热度，让自己时刻学习和拥抱新知识和新技术。热爱分享，以探讨和帮助解决同行朋友的问题为乐趣。　　

 　　拥有良好的英语听说读写能力，查看官方文档、外国技术网站或者博客都没有问题。　　

 　　本人性格开朗随和，能够很好地与团队相处和协作。
