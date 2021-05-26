# HumHub pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/humhub.svg)](https://dash.yunohost.org/appci/app/humhub) ![](https://ci-apps.yunohost.org/ci/badges/humhub.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/humhub.maintain.svg)  
[![Installer HumHub avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=humhub)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install HumHub quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

Une plate-forme de réseau social open source avec une grande variété de cas d'utilisation en tant qu'intranet social, plate-forme de communauté ou de collaboration. HumHub se compose d'une application principale, qui peut être étendue grâce à des modules supplémentaires et ajustée à vos besoins par de nombreuses options de configuration.

**Version incluse:** 1.8.2~ynh1

**Démo :** https://www.humhub.com/en

## Captures d'écran

![](./doc/screenshots/app_small.png)

## Avertissements / informations importantes

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

## Documentations et ressources

* Site officiel de l'app : https://www.humhub.org
* Documentation officielle utilisateur : https://docs.humhub.org
* Documentation officielle de l'admin : https://docs.humhub.org/docs/admin/introduction
* Dépôt de code officiel de l'app :  https://github.com/humhub/humhub/
* Documentation YunoHost pour cette app : https://yunohost.org/app_humhub
* Signaler un bug: https://github.com/YunoHost-Apps/humhub_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/humhub_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/humhub_ynh/tree/testing --debug
or
sudo yunohost app upgrade humhub -u https://github.com/YunoHost-Apps/humhub_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps