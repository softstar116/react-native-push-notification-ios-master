# Manual linking

- Add the `.xcodeproj` to your project
```
node_modules/@react-native-community/push-notification-ios/ios/PushNotificationIOS.xcodeproj
```

- Add the following to `Link Binary With Libraries` phase
```
libRNCPushNotificationIOS.a
```

More info on manual linking, [here](https://facebook.github.io/react-native/docs/linking-libraries-ios).
