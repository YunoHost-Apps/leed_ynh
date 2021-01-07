# Leed pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/leed.svg)](https://dash.yunohost.org/appci/app/leed) ![](https://ci-apps.yunohost.org/ci/badges/leed.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/leed.maintain.svg)  
[![Installer Leed avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=leed)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer leed rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé
Leed (contraction de Light Feed) est un agrégateur RSS/ATOM minimaliste qui permet la consultation de flux RSS de manière rapide et non intrusive.

**Version embarquée :** 1.8.3

## Captures d'écran

![](http://projet.idleman.fr/leed/data/leed1.jpg)

## Démo

Aucune démo pour cette application.

## Configuration

Utiliser le panneau d'administration de votre Jenkins pour configurer cette application.

## Documentation

 * Documentation YunoHost : Il n'y a pas d'autre documentation, n'hésitez pas à contribuer.

## Fonctionnalités spécifiques à YunoHost

* Login sécurisé par Fail2Ban

#### Support multi-utilisateurs

Non supportée.

#### Architectures supportées.

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/leed%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/leed/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/leed%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/leed/)

## Informations additionnelles

## Liens

 * Reporter un bug : https://github.com/YunoHost-Apps/leed_ynh/issues
 * Site de Leed : http://leed.idleman.fr/
 * Dépôt de Leed : http://git.idleman.fr/LeedRSS/Leed
 * Site de YunoHost : https://yunohost.org/

---

## Informations à l'intention des développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/leed_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/leed_ynh/tree/testing --debug
ou
sudo yunohost app upgrade leed -u https://github.com/YunoHost-Apps/leed_ynh/tree/testing --debug
```
