<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# rclone pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/rclone.svg)](https://dash.yunohost.org/appci/app/rclone) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![Installer rclone avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer rclone rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Expliquez en *quelques* (10~15) mots l'utilité de l'app ou ce qu'elle fait (l'objectif est de donner une idée grossière pour des utilisateurs qui naviguent dans un catalogue de 100+ apps)

**Version incluse :** 1.67.0~ynh1

## Captures d’écran

![Capture d’écran de rclone](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

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

## Documentations et ressources

- Site officiel de l’app : <https://rclone.org/>
- Documentation officielle utilisateur : <https://rclone.org/docs/>
- Dépôt de code officiel de l’app : <https://github.com/rclone/rclone>
- YunoHost Store : <https://apps.yunohost.org/app/rclone>
- Signaler un bug : <https://github.com/YunoHost-Apps/rclone_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/rclone_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
ou
sudo yunohost app upgrade rclone -u https://github.com/YunoHost-Apps/rclone_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
