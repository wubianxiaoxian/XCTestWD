# XCTestWD

## 1. Requirements

- XCode version 9.0 and above.
- iOS version 11.0 and above. （there is significant change on XCUITest interfaces and system private headers, hence we decide to support newest OS version only）

## 2. Starting XCTestWD

XCTestWD can be either started with XCode IDE or via simple xcodebuild command line. By default, the webdriver agent occupies port `8001`.  You can override the default port in XCode by searching `XCTESTWD_PORT` under project build settings. Alternatively, it can also be overrided when you execute command line method as specified in `2.2. Using Xcodebuild`

### 2.1. Using Xcode

Download the project and open the XCode project, checkout the scheme `XCTestWDUITests` and run the test case `XCTextWDRunner`


