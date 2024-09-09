<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Rclone untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/rclone.svg)](https://ci-apps.yunohost.org/ci/apps/rclone/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![Pasang Rclone dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Rclone secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Rclone is a command-line program to manage files on cloud storage. It is a feature-rich alternative to cloud vendors' web storage interfaces. Over 70 cloud storage products support rclone including S3 object stores, business & consumer file storage services, as well as standard transfer protocols.

**Versi terkirim:** 1.68.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Rclone](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://rclone.org/>
- Dokumentasi pengguna resmi: <https://rclone.org/docs/>
- Depot kode aplikasi hulu: <https://github.com/rclone/rclone>
- Gudang YunoHost: <https://apps.yunohost.org/app/rclone>
- Laporkan bug: <https://github.com/YunoHost-Apps/rclone_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/rclone_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
atau
sudo yunohost app upgrade rclone -u https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
