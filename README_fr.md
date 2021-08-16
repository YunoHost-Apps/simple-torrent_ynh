# Simple Torrent pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)  
[![Installer Simple Torrent avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Simple Torrent rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Client torrent distant auto-hébergé

**Version incluse :** 1.3.4~ynh1



## Captures d'écran

![](./doc/screenshots/64239393-bdbb6480-cf32-11e9-9269-d8d10e7c0dc7.png)
![](./doc/screenshots/.DS_Store)

## Avertissements / informations importantes

## Configuration

La plupart des éléments peuvent être modifiés à la volée dans Web-UI dans la page de configuration.

Vous pouvez configurer Simple Torrent en modifiant le fichier `/var/www/simple-torrent/config.yml` en vous aidant de la [documentation](https://github.com/boypt/simple-torrent/wiki/Config-File).

## Limitations

- Cette application ne peut pas être installée sur une machine ARM 32 bits.

## Documentations et ressources

* Site officiel de l'app : https://github.com/boypt/simple-torrent
* Documentation officielle de l'admin : https://github.com/boypt/simple-torrent/wiki
* Dépôt de code officiel de l'app : https://github.com/boypt/simple-torrent
* Documentation YunoHost pour cette app : https://yunohost.org/app_simple-torrent
* Signaler un bug : https://github.com/YunoHost-Apps/simple-torrent_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
ou
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps