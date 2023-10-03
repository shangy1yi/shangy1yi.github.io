---
categories:
- - 科技&产品
cover: https://github.com/shangy1yi/picx-images-hosting/raw/master/image.32moskio67g0.webp
date: '2023-08-25T16:37:40.395967+08:00'
tags:
- Firefox
- Mozilla
- Chrome
title: Firefox用户现在可以导入Chrome扩展
updated: 2023-8-27T17:22:12.526+8:0
---
# Firefox用户现在可以导入Chrome扩展

Mozilla最新稳定版本的Firefox现在允许用户从Chrome导入扩展程序。这一功能的实现是基于WebExtensions系统¹，旨在使跨浏览器扩展变得更加容易。

用户只需按照以下步骤操作：在浏览器地址栏输入：
1、"about:config"，确认继续操作
2、搜索"browser.migrate.chrome.extensions.enabled"，并将其设置为True
3、重新启动Firefox

这项功能已经集成到浏览器的导入功能中，用户可以选择在首次运行时或从设置页面导入数据。虽然目前仅支持来自Google Chrome的部分扩展²，但Mozilla计划将扩展的导入功能扩展到更多的扩展对，并有可能支持其他浏览器的导入。

这一功能的实施使得用户可以方便地在Firefox中使用他们喜欢的扩展，但需要注意的是，导入过程可能不会包括自定义设置和配置的导入。

<img src="https://github.com/shangy1yi/picx-images-hosting/raw/master/image.32moskio67g0.webp" alt="image" />
