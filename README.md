# LPMusicKitiOS

[English](README.md) | [中文](README_zh.md)

Linkplay Music Kit is the app side SDK for Linkplay Home Audio solution；you can use it to implement our solution into your product.

MusicKit mainly solves 2 issues：

- Maintain the commnunication protocol with our firmware so that your app could interact with the device without concerning the comlexity of the lower layers.

- Wrapper the complexity of cloud services (includes music services and voice services etc.) so that you can intergtate them rapidly and don't bother the details.

## Documentation

You can find documentation [on the website](https://linkplayapp.github.io/linkplay_sdk_doc/en/).

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

LPMusicKitiOS is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
platform :ios, '9.0'

target 'your_target_name' do

   pod "LPMusicKitiOS", :git => "https://github.com/linkplayapp/LPMusicKitiOS.git"

end
```

## Author

LinkPlay, ios_team@linkplay.com
