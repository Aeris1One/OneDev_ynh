# OneDev app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/OneDev.svg)](https://dash.yunohost.org/appci/app/OneDev) ![](https://ci-apps.yunohost.org/ci/badges/OneDev.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/OneDev.maintain.svg)  
[![Install OneDev with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=OneDev)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install OneDev quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Super Easy All-In-One DevOps Platform with Issue Tracking, Git Management, Pull Request, and Build Farm. Simple yet Powerful.

**Shipped version:** 4.2.5

## Screenshots

![](https://user-images.githubusercontent.com/29739547/115375224-de9b0100-a1cd-11eb-9977-7d1201cbc519.png)

## Demo

* [Official demo](https://code.onedev.io/projects/)
*Note : This is not a demo ! This is the official website which is powered by OneDev software.*

## Configuration

From the admin panel of OneDev

## Documentation

 * Official documentation: https://code.onedev.io/projects/onedev-manual
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? *Not at the moment, maybe in the future*
Can the app be used by multiple users? *Yes*

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/OneDev.svg)](https://ci-apps.yunohost.org/ci/apps/OneDev/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/OneDev.svg)](https://ci-apps-arm.yunohost.org/ci/apps/OneDev/)

## Limitations

* No known limitations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/OneDev_ynh/issues
 * App website: https://onedev.io/
 * Upstream app repository: https://code.onedev.io/projects/onedev-server
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing --debug
or
sudo yunohost app upgrade OneDev -u https://github.com/YunoHost-Apps/OneDev_ynh/tree/testing --debug
```
