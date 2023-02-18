---
layout:     page
title:      ACNet
authors:    Hao Ren
date:       2023-03-29
pub:        TCSVT
header-img: img/bg.jpg
---

## 前言

作为一名iOS开发者，最近面试被问到了`KVO`的问题。其实`KVO`的原理以及`runtiem`的知识，很早之前就有学习和使用了，但是实现的细节都忘记差不多了，故再此重新梳理一下。

## 正文

`NSKeyValueObserving `，一种非正式协议，通知其他对象的指定属性发生了改变。

简单理解就是，监听一个对象的某个`属性`是否发生改变。

### 参考

- [《Introduction to Key-Value Observing Programming Guide》
  ](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html#//apple_ref/doc/uid/10000177-BCICJDHA)
- https://blog.csdn.net/science_lee/article/details/82843080
- https://www.cenzhijun.top/2018/05/kvo/