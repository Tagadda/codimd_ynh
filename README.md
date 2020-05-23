# CodiMD for YunoHost

[![Integration level](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Install CodiMD with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=codimd)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install CodiMD quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Collaborative editor to work on notes written in Markdown.

**Shipped version:** 1.6.0

## Screenshots

![](https://demo.codimd.org/screenshot.png)

## Demo

* [Official demo](https://demo.codimd.org/)

## Configuration

If you need to configure CodiMD, you can tweak `/var/www/codimd/config.json` file using this [documentation](https://github.com/codimd/server/blob/master/docs/configuration-config-file.md)

## Documentation

 * Official documentation: https://hackmd.io/c/codimd-documentation/
 * YunoHost documentation: https://yunohost.org/#/app_codimd

## YunoHost specific features

#### Multi-users support

* Is LDAP supported? No
* Can the app be used by multiple users? Yes

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/codimd/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/codimd/)

## Limitations

**Status**: In progress, do *not* consider this app as stable and fully working (yet)

## Additional information

## Links

 * Report a bug: https://github.com/YunoHost-Apps/codimd_ynh/issues
 * Upstream app repository: https://github.com/codimd/server/
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
or
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```
