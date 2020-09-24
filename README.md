# wwdc2020（一）

## 简介

苹果全球开发者大会（Worldwide Developers Conference），简称为“WWDC”，每年定期由苹果公司（Apple Inc.）在美国举办。大会主要的目的是让苹果公司向研发者们展示最新的软件和技术。

今年6月wwdc的session基本都已经看完了，由于篇幅关系打算分篇来介绍，这次主要介绍我认为比较重大的改变或者是跟公司业务相关的改变。如果效果可以的话后面会在TDD2之后继续进行分享。

wwdc系列后续只分享相对通用的东西，iOS独特的东西会考虑以文章的形式共享到iOS技术群。

## 用户层面的变化

### iOS14

+ app资源库（App Library）
+ 屏幕小组件
+ 画中画
+ Siri不再占满全屏
+ 翻译软件
+ 信息应用
+ 地图应用
+ CarPlay
+ 轻应用（App Clips）

### iPadOS14

+ 侧边栏
+ 很多应用不再全屏
+ 搜索体验
+ apple pencil

### macOS Bug Sur

+ 图标风格拟物化
+ 通知栏重做
+ widgets
+ safari
+ 工具栏优化

### 轻应用（App clips）

+ 简介
轻应用是完整应用的一部分，用户可以用轻应用快速使用app的功能，类似微信小程序。
+ 特点
  + 大小要小于10MB
  + 支持apple登录（Sign in With Apple）
  + 支持Apple Pay
  + 可以选择下载完整app
+ 流程
![270478-b08d23d2850ee8e7](/assets/270478-b08d23d2850ee8e7.jpg)

### 隐私

## 开发者层面的变化

今天只展开介绍SwiftUI，小组件（widget）以及轻应用（app clips）

### Swift UI

+ 简介
+ 优点
+ 新变化
  + app
    + 可以用Swift UI来构建整个应用
    + 可以定义数据依赖
    + 可以用windowGroup来管理窗口，主要用于iPadOS以及macOS的多窗口管理
    + 可以用DocumentGroup来自动处理文档的常用操作
    + 用CommandMenu支持快捷键
    + SwiftUI应用跨平台模板
  + widgets
    + 用SwiftUI可以构建iOS、macOS以及iPadOS的小组件
    + 可以用SwiftUI构建watchOS自定义的复杂组件
  + 列表
    + 新增对大纲模式的封装
  + 工具栏和控件
    + 对tollbar进行了封装
    + 新增一些控件
  + 新风格
    + 转场动画优化
  + 系统交互

### widget

## 从变化看趋势

### 隐私监控

### 跨平台

### 轻量级

### AR

## 小结

技术变化日新月异，希望大家都能好好把握技术趋势，通过技术分享的方式把自己领域内的变化传达出来，让大家能够更好地把握行业趋势。
