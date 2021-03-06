# TTGEmojiRate
An emoji-based rating view for iOS, implemented in Swift. 

[![Version](https://img.shields.io/cocoapods/v/TTGEmojiRate.svg?style=flat)](http://cocoapods.org/pods/TTGEmojiRate)
[![License](https://img.shields.io/cocoapods/l/TTGEmojiRate.svg?style=flat)](http://cocoapods.org/pods/TTGEmojiRate)
[![Platform](https://img.shields.io/cocoapods/p/TTGEmojiRate.svg?style=flat)](http://cocoapods.org/pods/TTGEmojiRate)

![Screenshot](http://7nj2iz.com1.z0.glb.clouddn.com/TTGEmojiRate_screenshot.gif?refresh)

**Inspired by [Rating Version A - Hoang Nguyen](https://dribbble.com/shots/2211556-Rating-Version-A)**

![Rating Version A - Hoang Nguyen](http://7nj2iz.com1.z0.glb.clouddn.com/TTGEmojiRate_Dribbble.gif)

## Features
* More interactive with Emoji.
* Highly customizable.
* Can be used in Interface Builder.

![IB example](http://7nj2iz.com1.z0.glb.clouddn.com/TTGEmojiRate_1.png)

## What
TTGEmojiRate is an emoji-based rating view for iOS which is implemented in Swift.  
You can drop up and down on the Emoji face to change the rate, which is more interactive.  
TTGEmojiRate is also highly customizable that many features of it can be configure, like the emoji line width and the mouth width.

## Usage
### Use TTGEmojiRate

1. Create an instance of EmojiRateView and add it to the parent view.
```Swift
let rateView = EmojiRateView.init(frame: CGRectMake(0, 0, 200, 200))
rateView.center = self.view.center
self.view.addSubview(rateView)
```

2. Drop a view in the Interface builder and set the `Custom Class` to `EmojiRateView`

### Run example
To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements
Swift.  
iOS 8 and later.

## Installation
TTGEmojiRate is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
platform :ios, '8.0'
use_frameworks!

pod "TTGEmojiRate"
```

## Customization
![Customization](http://7nj2iz.com1.z0.glb.clouddn.com/TTGEmojiRate_mark.png)

## Author
zekunyan, zekunyan@163.com

## License
TTGEmojiRate is available under the MIT license. See the LICENSE file for more info.
