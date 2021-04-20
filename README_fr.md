# Application OneDev pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/OneDev.svg)](https://dash.yunohost.org/appci/app/OneDev) ![](https://ci-apps.yunohost.org/ci/badges/OneDev.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/OneDev.maintain.svg)
[![Installer OneDev avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=OneDev)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer OneDev rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Description rapide de cette application.

**Version incluse :** 4.2.5

## Captures d'écran

![](https://user-images.githubusercontent.com/29739547/115375224-de9b0100-a1cd-11eb-9977-7d1201cbc519.png)

## Démo

* [Démo officielle](https://code.onedev.io/projects/)
*Cette démo... n'est pas une démo, il s'agit du site officiel de documentation et de développement qui fonctionne en utilisant OneDev.*

## Configuration

Via le panneau d'administration accessible via votre compte administrateur défini à l'installation.

## Documentation

 * Documentation officielle : https://code.onedev.io/projects/onedev-manual
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? *Pas pour le moment, peut-être dans le futur*
* L'application peut-elle être utilisée par plusieurs utilisateurs ? *Oui*

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/OneDev.svg)](https://ci-apps.yunohost.org/ci/apps/OneDev/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/OneDev.svg)](https://ci-apps-arm.yunohost.org/ci/apps/OneDev/)

## Limitations

* Aucune limitation connue pour le moment.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/OneDev_ynh/issues
 * Site de l'application : https://onedev.io/
 * Dépôt de l'application principale : https://code.onedev.io/projects/onedev-server
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing --debug
ou
sudo yunohost app upgrade OneDev -u https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing --debug
```
