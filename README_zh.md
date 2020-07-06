# LPAlexaKitiOS

[English](README.md) | [中文](README_zh.md)

LPAlexaKitiOS是Linkplay Alexa操作方案的app端SDK；通过它，您可以实现设备Alexa的登录以及Alexa信息的设置。

LPAlexaKit主要提供了两个功能：

- 设备Alexa登录、登出

- 设备Alexa信息设置，如语言、提示音等

## 文档

你可以在这里找到更多[文档](https://linkplayapp.github.io/linkplay_sdk_doc/zh-hans/iOS/Alexa.html) 。

## 如何开始

- [下载 LPAlexaKitiOS](https://github.com/linkplayapp/LPAlexaKitiOS/archive/master.zip) 并且导入SDK到你的工程中

## SDK Demo
###  1. 使用 CocoaPods 安装SDK的demo
- [LPMusicKitPodsDemo](https://github.com/linkplayapp/LPMusicKitPodsDemo)

###  2. 手动导入SDK的demo
- [LPMusicKitDemo](https://github.com/linkplayapp/LPMusicKitDemo)

## 需求

- iOS >= 10.0

## 安装

###  1. 使用 CocoaPods 安装

LPAlexaKit 可以通过 [CocoaPods](https://cocoapods.org) 安装. 将下面的代码添加到您的pod文件里即可：

```ruby
platform :ios, '10.0'

target 'your_target_name' do

   pod "LPAlexaKitiOS", :git => "https://github.com/linkplayapp/LPAlexaKitiOS.git"

end
```

然后在项目根目录下执行 `pod update` 命令进行集成。

_CocoaPods 的使用请参考：[CocoaPods Guides](https://guides.cocoapods.org/)_
_CocoaPods 建议更新至最新版本_

### 2. 手动配置项目

#### Step 1: 下载 LPAlexaKitiOS
- [下载 LPAlexaKitiOS](https://github.com/linkplayapp/LPAlexaKitiOS/archive/master.zip)
#### Step 2: 导入SDK
- 导入 LPAlexaKitiOS.framework，依赖的SDK：[LPMusicKitiOS](https://github.com/linkplayapp/LPMusicKitiOS)

## 作者

LinkPlay, ios_team@linkplay.com
