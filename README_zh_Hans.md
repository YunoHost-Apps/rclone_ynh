# 打包应用，从这个示例开始

- 使用 Github 代码库中的['使用此模板'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost)按钮复制此应用，然后再对其进行操作
- 编辑 `manifest.toml` 文件以补充应用特定信息
- 编辑 `install`, `upgrade`, `remove`, `backup` 和 `restore` 脚本，以及 `conf/` 中的任何相关配置文件
  - 使用[脚本帮助文档](https://yunohost.org/packaging_apps_helpers)
- 同时编辑 `change_url` 和 `config` 脚本，如果不需要，可将其删除
- 为软件包添加 `LICENSE` 文件。
  - 注意：此 `LICENSE` 文件不一定与上游应用的 LICENSE 相同 - 它只是您希望此软件包的代码发布时使用的 LICENSE 并且您可以自由选择！（如果您不知道该如何选择，我们推荐 [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt)）
- 编辑 `doc/` 目录下的文件（[请参阅有关文档化软件包的页面](https://yunohost.org/packaging_app_doc)）
- `README.md` 文件将由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成

---
<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Example app

[![集成程度](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![工作状态](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)

[![使用 YunoHost 安装 Example app](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Example app。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况



**分发版本：** 1.0~ynh1

**演示：** <https://demo.example.com>

## 截图

![Example app 的截图](./doc/screenshots/example.jpg)

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

- 官方应用网站： <https://example.com>
- 官方用户文档： <https://yunohost.org/apps>
- 官方管理文档： <https://yunohost.org/packaging_apps>
- 上游应用代码库： <https://some.forge.com/example/example>
- YunoHost 商店： <https://apps.yunohost.org/app/example>
- 报告 bug： <https://github.com/YunoHost-Apps/example_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/example_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
或
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
