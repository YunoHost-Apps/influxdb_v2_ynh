<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# InfluxDB v2 para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/influxdb_v2.svg)](https://dash.yunohost.org/appci/app/influxdb_v2) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/influxdb_v2.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/influxdb_v2.maintain.svg)

[![Instalar InfluxDB v2 con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar InfluxDB v2 de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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



**Versión proporcionada:** 2.7.1~ynh1

## Capturas de pantalla

![Captura de pantalla de InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Documentación e recursos

- Web oficial da app: <https://www.influxdata.com/>
- Documentación oficial para admin: <https://docs.influxdata.com/influxdb/v2.0/>
- Tenda YunoHost: <https://apps.yunohost.org/app/influxdb_v2>
- Informar dun problema: <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
ou
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
