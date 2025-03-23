<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# InfluxDB v2 pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/influxdb_v2)](https://ci-apps.yunohost.org/ci/apps/influxdb_v2/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/influxdb_v2)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/influxdb_v2)

[![Installer InfluxDB v2 avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=influxdb_v2)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer InfluxDB v2 rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

InfluxDB est une base de données de séries temporelles conçue pour gérer des volumes élevés de données temporelles, comme des métriques, des événements et des analyses provenant de logiciels, d'appareils IoT, ou d'autres sources.

## Fonctionnalités

- **Expérience unifiée** : InfluxDB offre une plateforme de données intelligente avec tout ce dont vous avez besoin dans un binaire unique. Cela comprend une base de données de séries temporelles multi-tenant, une interface utilisateur, la création de tableaux de bord, un traitement en arrière-plan et un agent de surveillance.

- **Productivité des développeurs** : La plateforme est optimisée pour la productivité des développeurs. Tout dans InfluxDB, de l'ingestion des données à la visualisation en passant par l'interrogation, est accessible via une API unifiée. Cela permet d'accélérer le cycle de développement car tous les composants de la plateforme sont accessibles et contrôlés par programmation.

- **Des connaissances approfondies** : Structurez vos requêtes et séparez la logique commune en fonctions et en bibliothèques. Enrichissez vos données de séries temporelles avec d'autres magasins de données SQL ou des magasins de données basés sur le cloud.

- **API et ensemble d'outils** : InfluxDB propose une API RESTful et une gamme de bibliothèques clientes pour différents langages de programmation. Il fournit également Telegraf, un agent collecteur open-source avec plus de 300 plugins, et Flux, un langage fonctionnel conçu spécifiquement pour les données de séries temporelles.

- **Haute performance** : La plateforme est optimisée pour les charges de travail de données volumineuses, offrant un débit élevé et la cardinalité des séries. Elle prend en charge l'ingestion de données par lots et en continu à partir de millions de sources.

- **Communauté et écosystème** : Soutenu par une vaste communauté, InfluxDB s'intègre à divers outils et plateformes. Cela inclut des connecteurs pour Grafana, Google Data Studio, et bien plus encore. Il propose également des modèles InfluxDB à partager avec la communauté.

- **Interface utilisateur** : Une interface utilisateur est fournie, avec un explorateur de données, des outils de tableau de bord et un éditeur de scripts. Cela permet de naviguer rapidement dans les données, de les visualiser et de développer des scripts Flux.

En tirant parti d'InfluxDB v2, les utilisateurs peuvent obtenir des informations plus approfondies sur leurs données de séries temporelles, en garantissant une analyse et une visualisation efficaces des données. Que vous soyez un développeur à la recherche d'une plateforme rationalisée ou une organisation visant à prendre des décisions basées sur les données, InfluxDB v2 est l'outil qu'il vous faut.

**Version incluse :** 2.7.1~ynh2

## Captures d’écran

![Capture d’écran de InfluxDB v2](./doc/screenshots/influxdb_v2_data_explorer.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.influxdata.com/>
- Documentation officielle de l’admin : <https://docs.influxdata.com/influxdb/v2.0/>
- YunoHost Store : <https://apps.yunohost.org/app/influxdb_v2>
- Signaler un bug : <https://github.com/YunoHost-Apps/influxdb_v2_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
ou
sudo yunohost app upgrade influxdb_v2 -u https://github.com/YunoHost-Apps/influxdb_v2_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
