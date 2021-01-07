# Leed for YunoHost

[![Integration level](https://dash.yunohost.org/integration/leed.svg)](https://dash.yunohost.org/appci/app/leed) ![](https://ci-apps.yunohost.org/ci/badges/leed.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/leed.maintain.svg)  
[![Install Leed with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=leed)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install leed quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Leed (short for Light Feed) is a minimalist RSS/ATOM aggregator which offers fast RSS consultation and non-intrusive features.

**Shipped version:** 1.8.3

## Screenshots

![](http://projet.idleman.fr/leed/data/leed1.jpg)

## Demo

No demo available.

## Configuration

Use the admin panel of your Leed to configure this app.

## Documentation

* YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

* Login secured by Fail2Ban

#### Multi-users support

Not supported.

#### Supported architectures

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/leed%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/leed/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/leed%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/leed/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/leed_ynh/issues
 * Leed website: http://leed.idleman.fr/
 * Leed repository: http://git.idleman.fr/LeedRSS/Leed
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/leed_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/leed_ynh/tree/testing --debug
or
sudo yunohost app upgrade leed -u https://github.com/YunoHost-Apps/leed_ynh/tree/testing --debug
```
