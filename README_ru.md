<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Pretalx для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/pretalx.svg)](https://ci-apps.yunohost.org/ci/apps/pretalx/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/pretalx.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/pretalx.maintain.svg)

[![Установите Pretalx с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pretalx)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Pretalx быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Pretalx is a conference planning tool focused on providing the best experience for organisers, speakers, reviewers, and attendees alike. It handles the submission process with a configurable Call for Participation, the reviewing and selection of submissions, and the scheduling and release handling. After the event, pretalx allows speakers to receive feedback, upload their slides, and organisers to embed recordings.

**Поставляемая версия:** 2024.3.1~ynh1

**Демо-версия:** <https://pretalx.com/p/try>

## Снимки экрана

![Снимок экрана Pretalx](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://pretalx.com/>
- Официальная документация администратора: <https://docs.pretalx.org/>
- Репозиторий кода главной ветки приложения: <https://github.com/pretalx/pretalx>
- Магазин YunoHost: <https://apps.yunohost.org/app/pretalx>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/pretalx_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing --debug
или
sudo yunohost app upgrade pretalx -u https://github.com/YunoHost-Apps/pretalx_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
