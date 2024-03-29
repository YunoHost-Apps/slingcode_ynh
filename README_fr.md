<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Slingcode pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/slingcode.svg)](https://dash.yunohost.org/appci/app/slingcode) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/slingcode.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/slingcode.maintain.svg)

[![Installer Slingcode avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=slingcode)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Slingcode rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Slingcode est un éditeur de code contenu dans un unique fichier HTML. Il n'a pas de composant serveur, ce qui signifie que toutes vos données sont stockées dans le cache de votre navigateur. Cependant, il est toujours possible de créer des applications Web, de les exécuter, de les exporter et même de les partager en peer-to-peer.

### Caractéristiques :

- Vous pouvez créer, exécuter et partager des applications Web avec.
- Vous n'avez pas besoin d'outils compliqués pour l'utiliser, juste un navigateur Web.
- Vous n'avez pas besoin d'un serveur, d'un hébergement ou d'un certificat SSL pour exécuter les applications Web.
- Vous pouvez mettre Slingcode sur un site Web, l'exécuter à partir d'une clé USB, d'un ordinateur portable ou d'un téléphone, et il n'a pas besoin d'une connexion Internet pour fonctionner.
- Vous pouvez "ajouter à l'écran d'accueil" dans le navigateur de votre téléphone pour accéder facilement à votre bibliothèque de programmes lors de vos déplacements.
- Vous pouvez partager des applications peer-to-peer sur WebTorrent.
- C'est privé. Vous ne partagez que ce que vous choisissez. 


**Version incluse :** 0.2.2~ynh5

**Démo :** <https://slingcode.net/slingcode.html>

## Captures d’écran

![Capture d’écran de Slingcode](./doc/screenshots/Screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://slingcode.net/>
- Documentation officielle utilisateur : <https://slingcode.net/screencasts.html>
- Dépôt de code officiel de l’app : <https://github.com/chr15m/slingcode>
- YunoHost Store : <https://apps.yunohost.org/app/slingcode>
- Signaler un bug : <https://github.com/YunoHost-Apps/slingcode_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
ou
sudo yunohost app upgrade slingcode -u https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
