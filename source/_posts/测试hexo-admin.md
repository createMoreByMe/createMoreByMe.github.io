title: 微信小程序开发（一）
author: Xu Penguin
abbrlink: 6ecdea6c
tags:
  - 微信小程序
categories: []
date: 2019-12-28 23:11:00
---
#### 一、小程序的文件格式
```
 --小程序 		--web
 	--wxss 		--css
 	--wxml 		--html
 	--json 		--json
 	--js 		--js
```
#### 二、小程序的结构
每个小程序都有自己的全局文件结构：
```
 --app
 	--app.wxcss
 	--app.json
 	--app.js
```
每个page也有自己的配置文件结构:
```
 --page
 	--wxss 
 	--wxml 
 	--json 非必须
 	--js 
```
组件式组成小程序page结构:
```
 --page
 	--component
 		--wxss 
 		--wxml 
 		--json 非必须
 		--js 
```
#### 三、小程序的全局配置文件
##### 1.app.json
app.json的主要内容：
```
	属性	类型	必填	描述	最低版本
	pages	string[]	是	页面路径列表	
	window	Object	否	全局的默认窗口表现	
	tabBar	Object	否	底部 tab 栏的表现
```
其中[<font color=red >window</font>](https://developers.weixin.qq.com/miniprogram/dev/reference/configuration/app.html)包含了用于设置小程序的状态栏、导航条、标题、窗口背景色。
#### 三、小程序的全局配置文件



