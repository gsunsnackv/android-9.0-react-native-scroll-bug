# android-9.0-react-native-scroll-bug
The page has a scroll view with 100+ images. Everything works fine for android 8.x and 7.x but video cannot scroll smoothly on android 9.0

## Reproduce steps
1. `react-native init AwesomeProject`
2. Edit App.js .
3. Change <View> to <ScrollView>
4. Add 100 different images under the <ScrollView> for example https://github.com/gsunsnackv/android-9.0-react-native-scroll-bug/blob/master/App.js
5. Open an Android emulator with Android 9.0 (Pie) installed
6. `react-native run-android`

## Expect
Expect to scroll smoothly

## Actual
Cannot scroll smoothly

## Notes
Audio is fine. And on Android 8.x and 7.x, everything is fine
