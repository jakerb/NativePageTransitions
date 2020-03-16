## Native Page Transitions Cordova / PhoneGap Plugin
by [Telerik](http://www.telerik.com) and forked by [jakerb](https://jakebown.com)

This fork is to overcome the deprecation warning and eventual iOS App Store rejection of UIWebView code being present in the code. I couldn't find a version of this plugin that had been prepared for the [April 2020 App Store Deprecation](https://developer.apple.com/news/?id=12232019b)

> **WARNING** Do not install if using UIWebView - switch to WKWebView.

### UIWebView Removed
This fork is a direct copy of the original plugin but with all instances of UIWebView removed as this was causing deprecation warning when uploading to App Store for iOS. Only use this plugin if you have WKWebView installed and set as default engine as there is no fallback for UIWebView.

> **WARNING**: This plugin is no longer maintained, and we now recommend using [NativeScript](https://www.nativescript.org/) as you get native transitions (and UI) out of the box.

Using Capacitor CLI?

```
npm install git@github.com:jakerb/NativePageTransitions.git
npx cap sync
```

Using the Cordova CLI?

```
cordova plugin add git@github.com:jakerb/NativePageTransitions.git
```

Using PGB?

```xml
<plugin name="com.telerik.plugins.nativepagetransitions" source="npm" />
```

[The MIT License (MIT)](http://www.opensource.org/licenses/mit-license.html)
