[Quick Start Intro to Dart](https://www.dartlang.org/docs/dart-up-and-running/ch01.html)
==========================

Dart可以快速的创建HTML5 web apps。

###下面瞥一眼Dart语言

下面是一段Dart程序：

	import 'dart:math';

	class Point {
  	num x, y;
  	Point(this.x, this.y);
  	num distanceTo(Point other) {
    	var dx = x - other.x;
    	var dy = y - other.y;
    return sqrt(dx * dx + dy * dy);
  	}
	}

	main() {
  	var p = new Point(2, 3);
  	var q = new Point(3, 4);
  	print('distance from p to q = ${p.distanceTo(q)}');
	}
    
 Dart主要用于构建web应用，程序如下：
 
 	import 'dart:html';

	main() {
  	var button = new ButtonElement();
  	button..id = 'confirm'
    	    ..text = 'Click to Confirm'
        	..classes.add('important')
        	..onClick.listen((e) => 	window.alert('Confirmed!'));
	  querySelector('#registration').children.add(button);
	}