---
abbrlink: ''
categories:
- - 杂文快报
cover: https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.6mspmq5so680.png
date: '2023-10-02T14:17:28.436238+08:00'
tags:
- 中共
- 网络
- VS Code
- Visual Studio Code
title: 中国主要网络服务供应商对“我的世界”及“VS Code”实施网络访问限制，对 1.1.1.1 进行请求劫持。
updated: 2023-10-2T14:24:7.578+8:0
---
中国主要网络服务供应商对“我的世界”及“VS Code”实施网络访问限制，对 1.1.1.1 进行请求劫持。

Cloudflare的公共DNS服务1.1.1.1近期在中国遭遇了来自中国电信、中国联通和中国移动等主要运营商的访问限制。用户试图访问时，其HTTP请求会被301重定向至中国国家反诈中心和工信部反诈中心。同时，DNS查询请求被中断，DOH请求失败，并出现证书错误提示。此问题在中国广泛出现并已持续了一段时间。

鉴于此次全面的访问限制，建议用户考虑使用如谷歌DNS的其他服务，或者自行搭建DNS服务器，并确保对国内外的请求进行有效分流。

中国联通、中国移动及其他一些网络服务供应商近期已对“我的世界”（Minecraft）的主要网站和账号验证API域名及“Visual Studio Code”（VS Code）进行了网络访问限制。据用户反馈，当尝试登录或使用上述应用时，其HTTP请求会被重定向到国家反诈中心以及工信部反诈中心的提示页面。

由于 code.visualstudio.com 及 1.1.1.1 均有 HSTS 头，访问过这些网站的用户可能会注意到浏览器针对 HSTS 相关的报错


<img src="https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.6mspmq5so680.png" alt="image" />
