# React Native WebView

This project intends to show that React Native with it's standard react-native-webview library is bad idea if you're expecting your end users to be able to realy on "Digital Wellbeing" ot "Family Link" software.

The root cause of this is that
- the Android WebView doesn't respect web browsing restrictions at all
- react-native-webview shouldn't be using it