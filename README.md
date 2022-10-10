<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Trilium Notes for YunoHost (forked for the HW2K website)

[![Integration level](https://dash.yunohost.org/integration/trilium.svg)](https://dash.yunohost.org/appci/app/trilium) ![Working status](https://ci-apps.yunohost.org/ci/badges/trilium.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/trilium.maintain.svg)  
[![Install Trilium Notes with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=trilium)


> *This package allows you to install Trilium Notes quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Trilium Notes is an Evernote-like hierarchical note taking application with many advanced features, focused on building a large personal knowledge base.


**Shipped version:** 0.55.1~ynh1


## Screenshots

![Screenshot of Trilium Notes](./doc/screenshots/screenshot.png)
![Screenshot of Trilium Notes](./doc/screenshots/example.jpg)

## Disclaimers / important information

## Configuration

You will be asked to choose a username and password when you first access the app. You can configure Trillium from the settings menu of the app interface.

## Documentation and resources

* Official app website: <https://github.com/zadam/trilium>
* Official admin documentation: <https://github.com/zadam/trilium/wiki>
* Upstream app code repository: <https://github.com/zadam/trilium>
* YunoHost documentation for this app: <https://yunohost.org/app_trilium>
* Report a bug: <https://github.com/YunoHost-Apps/trilium_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/7357-2022/hw2k_trilium_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/7357-2022/hw2k_trilium_ynh/tree/testing --debug
```
or
```
sudo yunohost app upgrade trilium -u https://github.com/7357-2022/hw2k_trilium_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
