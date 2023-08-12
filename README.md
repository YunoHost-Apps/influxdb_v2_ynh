<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# InfluxDB v2 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/influxdb_v2.svg)](https://dash.yunohost.org/appci/app/influxdb_v2) ![Working status](https://ci-apps.yunohost.org/ci/badges/influxdb_v2.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/influxdb_v2.maintain.svg)

[![Install InfluxDB v2 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install InfluxDB v2 quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

# InfluxDB v2

InfluxDB is a time series database designed to handle high volumes of time-based data, such as metrics, events, and analytics from software, IoT devices, or other sources.

## Features

- **Unified Experience**: InfluxDB delivers a Smart Data Platform with everything you need in a single binary. This includes a multi-tenanted time series database, user interface, dashboarding tools, background processing, and a monitoring agent.

- **Developer Productivity**: The platform is optimized for developer productivity. Everything in InfluxDB, from data ingestion to querying and visualization, is accessible through a unified API. This ensures a faster development cycle as all platform components can be programmatically accessed and controlled.

- **Deep Insights**: Structure your queries and separate common logic into functions and libraries. Enrich your time series data with other SQL data stores or cloud-based data stores.

- **APIs & Toolset**: InfluxDB offers a RESTful API and a range of client libraries for various programming languages. It also provides Telegraf, an open-source collector agent with over 300+ plugins, and Flux, a functional language designed specifically for time series data.

- **High Performance**: The platform is optimized for large data workloads, offering high throughput and series cardinality. It supports both batch and streaming data ingestion from millions of sources.

- **Community & Ecosystem**: Supported by a vast community, InfluxDB integrates with various tools and platforms. This includes connectors to Grafana, Google Data Studio, and more. It also offers InfluxDB Templates to share monitoring solutions with the community.

- **User Interface**: A top-tier UI is provided, featuring a Data Explorer, dashboarding tools, and a script editor. This ensures quick data browsing, visualization, and Flux script development.

- **Edge & Distributed Environments**: InfluxDB is optimized for edge and distributed environments, allowing data collection, processing, and analysis from edge devices.

By leveraging InfluxDB v2, users can gain deeper insights from their time series data, ensuring efficient data analysis and visualization. Whether you're a developer looking for a streamlined platform or an organization aiming for data-driven decisions, InfluxDB v2 is the tool to consider.



**Shipped version:** 2.7.1~ynh1

## Screenshots

![Screenshot of InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Documentation and resources

* Official app website: <https://www.influxdata.com/>
* Official admin documentation: <https://docs.influxdata.com/influxdb/v2.0/>
* YunoHost documentation for this app: <https://yunohost.org/app_influxdb_v2>
* Report a bug: <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
or
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>