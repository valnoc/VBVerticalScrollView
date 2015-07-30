VBVerticalScrollView
===========

VBVerticalScrollView limits scrolling to only vertical direction by resizing its contentView.

According to Apple docs when working with UIScrollView you should put all views into one contentView which will be added to scrollView itself.

Use case

1. Create view with information to be scrolled (do not forget to set constraints)
2. verticalScrollView.contentView = myContentView;

ContentView's width is equal to scrollView width.

## How to install
Use CocoaPods

    pod 'VBVerticalScrollView'

or

Drag VBVerticalScrollView dir into your project.

## License
VBVerticalScrollView is available under the MIT license. See the LICENSE file for more info.
