# WildDog Demos

Wilddog SDK Demos　分类汇总

像著名的 [android-open-project](https://github.com/Trinea/android-open-project) ，这里分类汇总了 WildDog平台上的示例程序和开源应用。

欢迎大家推荐使用了 WildDog 的开源项目，也欢迎大家开源用 WildDog做的小应用、练手的应用，欢迎Fork、提交PR :)

对于下面的项目，若想下载到本地，请直接点击 Github 上的`Download Zip`，如图所示，这样只下载最新版本。如果是 `git clone`，则可能非常慢，因为含杂很大的提交历史。某次测试两者是 1.5M:40M。
![qq20150618-2 2x](https://cloud.githubusercontent.com/assets/5022872/8223520/4c25415a-15ab-11e5-912d-b5dab916ce86.png)

或者指定 depth 参数来快速克隆到本地： `git clone https://github.com/WildDogTeam/Wilddog-demos.git --depth=1` 。

对于 iOS 上的 CocoaPods 项目，请尽量试用 `pod install --no-repo-update --verbose` ，这样会大大加快 `pod install` 的速度。
对于 Android 项目，大多数都是 Android Studio 所用的 Gradle 项目结构，导入 Eclipse 的话可能缺少某些类，请到 [SDK 下载页](https://www.wilddog.com/download/)下载 SDK 手动添加依赖。

Demo 分类：[iOS](https://github.com/WildDogTeam/Wilddog-demos#ios)、[Android](https://github.com/WildDogTeam/Wilddog-demos#android)、[JavaScript](https://github.com/WildDogTeam/Wilddog-demos#javascript)

## ios

### demo-ios-wildchat

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-wildchat.svg?style=social)

demo-ios-wildchat 是一个基于 Wilddog iOS SDK 实现的简单聊天通讯类 APP。

项目地址：https://github.com/WildDogTeam/demo-ios-wildchat


### demo-ios-wildfeed

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-wildfeed.svg?style=social)

demo-ios-wildfeed 是一个基于 Wilddog iOS SDK 开发的类似微博的社交应用。

项目地址：https://github.com/WildDogTeam/demo-ios-wildfeed

![image](https://raw.githubusercontent.com/WildDogTeam/demo-ios-wildfeed/master/screenShot.png)

### demo-ios-danmu

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-danmu.svg?style=social)

demo-ios-danmu 是一个基于 Wilddog iOS SDK 实现的弹幕。

项目地址：https://github.com/WildDogTeam/demo-ios-danmu

### demo-ios-weather

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-weather.svg?style=social)

demo-ios-weather 是一个基于 Wilddog iOS SDK 开发的修改天气状态 demo，主要实现 Wilddog 数据多设备同步修改和加载。

项目地址：https://github.com/WildDogTeam/demo-ios-weather

### demo-ios-drawing

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-drawing.svg?style=social)

demo-ios-drawing是一个基于 Wilddog iOS SDK 开发的实时画图 demo，可多终端登录来一起画画，同步显示图画效果。

项目地址：https://github.com/WildDogTeam/demo-ios-drawing

### demo-ios-login

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-login.svg?style=social)

demo-ios-login 是一个基于 Wilddog iOS SDK 开发登录 demo，其中实现的功能实例有QQ登录、微信登录、微博登录、匿名登录。

项目地址：https://github.com/WildDogTeam/demo-ios-login


### demo-ios-objects

![](https://img.shields.io/github/stars/WildDogTeam/demo-ios-objects.svg?style=social)

WilddogObjects是一个回调，用几个类配合wilddog实现一个同步的NSDictionary

项目地址：https://github.com/WildDogTeam/demo-ios-objects

## Android 

### demo-android-login 

![](https://img.shields.io/github/stars/WildDogTeam/demo-android-login.svg?style=social)

demo-android-login 是一个基于 Wilddog Android SDK 开发登录 demo，其中实现的功能实例有QQ登录、微信登录、微博登录、匿名登录。

项目地址：https://github.com/WildDogTeam/demo-android-login

### demo-android-drawing

![](https://img.shields.io/github/stars/WildDogTeam/demo-android-drawing.svg?style=social)

demo-android-drawing是一个基于 Wilddog Android SDK 开发的实时画图 demo，可多终端登录来一起画画，同步显示图画效果。

项目地址：https://github.com/WildDogTeam/demo-android-drawing

### demo-android-chat

![](https://img.shields.io/github/stars/WildDogTeam/demo-android-chat.svg?style=social)

demo-android-wildchat 是一个基于 Wilddog Android SDK 实现的简单聊天通讯类 APP。

项目地址：https://github.com/WildDogTeam/demo-android-chat

## javascript

### demo-js-geomap 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-geomap.svg?style=social)

demo-js-geomap 是一个基于wilddog JavaScript SDK和高德LBS开放平台完成的一个地图应用，能够实现实时的geohash范围查询。

项目地址：https://github.com/WilddogTeam/demo-js-geomap

在线地址：http://geomap.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-geomap/master/screenshot.jpg)

### demo-js-wildchat 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-wildchat.svg?style=social)

Wildchat 是使用 Wilddog 一个开源的、实时的聊天应用。它提供完全多用户，多房间，用户搜索，站内短信，聊天邀请等等。

项目地址：https://github.com/WilddogTeam/demo-js-wildchat

在线地址：http://wildchat.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-wildchat/master/screenshot.png)

### demo-js-wildpad 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-wildpad.svg?style=social)

Wildpad是一个开源的协同文本编辑器，它可以嵌入到较大的应用中。

项目地址：https://github.com/WilddogTeam/demo-js-wildpad

在线地址：http://wildpad.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-wildpad/master/screenshot.png)

### demo-js-wildfeed 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-wildfeed.svg?style=social)

利用野狗javaScript Sdk开发的类似的微博的社交应用。

项目地址：https://github.com/WilddogTeam/demo-js-wildfeed

在线地址：http://wildfeed.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-wildfeed/master/screenshot.png)

### demo-js-drawing 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-drawing.svg?style=social)

利用野狗javaScript Sdk开发的类似的微博的社交应用。

项目地址：https://github.com/WilddogTeam/demo-js-drawing

在线地址：http://drawing.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-drawing/master/app/images/drawing-demo.jpg)

### demo-js-crud 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-crud.svg?style=social)

使用野狗进行数据管理，只需要基本的DOM操作和简单的API就可以进行数据增加，持久化查询，数据修改和删除。

项目地址：https://github.com/WilddogTeam/demo-js-crud

在线地址：http://crud.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-crud/master/crud.png)


### demo-js-danmu 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-danmu.svg?style=social)

demo-js-danmu 是一个基于wilddog JavaScript SDK实现的弹幕。

项目地址：https://github.com/WilddogTeam/demo-js-danmu

在线地址：http://danmu.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-danmu/master/danmu.png)

### demo-js-starwars 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-starwars.svg?style=social)

demo-js-starwars 是一个基于wilddog JavaScript SDK实现的弹幕。

项目地址：https://github.com/WilddogTeam/demo-js-starwars

在线地址：http://starwars.wilddogapp.com/

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-starwars/master/starwars.png)

### demo-js-wildqiniu 

![](https://img.shields.io/github/stars/WildDogTeam/demo-js-wildqiniu.svg?style=social)

基于野狗和七牛API及Plupload开发的简单图片上传demo。

项目地址：https://github.com/WilddogTeam/demo-js-wildqiniu

![image](https://raw.githubusercontent.com/WildDogTeam/demo-js-wildqiniu/master/screenshot.png)













