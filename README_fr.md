# Slingcode pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/slingcode.svg)](https://dash.yunohost.org/appci/app/slingcode) ![](https://ci-apps.yunohost.org/ci/badges/slingcode.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/slingcode.maintain.svg)  
[![Install Slingcode with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=slingcode)

*[Read this Slingcode in english.](./README.md)* 

> *Ce package vous permet d’installer Slingcode rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Slingcode est un éditeur de code contenu dans un unique fichier HTML. Il n'a pas de composant serveur, ce qui signifie que toutes vos données sont stockées dans le cache de votre navigateur. Cependant, il est toujours possible de créer des applications Web, de les exécuter, de les exporter et même de les partager en peer-to-peer.

**Version incluse :** 0.2.0

## Captures d’écran

![](sources/Screenshot.png)

## Démo

* [Démo officielle](https://slingcode.net/slingcode.html)

## Documentation

 * Documentation officielle : https://slingcode.net/screencasts.html

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/slingcode%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/slingcode/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/slingcode%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/slingcode/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/slingcode_ynh/issues
 * Site de l'application : https://slingcode.net/
 * Dépôt de l’application principale : https://github.com/chr15m/slingcode
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
or
sudo yunohost app upgrade slingcode -u https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
```
