<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# InfluxDB v2 voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/influxdb_v2)](https://ci-apps.yunohost.org/ci/apps/influxdb_v2/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/influxdb_v2)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/influxdb_v2)

[![InfluxDB v2 met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je InfluxDB v2 snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

InfluxDB is a time series database designed to handle high volumes of time-based data, such as metrics, events, and analytics from software, IoT devices, or other sources.

## Features

- **Unified Experience**: InfluxDB delivers a Smart Data Platform with everything you need in a single binary. This includes a multi-tenanted time series database, user interface, dashboarding tools, background processing, and a monitoring agent.

- **Developer Productivity**: The platform is optimized for developer productivity. Everything in InfluxDB, from data ingestion to querying and visualization, is accessible through a unified API. This ensures a faster development cycle as all platform components can be programmatically accessed and controlled.

- **Deep Insights**: Structure your queries and separate common logic into functions and libraries. Enrich your time series data with other SQL data stores or cloud-based data stores.

- **APIs & Toolset**: InfluxDB offers a RESTful API and a range of client libraries for various programming languages. It also provides Telegraf, an open-source collector agent with over 300+ plugins, and Flux, a functional language designed specifically for time series data.

- **High Performance**: The platform is optimized for large data workloads, offering high throughput and series cardinality. It supports both batch and streaming data ingestion from millions of sources.

- **Community & Ecosystem**: Supported by a vast community, InfluxDB integrates with various tools and platforms. This includes connectors to Grafana, Google Data Studio, and more. It also offers InfluxDB Templates to share monitoring solutions with the community.

- **User Interface**: A top-tier UI is provided, featuring a Data Explorer, dashboarding tools, and a script editor. This ensures quick data browsing, visualization, and Flux script development.

By leveraging InfluxDB v2, users can gain deeper insights from their time series data, ensuring efficient data analysis and visualization. Whether you're a developer looking for a streamlined platform or an organization aiming for data-driven decisions, InfluxDB v2 is the tool to consider.



**Geleverde versie:** 2.7.1~ynh2

## Schermafdrukken

![Schermafdrukken van InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.influxdata.com/>
- Officiele beheerdersdocumentatie: <https://docs.influxdata.com/influxdb/v2.0/>
- YunoHost-store: <https://apps.yunohost.org/app/influxdb_v2>
- Meld een bug: <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
of
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
