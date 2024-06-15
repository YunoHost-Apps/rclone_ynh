<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# rclone YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/rclone.svg)](https://dash.yunohost.org/appci/app/rclone) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![Instalatu rclone YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek rclone YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena



**Paketatutako bertsioa:** 1.67.0~ynh1

## Pantaila-argazkiak

![rclone(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Ezespena / informazio garrantzitsua

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

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://rclone.org/>
- Erabiltzaileen dokumentazio ofiziala: <https://rclone.org/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/rclone/rclone>
- YunoHost Denda: <https://apps.yunohost.org/app/rclone>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/rclone_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/rclone_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
edo
sudo yunohost app upgrade rclone -u https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
