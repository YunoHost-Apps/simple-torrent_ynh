# Simple Torrent pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simpletorrent) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)  
[![Installer Simple Torrent avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Simple Torrent rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Simple Torrent est un client torrent distant auto-hébergé, écrit en Go (golang). Démarrez des torrents à distance, téléchargez des ensembles de fichiers sur le disque local du serveur, qui sont ensuite récupérables ou diffusables via HTTP.

**Version incluse :** 1.2.12

## Captures d'écran

![](https://user-images.githubusercontent.com/1033514/64239393-bdbb6480-cf32-11e9-9269-d8d10e7c0dc7.png)

## Configuration

La plupart des éléments peuvent être modifiés à la volée dans Web-UI dans la page de configuration.

Vous pouvez configurer Simple Torrent en modifiant le fichier `/var/www/simple-torrent/config.json` en vous aidant de la [documentation](https://github.com/boypt/simple-torrent/wiki/Config-File).

## Documentation

 * Documentation officielle : https://github.com/boypt/simple-torrent/wiki
 * Documentation YunoHost : https://yunohost.org/#/app_simple-torrent_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Non**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/simple-torrent%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/simple-torrent/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/simple-torrent%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/simple-torrent/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/simple-torrent_ynh/issues
 * Dépôt de l'application principale : https://github.com/boypt/simple-torrent
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
ou
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```
