# TaiChi-Guide


## 介绍

太极是一个能够运行 Xposed 模块的框架，模块能通过它改变系统和应用的行为。太极既能以传统的 Root / 刷机方式运作，也能免 Root / 免刷机运行；并且它支持 Android Lollipop ~ 10。

简单来说，太极就是一个类 Xposed 框架，它能够加载 Xposed 模块、修改系统和 APP、拦截方法，执行 Hook 逻辑等。

[点此来访问官方网站](https://www.taichi-app.com)


## 安装

### 太极阴（免 Root）

1. 在 [GitHub Releases](https://github.com/taichi-framework/TaiChi/releases/latest) 或者[酷安](https://www.coolapk.com/apk/me.weishu.exp)下载最新太极。
2. 点击下载好的 APK 安装包来进行安装。
3. 开始体验吧！

### 太极阳（依赖 Magisk）

警告：此模式仅保证 Android Oreo ~ 10 可用。

1. 在 Magisk 模块仓库中搜索“Taichi”。
2. 点击右边的下载图标，并在弹出的窗口中选择“安装”。
3. 安装完成后按照太极阴操作，并在操作完成后重新启动设备。
4. 开始体验吧！


## 使用方法

1. 点击右下角浮动按钮，然后选择“创建应用”。
2. 在“创建应用”界面中，选择你需要使用 Xposed 模块的 APP，然后点击最下方的按钮“创建”。
3. 耐心等待应用创建完成。这个过程可能会很长，取决于你手机 CPU 的好坏（太极阳不需要等待）。
4. 在系统中装好你需要使用的 Xposed 模块（不需要在太极中创建）。
5. 在太极主页右下角浮动按钮，选择 “模块管理”；然后勾选你需要使用的 Xposed 模块。
6. 在太极主页的已经创建过的 APP 列表中，长按列表或者点击右方箭头，选择“强制停止”，然后强制停止对应的 APP。
7. 重新打开此 APP，模块即可生效（不需要在太极中打开，从系统桌面打开即可）。


## 已支持的部分模块列表（更新可能会不及时）

[点击此处访问](https://taichi.cool/module/module_cn)


## 常见问题及其解答

[点击此处访问](https://www.taichi-app.com/fqa.html)


## 问题反馈

若遇到 BUG 请去 GitHub 提 [Issue](https://github.com/taichi-framework/TaiChi/issues)。

注意选择合适的问题模板并且尽量描述清楚问题。

当然，如果你有好的建议，也欢迎在 Issue 中提出。


## 模块适配

请访问[模块适配页面](http://admin.taichi.cool)提交适配。


## 注

本文档原创内容遵循 CC BY-NC-SA 4.0 协议。
