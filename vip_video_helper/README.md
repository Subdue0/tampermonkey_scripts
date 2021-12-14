# VIP视频解析助手
[![TamperMonkey](https://img.shields.io/badge/-TamperMonkey-brightgreen)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) [![Chrome x64](https://img.shields.io/badge/-Chrome%20x64-brightgreen)](https://www.google.cn/chrome/) [![Firefox x64](https://img.shields.io/badge/-Firefox%20x64-brightgreen)](http://www.firefox.com.cn/) [![Yandex arm](https://img.shields.io/badge/-Yandex%20arm-brightgreen)](https://yandex-browser-for-android.cn.uptodown.com/android/download) [![User-Agent Switcher](https://img.shields.io/badge/-User--Agent%20Switcher-brightgreen)](https://chrome.google.com/webstore/detail/user-agent-switcher/aedikcfpfonanffanecfolneiaoakmlc)

超好用的[油猴(科学上网)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)脚本，界面简洁美观，使用方便，同时又适配桌面端和移动端，全网只此一个！~~这脚本一直都是自己用，身边人用，好几年了，只是不公开，好东西总是藏起来滴，发布即是2.0.0版本！~~

## 支持：
理论上，本脚本可以解析全网移动端和桌面端的VIP视频，包括各大网站的付费电影和最新电视剧的超前点播。

## 使用说明：
- **桌面端：** 鼠标指针悬浮在播放按钮上方，出现菜单，选择自己喜欢的接口（接口可自由增减）；鼠标指针离开菜单范围，菜单消失。

- **移动端：** 双击直接使用默认接口，第二接口；长按播放按钮，出现菜单；滑动菜单，菜单消失。

## 浏览器推荐：
- **桌面端：**
  - [谷歌浏览器](https://www.google.cn/chrome/)
  - [火狐浏览器](http://www.firefox.com.cn/)
- **移动端：** 用过很多个支持油猴的浏览器，个人感觉[红叉浏览器](https://yandex-browser-for-android.cn.uptodown.com/android/download)的设计，无论是从美感还是拓展功能，又或者是从方便程度上来看，都是非常人性化的。

## 使用建议：
- 桌面端，可选择性太多，不做建议，留给大家自己折腾。

- 移动端，播放视频的时候关闭手机的方向锁定，手机横屏下可以直接免广告全屏播放视频。

- 移动端，如果下载有一些关联的APP，比如：爱奇艺，腾讯视频等，最好删了，因为这样可以防止网页播放视频时自动跳转到APP播放界面。

- 移动端，如果手机设备屏幕比较大，建议搭配[User-Agent Switcher(科学上网)](https://chrome.google.com/webstore/detail/user-agent-switcher/aedikcfpfonanffanecfolneiaoakmlc)使用，开启桌面版网页，效果不错。屏幕小点也能搭配着使用，就是操作起来稍微麻烦一点，不过可以去除很多视频悬浮广告和大部分APP跳转弹窗，而且就解析范围而言，桌面版网页也会支持更好一些。

## 脚本效果：
<a href="https://i.loli.net/2020/04/17/Vbahknp3i6MtDBN.gif" target="_blank"><img width="80%" src="https://i.loli.net/2020/04/17/Vbahknp3i6MtDBN.gif" ></a><a href="https://i.loli.net/2020/04/21/VUgPnktJhj1B7OC.gif" target="_blank"><img width="20%" src="https://i.loli.net/2020/04/21/VUgPnktJhj1B7OC.gif" ></a>

## 接口说明：
解析接口失效后，有时间就更新。

## 常见问题：
**Q：移动端的腾讯视频播放图标无法加载？**

A：这是由于通过首页导航的链接跳转时，并没有刷新整个页面，导致插件无法重新加载。这时只要重新刷新下视频页面就能解决问题。

**Q：爱奇艺的连续剧无法解析下一集？**

A：这是因为浏览器的链接并没有更换，所以一直解析旧的链接，只需右键集数，选择在新标签页中打开链接，再次解析即可解决问题。