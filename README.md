# Whoogle for YunoHost

[![Integration level](https://dash.yunohost.org/integration/whoogle.svg)](https://dash.yunohost.org/appci/app/whoogle) ![](https://ci-apps.yunohost.org/ci/badges/whoogle.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/whoogle.maintain.svg)  
[![Install Whoogle with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=whoogle)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Whoogle quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Whoogle is intended to only ever be deployed to private instances by individuals of any background, with as little effort as possible. Prior knowledge of/experience with the command line or deploying applications is not necessary to deploy Whoogle, which isn't the case with Searx. As a result, Whoogle is missing some features of Searx in order to be as easy to deploy as possible.
Whoogle also only uses Google search results, not Bing/Quant/etc, and uses the existing Google search UI to make the transition away from Google search as unnoticeable as possible.

**Shipped version:** 0.2.0

## Screenshots

![](https://raw.githubusercontent.com/benbusby/whoogle-search/develop/app/static/img/docs/screenshot_desktop.jpg)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/whoogle%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/whoogle/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/whoogle%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/whoogle/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/whoogle_ynh/issues
 * App website: https://benbusby.com/projects/whoogle-search/
 * Upstream app repository: https://github.com/benbusby/whoogle-search
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
or
sudo yunohost app upgrade whoogle -u https://github.com/YunoHost-Apps/whoogle_ynh/tree/testing --debug
```
