<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 rclone

[![集成程度](https://dash.yunohost.org/integration/rclone.svg)](https://dash.yunohost.org/appci/app/rclone) ![工作状态](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![使用 YunoHost 安装 rclone](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 rclone。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况



**分发版本：** 1.0~ynh1

## 截图

![rclone 的截图](./doc/screenshots/example.jpg)

## 免责声明 / 重要信息

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

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
