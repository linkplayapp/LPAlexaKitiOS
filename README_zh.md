# LPAlexaKitiOS

[English](README.md) | [中文](README_zh.md)

LPAlexaKitiOS是Linkplay Alexa操作方案的app端SDK；通过它，您可以实现设备Alexa的登录以及Alexa信息的设置。

LPAlexaKit主要提供了两个功能：

- 设备Alexa登录、登出

- 设备Alexa信息设置，如语言、提示音等

## 文档

你可以在这里找到更多[文档](https://linkplayapp.github.io/linkplay_sdk_doc/zh-hans/iOS/Alexa.html) 。

## 示例

如果您要执行示例工程，请clone工程并使用`pod install`安装必要库。

## 需求

- iOS >= 10.0

## 安装

LPAlexaKit 可以通过 [CocoaPods](https://cocoapods.org) 安装. 将下面的代码添加到您的pod文件里即可：

```ruby
platform :ios, '10.0'

target 'your_target_name' do

   pod "LPAlexaKitiOS", :git => "https://github.com/linkplayapp/LPAlexaKitiOS.git"

end
```

## 作者

LinkPlay, ios_team@linkplay.com
