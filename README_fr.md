# Whoogle pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/whoogle.svg)](https://dash.yunohost.org/appci/app/whoogle) ![](https://ci-apps.yunohost.org/ci/badges/whoogle.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/whoogle.maintain.svg)  
[![Installer Whoogle avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=whoogle)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Whoogle rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Description rapide de cette application.

**Version incluse :** 0.2.1

## Captures d'écran

![](https://raw.githubusercontent.com/benbusby/whoogle-search/develop/app/static/img/docs/screenshot_desktop.jpg)

## Démo

* [Démo officielle](Lien vers un site de démonstration de cette application.)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/whoogle%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/whoogle%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/whoogle/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/whoogle_ynh/issues
 * Site de l'application : https://benbusby.com/projects/whoogle-search/
 * Dépôt de l'application principale : https://github.com/benbusby/whoogle-search
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
ou
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```
