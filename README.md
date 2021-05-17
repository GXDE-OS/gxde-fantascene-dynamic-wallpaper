## 原来的名称
deepin-dreamscene-ui

## 目前是个动态壁纸demo [video wallpaper demo for deepin/uos]
关于deepin和uos系统的测试软件包,可以在右侧网页下载

## 演示视频:
[https://www.bilibili.com/video/BV1bB4y1c7Fq](https://www.bilibili.com/video/BV1bB4y1c7Fq/)

## 依赖
sudo apt install qtcreator libdtkwidget-dev libdtkcore-dev libx11-xcb-dev libxcb-ewmh-dev libmpv-dev mpv ffmpeg

## 在已经能编译代码的情况下如何打包
在修改了代码之后，直接在代码主目录下打开终端执行 dpkg-buildpackage -b -us -uc ，即可得到deb包

无理的需求可以随便提

如果有更好的做动态壁纸的方法欢迎讨论和分享

本软件作为学习作用,可以提出一些有理无理的需求,有时间会做下去的.
正在编码能力提高的路上,

目前:用已经编译好的透明dde-desktop在运行时替换原生dde-desktop

绘制动态壁纸，使用硬解码，目前最高支持双屏（功能当前相对简单）

最近几个月都会保持更新

有什么想法和问题都可以联系我liuminghang0821@gmail.com

有问必回

也可以提交issues 和pull requests

个人想法有限，能提意见和需求最好

目前已知问题:
1.在运行中修改分辨率，也许需要重启程序



github地址:https://github.com/dependon/deepin-dreamscene-ui
gitee地址:https://gitee.com/liuminghang/deepin-dreamscene-ui

