VisionLocalImageScroller
=====
* VisionLocalImageScroller provides infinite scroll on a group of local images which could autoplay with a specified interval. Scrollable horizontally only. Use [VisionRemoteImageScroller](https://github.com/VIIIO/VisionRemoteImageScroller "VisionRemoteImageScroller") instead if you want to load remote images.
* 非常实用、可自动播放的图片滑动器（类似幻灯片效果），可在水平方向无限滚动。若需要加载远程图片，请使用同系列控件：[VisionRemoteImageScroller](https://github.com/VIIIO/VisionRemoteImageScroller "VisionRemoteImageScroller")

### Screenshots
![image](http://blog.viiio.com/wp-content/uploads/2016/04/visioncontrol_02.gif)

### Contents
## Installation 安装

* Just drag `VisionControl` folder into your project
* 将`VisionControl`文件夹拖入你的項目

### 在你需要使用控件的文件中导入头文件:
```objective-c
#import "VisionLocalImageScroller.h"
```
## Usage 使用方法
```objective-c
    VisionLocalImageScroller *scroller = [[VisionLocalImageScroller alloc] 
                                               initWithFrame:CGRectMake(0, 100, 400, 200)
                                               imageArray:@[[UIImage imageNamed:@"1.png"],
                                                            [UIImage imageNamed:@"2.png"],
                                                            [UIImage imageNamed:@"3.png"],
                                                            [UIImage imageNamed:@"4.png"]]
                                               autoPlay:YES];
    [self.view addSubview:scroller];
```

## Features 特性
* support custom placeholder image</br>
* infinite scroll</br>
* support autoplay</br>
* 可自定义占位图片</br>
* 可无限滚动</br>
* 支持自动播放</br>

## Requirements 要求
* iOS 6 or later. Requires ARC  ,support iPhone/iPad.
* iOS 6及以上系统可使用. 本控件纯ARC，支持iPhone/iPad横竖屏

## More 更多 

Please create a issue if you have any questions.
Welcome to visit my [Blog](http://blog.viiio.com/ "Vision的博客")

## Licenses
All source code is licensed under the [MIT License](https://github.com/VIIIO/VisionLocalImageScroller/blob/master/LICENSE "License").

