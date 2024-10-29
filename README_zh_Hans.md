<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Pretalx

[![集成程度](https://dash.yunohost.org/integration/pretalx.svg)](https://ci-apps.yunohost.org/ci/apps/pretalx/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/pretalx.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/pretalx.maintain.svg)

[![使用 YunoHost 安装 Pretalx](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pretalx)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Pretalx。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Pretalx is a conference planning tool focused on providing the best experience for organisers, speakers, reviewers, and attendees alike. It handles the submission process with a configurable Call for Participation, the reviewing and selection of submissions, and the scheduling and release handling. After the event, pretalx allows speakers to receive feedback, upload their slides, and organisers to embed recordings.

**分发版本：** 2024.3.1~ynh1

**演示：** <https://pretalx.com/p/try>

## 截图

![Pretalx 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://pretalx.com/>
- 官方管理文档： <https://docs.pretalx.org/>
- 上游应用代码库： <https://github.com/pretalx/pretalx>
- YunoHost 商店： <https://apps.yunohost.org/app/pretalx>
- 报告 bug： <https://github.com/YunoHost-Apps/pretalx_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing --debug
或
sudo yunohost app upgrade pretalx -u https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
