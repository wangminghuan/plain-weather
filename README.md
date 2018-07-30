## plainWeather
>一个简易的天气预报小程序

## 说明
心血来潮，试水一个微信小程序，整体思路来源：[两天撸一个天气应用微信小程序](https://www.jianshu.com/p/bf3a261e68e5)；数据来源：[天气预报开放API](https://blog.csdn.net/qq_26599807/article/details/80814753)。

## 项目构建
采用腾讯官方的[小程序组件化开发框架](https://tencent.github.io/wepy/)

## 其他
1. 遇到一个异步数据无法刷新dom的坑，得手动触发下this.$apply();详见[小程序笔记](https://blog.csdn.net/yaodong379/article/details/79210201)