<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Plume for YunoHost

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume) ![Working status](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Install Plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Plume quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Shipped version:** 0.7.2~ynh2

**Demo:** https://joinplu.me/#instances

## Screenshots

![Screenshot of Plume](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://joinplu.me/>
* Official admin documentation: <https://docs.joinplu.me/>
* Upstream app code repository: <https://github.com/Plume-org/Plume>
* YunoHost Store: <https://apps.yunohost.org/app/plume>
* Report a bug: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
or
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
