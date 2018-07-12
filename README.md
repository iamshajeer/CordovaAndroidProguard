# cordova-proguard-android

#### Version 0.1.0 (12/07/2018)

## What is ProGuard?

> ProGuard is the open source optimizer for Java bytecode

You can read more about it on [ProGuard official website](https://www.guardsquare.com/en/proguard) and on [android developer portal](https://developer.android.com/studio/build/shrink-code.html)

## How to use

- If you already have installed [Android Studio](https://developer.android.com/studio/index.html) then seems you already have installed ProGuard on your machine. If no, then  you should download and install it manually from [ProGuard official website](https://www.guardsquare.com/en/proguard).
- ```cordova plugin add cordova-plugin-android``` - this command will configure your `build.gradle` file and copy `proguard-custom.txt` to `${androidPlatformDirectory}/assets/www/proguard-custom.txt`

## Customization

`proguard-custom.txt` file contains some basic rules for your cordova mobile app. Feel free to [fork this repo](https://github.com/greybax/cordova-plugin-proguard/fork) and modify it as you want. 

You can also to check out some [Android ProGuard snippets](https://github.com/krschultz/android-proguard-snippets)

## License
```
The MIT License

Copyright (c) 2017 Shajeer Ahamed (info4shajeer@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
