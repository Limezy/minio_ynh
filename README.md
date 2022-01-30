<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# MinIO server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/minio.svg)](https://dash.yunohost.org/appci/app/minio) ![](https://ci-apps.yunohost.org/ci/badges/minio.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/minio.maintain.svg)  
[![Install MinIO server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minio)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install MinIO server quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Some long and extensive description of what the app is and does, lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Features

- Ut enim ad minim veniam, quis nostrud exercitation ullamco ;
- Laboris nisi ut aliquip ex ea commodo consequat ;
- Duis aute irure dolor in reprehenderit in voluptate ;
- Velit esse cillum dolore eu fugiat nulla pariatur ;
- Excepteur sint occaecat cupidatat non proident, sunt in culpa."


**Shipped version:** 2022.01.28~ynh1



## Screenshots

![](./doc/screenshots/minio-browser.jpg)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentation and resources

* Official app website: https://min.io
* Official admin documentation: https://docs.min.io/
* Upstream app code repository: https://github.com/minio/minio
* YunoHost documentation for this app: https://yunohost.org/app_minio
* Report a bug: https://github.com/YunoHost-Apps/minio_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/minio_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minio_ynh/tree/testing --debug
or
sudo yunohost app upgrade minio -u https://github.com/YunoHost-Apps/minio_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps