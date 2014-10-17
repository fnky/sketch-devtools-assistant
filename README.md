Sketch DevTools Assistant
=========================

Sketch DevTools Assistant is a helper OSX application that works together with [Sketch DevTools]() solution and provides protocol handling functionality for `Jumpt To Code` feature of DevTools for the following list of IDEs:
- Atom
- Sublime Text
- WebStorm
- AppCode
- XCode
- MacVim

Without this app installed all the listed editors will not work with the `Jump To Code` feature of DevTool.

## Installation
1. Download an archive [Sketch DevTools Assistant.zip]() with compiled app and unzip it
2. Copy `Sketch DevTools Assistant.app` to the `Applications` folder
3. The compiled application isn't signed because I don't have Mac Developer subscription yet, thus you have to do one extra steps to make it work. Go to the `Applications` folder and right click on the `Sketch DevTools Assistant` app file and click `Open` item form context menu like this:
<img src="https://raw.githubusercontent.com/turbobabr/sketch-devtools-assistant/master/docs/open_app.png" width="500" height="398">
4. Run the application. If everything works fine you will see the app icon in the tray:

<img src="https://raw.githubusercontent.com/turbobabr/sketch-devtools-assistant/master/docs/tray_status.png">

## Compiling

If you don't want to use unsigned binary you can just clone this repo, compile the app, put it into the `Applications` folder and run it.

## Usage

### How and why protocol handling works

> Content goes here...

### Using actions

> Content goes here...

### Using automation to run plugins

> Content goes here...

## Version history

> Version history goes here..

## Feedback

If you discover any issue or have any suggestions for improvement of the plugin, please [open an issue](https://github.com/turbobabr/sketch-devtools-assistant/issues) or find me on twitter [@turbobabr](http://twitter.com/turbobabr).

## Credits

Sketch DevTools Assistant uses [CocoaScript](http://github.com/ccgus/CocoaScript) framework by [August Mueller](http://github.com/ccgus) for running Sketch plugins using actions or automation.

## License

The MIT License (MIT)

Copyright (c) 2014 Andrey Shakhmin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



