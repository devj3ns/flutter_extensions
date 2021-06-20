# Fleasy

<p align="center">
<a href="https://pub.dev/packages/fleasy"><img src="https://img.shields.io/pub/v/fleasy?color=informational" alt="pub.dev badge"></a>
</p>


This package helps create Flutter apps easier by providing useful and easy to use extensions, helper classes and widgets.

The goal is that by using this package you have to write less (repeating) and more clean and readable code.

This package contains the following features:

## Extensions:
- ### `BuildContext`
    - `mediaQuery`
    - `screenSize`
    - `screenWidth`
    - `screenHeight`
    - `screenOrientation`
    - `screenIsLandscape`
    - `screenIsPortrait`
    - `formFactor`
    - `closeKeyboard()`
    - `pushRoute(...)`
    - `pushPage(...)`
    - `popPage()`
    - `canPopPage()`
    
- ### `String`
    - `addHttps()`
    - `isValidEmail`
    - `isInvalidEmail`
    
- ### `String?`
    - `isNotBlank`
    - `isBlank`
    - `isValidEmail`
    - `isInvalidEmail`
    - `toNullIfBlank()`

- ### `DateTime`
    - `copyWith(...)`
    - `isToday`
    - `isYesterday`
    - `isTomorrow`
    - `isFutureDay`
    - `isSameDay(...)`
    - `timeIsZero`
    - `copyWithEmptyTime()`
    - `format(...)`
    
- ### `List<DateTime>`
    - `containsDate(...)`
    - `indexOfDate(...)`
    
- ### `List?`
    - `isNotBlank`
    - `isBlank`

- ### `List<T>`
    - `find(...)`
        
        
## Helper Classes: 
- ### `Date`
    - `Date.today()`
    - `Date.tomorrow()`
    - `Date.yesterday()`
    
- ### `DeviceType`
    - `DeviceType.isIOS`
    - `DeviceType.isAndroid`
    - `DeviceType.isMacOS`
    - `DeviceType.isLinux`
    - `DeviceType.isWindows`
    - `DeviceType.isWeb`
    - `DeviceType.isDesktop`
    - `DeviceType.isMobile`
    - `DeviceType.isDesktopOrWeb`
    - `DeviceType.isMobileOrWeb`
    
- ### `Insets`
    - `xxs`
    - `xs`
    - `s`
    - `m`
    - `l`
    - `xl`
    - `xxl`
    
## Flutter Widgets: 
- ### [EasyFutureBuilder<T>](https://pub.dev/documentation/fleasy/latest/fleasy/EasyFutureBuilder-class.html)
  A wrapper around `FutureBuilder` which makes it easy to display the various states of fetching data from the given `Future`. See [example](https://github.com/devj3ns/fleasy/blob/main/example/lib/main.dart).
- ### [EasyStreamBuilder<T>](https://pub.dev/documentation/fleasy/latest/fleasy/EasyStreamBuilder-class.html)
  A wrapper around `StreamBuilder` which makes it easy to display the various states of streaming data from the given `Stream`. See [example](https://github.com/devj3ns/fleasy/blob/main/example/lib/main.dart).
    
------

## To-Do's:
 - [ ] Add more tests
 - [ ] Document the complete code
 - [x] Create example app
 
## Note:
This package is still in early stages.
If you notice any bugs not present in issues, please file a new issue. If you are willing to fix or enhance things yourself, you are very welcome to make a pull request.