JSGeometry
==========

#### Easily manipulate CoreGraphics points, sizes and rects with one line of code

How much code do you have that looks like this:

```objective-c
CGRect myViewFrame = myView.frame;
myViewFrame.size.width = 300.f;
myView.frame = myViewFrame;
```

Wouldn't it be nicer to just write:

```objective-c
myView.frame = JSGRectChangeWidth(myView.frame, 300.f);
```

JSGeometry is very simply, a small set of C functions that will make your layout-code easier and less tedious to write!
It also works across both iOS & OSX.

#### Hope that you'll enjoy using JSGeometry

Why not give me a shout on Twitter: [@johnsundell](https://twitter.com/johnsundell)