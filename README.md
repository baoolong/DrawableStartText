# DrawableStartText

[![pub package](https://img.shields.io/pub/v/drawablestarttext.svg)](https://pub.dartlang.org/packages/drawablestarttext)

如果你的文字需要多行显示，并且在开头的位置要能添加图片。不妨试试这个控件，图片会自适应文字的高度来显示

If your text needs to be displayed in multiple lines and you need to add an image at the start, try this control.The image will be responsive to the height of the text to display

Home Page：[https://github.com/baoolong/DrawableStartText](https://github.com/baoolong/DrawableStartText)

More Widgt：[https://github.com/OpenFlutter/PullToRefresh](https://github.com/OpenFlutter/PullToRefresh)

<img width="38%" height="38%" src="https://raw.githubusercontent.com/baoolong/PullToRefresh/master/demonstrationgif/screenshot_20190127113535.png"/>

## Usage

Add this to your package's pubspec.yaml file:

	dependencies:
	  drawablestarttext: ^0.1.1
	  
Add it to your dart file:

    import 'package:drawablestarttext/drawablestarttext.dart';

## Example

    import 'package:flutter/material.dart';
    import 'package:drawablestarttext/drawablestarttext.dart';
    
    class DrawableStartTextDemo extends StatelessWidget{
      @override
      Widget build(BuildContext context) {
    
        return new Scaffold(
          appBar: new AppBar(
            title: new Text("DrawableStartText"),
          ),
          body: new Center(
            child: new Container(
              child: new DrawableStartText(
                assetImage: "images/tianmao.jpg",
                text: " 莫顿 全自动感应壁挂式酒精喷雾式手消毒器 手消毒机杀菌净手器",
                textStyle: new TextStyle(fontSize: 17.0),
              ),
            ),
          ),
        );
      }
    }

## Notice

No Notice

## LICENSE
    MIT License

	Copyright (c) 2018 baoolong
	
	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:
	
	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.
	
	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.
