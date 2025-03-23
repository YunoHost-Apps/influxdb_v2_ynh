<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# InfluxDB v2 dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/influxdb_v2)](https://ci-apps.yunohost.org/ci/apps/influxdb_v2/)
![Status działania](https://apps.yunohost.org/badge/state/influxdb_v2)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/influxdb_v2)

[![Zainstaluj InfluxDB v2 z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację InfluxDB v2 na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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



**Dostarczona wersja:** 2.7.1~ynh2

## Zrzuty ekranu

![Zrzut ekranu z InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.influxdata.com/>
- Oficjalna dokumentacja dla administratora: <https://docs.influxdata.com/influxdb/v2.0/>
- Sklep YunoHost: <https://apps.yunohost.org/app/influxdb_v2>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
lub
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
