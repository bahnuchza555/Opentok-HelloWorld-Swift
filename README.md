OpenTok Hello World (in swift)
==============================

To get started download the iOS SDK, and place it in `HelloWorld/Opentok.framework`, e.g. with:

```bash
$ git clone git@github.com:thepatrick/Opentok-HelloWorld-Swift.git
$ cd Opentok-HelloWorld-Swift
$ curl -L -O https://tokbox.com/downloads/opentok-ios-sdk-2.5.0
$ tar xzvf opentok-ios-sdk-2.5.0 OpenTok-iOS-2.5.0/OpenTok.framework
$ mv OpenTok-iOS-2.5.0/OpenTok.framework HelloWorld/OpenTok.framework
```

Then open `HelloWorld.xcodeproj` and run on your device.

Warnings
--------

You must have an Xcode with support for swift. See [Introducing Swift](https://developer.apple.com/swift/) for links to download Xcode.
