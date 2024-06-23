<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Slingcode

[![集成程度](https://dash.yunohost.org/integration/slingcode.svg)](https://dash.yunohost.org/appci/app/slingcode) ![工作状态](https://ci-apps.yunohost.org/ci/badges/slingcode.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/slingcode.maintain.svg)

[![使用 YunoHost 安装 Slingcode](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=slingcode)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Slingcode。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Slingcode is a code editor contained in a single HTML file. Therefore, it has no server component, so all of your data is stored in your browser's cache. However, it is still possible to make web apps, run them, export them, and even share them using peer-to-peer.

### Features:

- You can make, run, and share web apps with it.
- You don't need any complicated tools to use it, just a web browser.
- You don't need a server, hosting, or an SSL certificate to run the web apps.
- You can put Slingcode on a web site, run it from a USB stick, laptop, or phone, and it doesn't need an internet connection to work.
- You can "add to home screen" in your phone's browser to easily access your library of programs on the go.
- You can share apps peer-to-peer over WebTorrent.
- It's private. You only share what you choose.


**分发版本：** 0.2.2~ynh5

**演示：** <https://slingcode.net/slingcode.html>

## 截图

![Slingcode 的截图](./doc/screenshots/Screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://slingcode.net/>
- 官方用户文档： <https://slingcode.net/screencasts.html>
- 上游应用代码库： <https://github.com/chr15m/slingcode>
- YunoHost 商店： <https://apps.yunohost.org/app/slingcode>
- 报告 bug： <https://github.com/YunoHost-Apps/slingcode_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
或
sudo yunohost app upgrade slingcode -u https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
