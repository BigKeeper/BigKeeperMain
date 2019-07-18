# LPDBaseLib

[![CI Status](https://img.shields.io/travis/sfmdeveloper@icloud.com/LPDBaseLib.svg?style=flat)](https://travis-ci.org/sfmdeveloper@icloud.com/LPDBaseLib)
[![Version](https://img.shields.io/cocoapods/v/LPDBaseLib.svg?style=flat)](https://cocoapods.org/pods/LPDBaseLib)
[![License](https://img.shields.io/cocoapods/l/LPDBaseLib.svg?style=flat)](https://cocoapods.org/pods/LPDBaseLib)
[![Platform](https://img.shields.io/cocoapods/p/LPDBaseLib.svg?style=flat)](https://cocoapods.org/pods/LPDBaseLib)
LPDTeam 基础三方库以及工具类.</br>
```
subspec: Base -> 'AFNetworking', '3.1.0' 'SDWebImage', '4.1.2' 'Masonry', '1.1.0' 'GZIP', '1.2.1' 'Mantle', '2.1.0'
subspec: Image -> 图片资源下载器,[图片上传cdn地址](https://fuss.faas.ele.me/),直接解析 Hash->URL.
subspec: Time -> 使本地时间尽量与后端时间同步(永光写的,迁移过来)
```
## Release
```
pod repo push elenet-lpdspecs LPDBaseLib.podspec --sources='git@git.elenet.me:arch.mobile/iOS_specs.git,git@git.elenet.me:LPD-iOS/LPDSpecs.git,git@git.elenet.me:LPD-iOS/GitHubSpecs.git' --allow-warnings
```
## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

LPDBaseLib is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'LPDBaseLib'
pod 'LPDBaseLib/Image'
pod 'LPDBaseLib/Time'
```

## Author

fengming.shi@ele.me

## License

#不开源#
