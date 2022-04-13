# HNU-Web-Design-2021

## Warning

***This repository has been archived!***

## 说明

这是「HNU 网页设计大赛 2021」的作品项目。项目作者以及贡献者：
- [Rain Chen](https://github.com/Chen-Rain)
- [Zeng Shun](https://github.com/sleepy-chuan)

## 演示体验

点击这里进入：[Demo传送门](https://chen-rain.github.io/projects/demo/login.html)
注意：这个 Demo 移除了「谷歌小恐龙」小游戏，但是本仓库包含它。

> 正确登录用户名请填写：`202108030122`<br>正确登录密码请填写：`2021`

## 实现功能

### 主要功能 - 倒计时

用于提示用户距离最后期限还剩多少时间。这个倒计时精确到秒。在倒计时加载的过程中，会有加载的动画。

### 主页面简述

选择每一个学科的考试时间倒计时，并点击按钮（View sth.）直接跳转到倒计时页面。

### 倒计时页面简述

横幅提示你的最后期限。下方是时刻变动的倒计时时间，采用天、时、分、秒的计算方式，数位不是对齐的，不管它是几位数，这个页面都会使整个时间，包括下方的单位一同保持在页面的中央。下方的左边有一个返回按钮（Back），用于跳转回主页面；下方的右边有一个复（续）习（命）按钮（Review!），用于跳转到相关学科的学习与练习网站，注意，这里有个别网站打开需要连接HNU校园网；正中央有一个休息按钮（Tired?），按下之后会跳转到经典的「谷歌小恐龙」小游戏。

### 登录页面简述

新增了浏览器判断，基于本人使用 Safari 浏览器进行调试开发，为了取得最佳浏览体验，当检测到非 Safari 浏览器的时候会弹出提示。

设置了一个用户名（Username）框以及一个密码（Password）框。下方有一个登录（Login）按钮。输入用户名及密码之后，网页会进行判断是否正确。如果输入内容无误，跳转到主页面。如果输入的内容有误，那么将会弹出提示「无效的用户名/密码」。连续输入错误超过三次，将会无法再进行登录操作，此时也会弹出提示，必须重新加载登录页面才能正常登录。

## 相关信息声明

### 关于图片及图标

网页标签图标及书签标签图标由 Rain Chen 设计制作，可以说十分简陋但是意义非常清楚。背景是白色的圆角正方形，主体部分是加粗斜体的「DDL」。

网页背景咖啡图片由 Rain Chen 拍摄。

### 关于本仓库的网页代码

除了 `/relax` 目录下的代码，其余所有代码都是由 [Rain Chen](https://github.com/Chen-Rain) 和 [Zeng Shun](https://github.com/sleepy-chuan) 编写。

### 关于「谷歌小恐龙」小游戏

这部分代码引用自 [wayou/t-rex-runner](https://github.com/wayou/t-rex-runner) 这个仓库。

