# Simple Torrent for YunoHost

[![Integration level](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)  
[![Install Simple Torrent with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent/)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Simple Torrent quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Simple Torrent is a self-hosted remote torrent client, written in Go (golang). Started torrents remotely, download sets of files on the local disk of the server, which are then retrievable or streamable via HTTP.

**Shipped version:** 1.2.17

## Screenshots

![](https://user-images.githubusercontent.com/1033514/64239393-bdbb6480-cf32-11e9-9269-d8d10e7c0dc7.png)

## Configuration

Most of the items can be edited in Web-UI on the fly in the config board.

You can also configure Simple Torrent by editing this file `/var/www/simple-torrent/config.json` using the [documentation](https://github.com/boypt/simple-torrent/wiki/Config-File).

## Documentation

 * Official documentation: https://github.com/boypt/simple-torrent/wiki
 * YunoHost documentation: https://yunohost.org/en/app_simple-torrent

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **No**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/simple-torrent%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/simple-torrent/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/simple-torrent%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/simple-torrent/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/simple-torrent_ynh/issues
 * Upstream app repository: https://github.com/boypt/simple-torrent
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
or
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```
