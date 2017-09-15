# ios-sdk

## Introduction
Our SDK provides a wide range of both utility and client-facing features that will save time and make development easier than ever with APS Card. It's built purely on Apple Core Location and Core Bluetooth technologies and is 100% iBeacon compatible.
## Requirements
* iOS 8.0+
* Xcode 8
## Installation
### CocosPods
Add ```pod APSCardSDK``` to your Podfile and run ```pod install```. More on [CocoaPods here](http://cocospods.com).
### Manual
APS Card SDK comes to you as a framework. To setup, you only need to include a single APSCardSDK.framework file in your project to get started:
1. Drag and drop APSCardSDK.framework file into your Xcode project. It will automatically show up in your project navigator and will be added to "Linked Frameworks and Libraries" section in project settings.
2. APSCard SDK depends on Apple's CoreLocation and CoreBlueooth frameworks as well as SystemConfiguration framework to handle APSCard Server API requests, so you should include them in your project too. When you add them to your project settings, it should look like on the screenshot below.
## Usage
### Configuration
### Initilization
<pre><code>
</code></pre>
### APIs
