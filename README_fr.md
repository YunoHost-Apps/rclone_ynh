<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Rclone pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/rclone.svg)](https://dash.yunohost.org/appci/app/rclone) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/rclone.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/rclone.maintain.svg)

[![Installer Rclone avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rclone)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Rclone rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Rclone est un programme en ligne de commande permettant de gérer des fichiers sur le stockage cloud. Il s'agit d'une alternative riche en fonctionnalités aux interfaces de stockage Web des fournisseurs de cloud. Plus de 70 produits de stockage cloud prennent en charge rclone, notamment les magasins d'objets S3, les services de stockage de fichiers professionnels et grand public, ainsi que les protocoles de transfert standard.

**Version incluse :** 1.67.0~ynh1

## Captures d’écran

![Capture d’écran de Rclone](./doc/screenshots/example.jpg)

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
