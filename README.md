# LPAlexaKitiOS

[English](README.md) | [中文](README_zh.md)

LPAlexaKitiOS is the app side SDK for Linkplay Alexa operation solution；you can use it to implement the device's Alexa login and Alexa information settings.

LPAlexaKit mainly provides two functions：

- Device Alexa login and logout.

- Device Alexa information settings, such as language, prompt tone, etc.

## Documentation

You can find documentation [on the website](https://linkplayapp.github.io/linkplay_sdk_doc/en/iOS/Alexa.html).

## How To Get Started

- [Download LPAlexaKitiOS](https://github.com/linkplayapp/LPAlexaKitiOS/archive/master.zip) and import SDK to your project

## SDK Demo
###  1. SDK demo with CocoaPods
- [LPMusicKitPodsDemo](https://github.com/linkplayapp/LPMusicKitPodsDemo)

###  2. SDK demo
- [LPMusicKitDemo](https://github.com/linkplayapp/LPMusicKitDemo)

## Requirements

- iOS >= 10.0

## Installation

###  1. Installationwith CocoaPods

LPAlexaKit is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
platform :ios, '10.0'

target 'your_target_name' do

   pod "LPAlexaKitiOS", :git => "https://github.com/linkplayapp/LPAlexaKitiOS.git"

end
```

Then run the `pod update` command in the root directory of project.
For use of CocoaPods, please refer to the [CocoaPods Guides](https://guides.cocoapods.org/). It is recommended to update the CocoaPods to the latest version.

### 2. Manually configure your project

#### Step 1: Download LPAlexaKitiOS

- [Download LPAlexaKitiOS](https://github.com/linkplayapp/LPAlexaKitiOS/archive/master.zip)

#### Step 2: Import Framework

- Import LPAlexaKit.framework, and its dependent SDK: [LPMusicKitiOS](https://github.com/linkplayapp/LPMusicKitiOS)

## Author

LinkPlay, ios_team@linkplay.com
