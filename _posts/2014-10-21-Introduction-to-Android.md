---
layout: post
date: 2014-10-21 17:15:04 +0800
title: 'Android 概览'
tags: ["Introduction"]
category: "Introduction"
---

#  Android 概览

标签（空格分隔）： 介绍

---
Android提供了一个允许你构建革新的应用程序或者游戏的应用程序框架,该框架运行于Java环境.本文档左侧列出了用各种Android提供的API构建应用程序的文档.如果你是一个Android开发新手,本文档对你理解Android应用程序框架有十分重要的作用

Android provides a rich application framework that allows you to build innovative apps and games for mobile devices in a Java language environment. The documents listed in the left navigation provide details about how to build apps using Android's various APIs.

If you're new to Android development, it's important that you understand the following fundamental concepts about the Android app framework:

##应用程序提供了多个入口
## Apps provide multiple entry points

Android apps are built as a combination of distinct components that can be invoked individually. For instance, an individual activity provides a single screen for a user interface, and a service independently performs work in the background.

From one component you can start another component using an intent. You can even start a component in a different app, such an activity in a maps app to show an address. This model provides multiple entry points for a single app and allows any app to behave as a user's "default" for an action that other apps may invoke.

**Learn more:**

[App Fundamentals][1]
[Intents and Intent Filters][2]
[Activities][3]
## Apps adapt to different devices

Android provides an adaptive app framework that allows you to provide unique resources for different device configurations. For example, you can create different XML layout files for different screen sizes and the system determines which layout to apply based on the current device's screen size.

You can query the availability of device features at runtime if any app features require specific hardware such as a camera. If necessary, you can also declare features your app requires so app markets such as Google Play Store do not allow installation on devices that do not support that feature.

**Learn more:**

[Device Compatibility][4]
[Resources Overview][5]
[User Interface Overview][6]


[1]:http://developer.android.com/guide/components/fundamentals.html
[2]:http://developer.android.com/guide/components/intents-filters.html
[3]:http://developer.android.com/guide/components/activities.html

[4]:http://developer.android.com/guide/practices/compatibility.html
[5]:http://developer.android.com/guide/topics/resources/overview.html
[6]:http://developer.android.com/guide/topics/ui/overview.html