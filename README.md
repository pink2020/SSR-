# ShadowsocksR跨平台客户端

这是一个跨平台（支持Windows MacOS Linux系统）的`ShadowsocksR`客户端桌面应用，它功能丰富，支持windows版大部分功能，更有更多人性化功能。它是开源的，它来源于开源，回馈以开源。

## 客户端下载

[下载](https://github.com/erguotou520/electron-ssr/releases)

## 功能特色

- 支持手动添加配置
- 支持服务器订阅更新，复制该地址测试

  `https://raw.githubusercontent.com/erguotou520/electron-ssr/redesign/docs/assets/subscribe.txt`
- 支持二维码扫描(请确保屏幕中只有一个有效的二维码)，扫描该二维码测试

  ![](docs/assets/scan.jpg)
- 剪贴板复制、配置文件导入等方式添加配置
- 支持复制二维码图片(右键菜单)，SSR链接
- 支持链接打开应用(仅Mac和Windows)，[因平台限制，请前往该地址点击测试](https://erguotou520.github.io/electron-ssr)
- 支持切换系统代理模式:PAC、全局、不代理
- [内置http_proxy服务](docs/HTTP_PROXY.md)，可在选项中开启或关闭
- 支持配置项变更
- 更多功能尽在任务栏菜单中

<!-- ## Telegram交流

[![](https://img.shields.io/badge/Telegram-electron--ssr-blue.svg)](https://t.me/joinchat/E7ViZhJAZpKtnIJy9WepDA) -->

## 环境要求

- 只需要系统已安装 [python](https://www.python.org/downloads/) 可正常执行`shadowsocksr`的python版即可

## 快捷键

为了解决部分Linux发行版无法显示图标导致功能无法使用而加入了2个快捷键一个全局打开主窗口`Ctrl+Shift+W`，一个在窗口按`Ctrl+Shift+B`打开操作菜单，目前仅Linux可用。

## 已知Bug

- 部分Linux系统无法切换系统代理模式（使用`gsetting`设置的，非gnome桌面可能不生效），如果你知道如何实现，欢迎发issue告知。

## 应用截图

![](docs/assets/main.jpg)
![](docs/assets/settings.jpg)
![](docs/assets/ssr-settings.jpg)
![](docs/assets/subscribe.jpg)
![](docs/assets/tray.jpg)

## FAQ

[FAQ](./docs/FAQ.md)

## 图标资源

[https://www.figma.com/file/ghtehcxfzu0N2lQPoVEQXeU7/electron-ssr](https://www.figma.com/file/ghtehcxfzu0N2lQPoVEQXeU7/electron-ssr)

欢迎提出改修意见

## 打赏

[如果觉得本项目对你有所帮助，欢迎打赏](https://github.com/erguotou520/donate)

## 开发和构建

``` bash
# or npm install
yarn

# 开发时
npm run dev

# 打包构建
npm run build

# 单元测试
# npm test

# 代码风格检查
npm run lint

```

## Changelog更新日志

请直接查看[release发布说明](https://github.com/erguotou520/electron-ssr/releases)

## ShadowsocksR 参考文档

- [Python client setup (Mult language)](https://github.com/breakwa11/shadowsocks-rss/wiki/Python-client-setup-(Mult-language))
- [Python client setup (Mult language)备份](https://github.com/shadowsocksr-backup/shadowsocks-rss/wiki/Python-client-setup-(Mult-language))
- [SSR QRcode scheme](https://github.com/breakwa11/shadowsocks-rss/wiki/SSR-QRcode-scheme)
- [SSR QRcode scheme备份](https://github.com/shadowsocksr-backup/shadowsocks-rss/wiki/SSR-QRcode-scheme)

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[1c165f7](https://github.com/SimulatedGREG/electron-vue/tree/1c165f7c5e56edaf48be0fbb70838a1af26bb015) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).
