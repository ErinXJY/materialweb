# Material Web 

<img src="https://github.com/folgore95/media/blob/master/materialweb.png"/>

## About

Your personal Android app based on Google's material design.

## How does the app work?

The app needs an internet connection to work correctly because it uses the webview. The website will be cached in the app.
In this example i have used my personal website hosted on GitHub which follows the material design. You are free to fork it and design your copy. 

## Design the material page

Fork this <a href="https://github.com/folgore95/folgore95.github.io">repository</a> and rename it into `your-github-username.github.io` then start design your personal copy.

## Make the app

Download the project and after you have opened it in Android Studio open `MainActivity.java`. Now you need to change this line:
```xml
webview.loadUrl("https://folgore95.github.io");
```
into
```xml
webview.loadUrl("https://your-github-username.github.io");
```
After you have do that, open `colors.xml` which is located in `res/values` and change the app's colors to make them in line with the website colors.

## More

- <a href="https://developer.android.com/guide/webapps/webview.html">Android Developers - WebView</a>








