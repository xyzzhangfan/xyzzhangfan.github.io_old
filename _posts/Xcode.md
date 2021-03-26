---
layout:     post
title:      Xcode Commond Line Installation2
subtitle:   How to install Xcode Commond Line tool
date:       2018-05-05
author:     xyzzhangfan
header-img: img/post-bg-kuaidi.jpg
catalog: true
tags:
    - Xcode
    - iOS
---

## Installing

	xcode-select --install

![](https://upload-images.jianshu.io/upload_images/545662-f9031dfcce085f8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/459)

## Switch Xcode version

### Show the current version of xcode

	$ xcode-select --print-path
	
### Choose the default Xcode version

	$ sudo xcode-select -switch /Applications/Xcode.app
