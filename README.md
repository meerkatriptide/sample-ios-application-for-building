# sample-ios-application-for-building

Forked from https://github.com/appium/ios-test-app for purpose of publishing new npm package, as the package from Appium is causing EINTEGRITY issues during npm install.


A simple test application for iOS, used by [Appium](https://github.com/appium/appium) for certain tests.

### Building

`npm install` will build the app for a simulator. If you want also to build for
a real device, set the environment variable `IOS_REAL_DEVICE` or `REAL_DEVICE`
to a truthy value.

```
REAL_DEVICE=1 npm install
```

If any special build information is needed, the `XCCONFIG_FILE` environment
variable can be set to the path to an `xcconfig` file.

## Watch

```
npm run watch
```

## Test

```
npm test
```
