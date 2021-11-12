# xcuitest-sample-app

![TestingBot logo](resources/testingbot-logo.png?raw=true "Logo")

This is a sample iOS app, created by TestingBot, to demonstrate how to use [XCUITest](https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/09-ui_testing.html) on [TestingBot](https://testingbot.com).
The app offers two input-fields, where you can enter numbers.
Upon clicking the 'calculate' button, the sum field will contain the sum of the two numbers that were entered.

The project contains an example XCUITest which performs these actions and verifies if the sum is correct.

## How to start

To get started, open the project in XCode and click *Product* then *Test*
If you'd like to run the test through commandline, you can use 

```
xcodebuild -project xcuitest-sample.xcodeproj -scheme xcuitest-sample -destination 'platform=iOS Simulator,name=iPhone 13,OS=15.0' test
```

or any other kind of simulator or device udid.

![Screenshot XCUITest](resources/screenshot.png?raw=true "Screenshot")

## More information

To learn more about XCUITesting in the cloud, please see the [TestingBot XCUITest documentation](https://testingbot.com/support/xcuitest)
