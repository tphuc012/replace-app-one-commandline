# replace-app-one-commandline [![NPM version](https://img.shields.io/npm/v/replace-app-one-commandline.svg?style=flat)](https://www.npmjs.com/package/replace-app-one-commandline) [![NPM monthly downloads](https://img.shields.io/npm/dm/replace-app-one-commandline.svg?style=flat)](https://npm-stat.com/charts.html?package=replace-app-one-commandline) [![NPM total downloads](https://img.shields.io/npm/dt/replace-app-one-commandline.svg?style=flat)](https://npm-stat.com/charts.html?package=replace-app-one-commandline) [![Paypal Donate](https://img.shields.io/badge/paypal-donate-green.svg?style=flat)](https://www.paypal.me/junedomingo)

Rename react-native app with just one command

![replace-app-one-commandline](https://cloud.githubusercontent.com/assets/5106887/24444940/cbcb0a58-149a-11e7-9714-2c7bf5254b0d.gif)

> This package assumes that you created your react-native project using `react-native init`.

**Note:** This package does not attempt to properly rename build artifacts such as `ios/build` or Cocoa Pod installation targets. After renaming your project you should clean, build, and reinstall third party dependencies to get it running properly with the new name.

### Usage
```
$ npx replace-app-one-commandline <newName>
```

> With custom Bundle Identifier (Android only. For iOS, please use Xcode)
```
$ npx replace-app-one-commandline <newName> -b <bundleIdentifier>
```

### Example

##### First, Switch to new branch (optional but recommended)
```
$ git checkout -b rename-app
```
##### Then, Rename your app
```
$ npx replace-app-one-commandline "Travel App"
```
> With custom Bundle Identifier
```
$ npx replace-app-one-commandline "Travel App" -b com.junedomingo.travelapp
```

### Local installation
With **Yarn**:
```
$ yarn global add replace-app-one-commandline
```
With **npm**:
```
$ npm install replace-app-one-commandline -g
```

### Support
<a href="https://www.buymeacoffee.com/junedomingo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;"  target="_blank"></a>
