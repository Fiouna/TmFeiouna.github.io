---
layout: post
title: 弧度和角度互相转换
category: iOS
tags:
description:
---


1. 弧度（radians）和角度转换（degree）相互转换

### 详细内容

1. Swift 

````swift
CGFloat DegreesToRadians(CGFloat degrees) {return degrees * M_PI / 180;};
CGFloat RadiansToDegrees(CGFloat radians) {return radians * 180 / M_PI;};
````

2. Objective-C 

````objc
/** Degrees to Radian **/
#define degreesToRadians( degrees ) ( ( degrees ) / 180.0 * M_PI )

/** Radians to Degrees **/
#define radiansToDegrees( radians ) ( ( radians ) * ( 180.0 / M_PI ) )
````
