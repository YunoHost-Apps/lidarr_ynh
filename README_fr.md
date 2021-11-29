# Lidarr pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/lidarr.svg)](https://dash.yunohost.org/appci/app/lidarr) ![](https://ci-apps.yunohost.org/ci/badges/lidarr.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/lidarr.maintain.svg)  
[![Installer Lidarr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lidarr)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Lidarr rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Gestionnaire de discothèque pour utilisateurs de Usenet et BitTorrent

**Version incluse :** 0.8.1.2135~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot.jpg)

## Avertissements / informations importantes

* Les architectures compatibles sont `arm`, `arm64`, et `amd64`
* Le contrôle de l'accès se fait avec le système de permissions de YunoHost.
  * L'API (`domain.tld/path/api`) est accessible aux visiteurs pour permettre le contrôle via des clients externes.
* L'application utilise les dossiers multimédia de YunoHost, elle a donc accès en écriture aux dossiers utilisateurs et communs de `/home/yunohost.multimedia`. Après installation, vous pourrez choisir ces dossiers pour y stocker vos médias.

## Documentations et ressources

* Site officiel de l'app : https://lidarr.audio
* Documentation officielle de l'admin : https://wiki.servarr.com/Lidarr
* Dépôt de code officiel de l'app : https://github.com/Lidarr/Lidarr
* Documentation YunoHost pour cette app : https://yunohost.org/app_lidarr
* Signaler un bug : https://github.com/YunoHost-Apps/lidarr_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade lidarr -u https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps