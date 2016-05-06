# PTHospital.chrome

[![Build Status](https://travis-ci.org/hustcc/PTHospital.chrome.svg?branch=master)](https://travis-ci.org/hustcc/PTHospital.chrome)

一个莆田系医院网站提醒的浏览器插件，对于莆田系无良网站，将显示红色警告提示，并给出它的医院名字和医院电话。

## 安装地址

1. 下载本代码安装
2. chrome安装地址：[https://chrome.google.com/webstore/detail/%E8%8E%86%E7%94%B0%E7%B3%BB%E5%8C%BB%E9%99%A2%E7%BD%91%E7%AB%99%E6%8F%90%E9%86%92/pihadmdiehanenijehoohjnpiaofmmng](https://chrome.google.com/webstore/detail/%E8%8E%86%E7%94%B0%E7%B3%BB%E5%8C%BB%E9%99%A2%E7%BD%91%E7%AB%99%E6%8F%90%E9%86%92/pihadmdiehanenijehoohjnpiaofmmng)

## 截图

![screenshot/screenshot_1.png](screenshot/screenshot_1.png)

![screenshot/screenshot_2.png](screenshot/screenshot_2.png)

或者安装插件之后，从[https://raw.githubusercontent.com/langhua9527/Hospital/master/README.md](https://raw.githubusercontent.com/langhua9527/Hospital/master/README.md)中随意打开一个医院网址。


## 贡献代码

1. 首先fork代码，然后在`PTHospitalList.js`中增加医院的信息，主要是`网站`、`医院名字`、`医院位置`。
2. 然后发出`PR`即可。
3. 或者直接`发出issue`，由我们来修改。

代码PR并merge之后，会`自动触发webhook，然后将对应的数据推送到cdn上`，等待缓存过期之后，自动生效。

数据可以参考项目：

 - [https://github.com/langhua9527/Hospital](https://github.com/langhua9527/Hospital)
