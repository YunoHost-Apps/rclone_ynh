<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Rclone

[![集成程度](https://dash.yunohost.org/integration/rclone.svg)](https://ci-apps.yunohost.org/ci/apps/rclone/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![使用 YunoHost 安装 Rclone](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Rclone。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Rclone is a command-line program to manage files on cloud storage. It is a feature-rich alternative to cloud vendors' web storage interfaces. Over 70 cloud storage products support rclone including S3 object stores, business & consumer file storage services, as well as standard transfer protocols.

**分发版本：** 1.68.2~ynh1

## 截图

![Rclone 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://rclone.org/>
- 官方用户文档： <https://rclone.org/docs/>
- 上游应用代码库： <https://github.com/rclone/rclone>
- YunoHost 商店： <https://apps.yunohost.org/app/rclone>
- 报告 bug： <https://github.com/YunoHost-Apps/rclone_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/rclone_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
或
sudo yunohost app upgrade rclone -u https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
