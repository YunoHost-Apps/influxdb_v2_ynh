<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# InfluxDB v2 para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/influxdb_v2)](https://ci-apps.yunohost.org/ci/apps/influxdb_v2/)
![Estado funcional](https://apps.yunohost.org/badge/state/influxdb_v2)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/influxdb_v2)

[![Instalar InfluxDB v2 con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarInfluxDB v2 rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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



**Versión actual:** 2.7.1~ynh2

## Capturas

![Captura de InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Documentaciones y recursos

- Sitio web oficial: <https://www.influxdata.com/>
- Documentación administrador oficial: <https://docs.influxdata.com/influxdb/v2.0/>
- Catálogo YunoHost: <https://apps.yunohost.org/app/influxdb_v2>
- Reportar un error: <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
o
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
