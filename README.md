# Bases de données: MariaDB pour SQL, MongoDB pour NoSQL; et Données Massives

**Objectif:** analyser les besoins à partir du modèle conceptuel et déployer la base de données jusqu’à la mise en production.

## SQL ou BD relationnelle

| Déployer une BD relationnelle |    |
|:---|:---|
| Établir le modèle conceptuel avec ERDPlus | <img src="img/physical_schema.jpg" alt="" width="300"> |
| Étudier des études de cas: différents contextes, besoins... |    |
| Maitriser la cardinalité | <img src="img/cardinality.jpg" alt="" width="300">   |
| Générer le modèle physique avec ERDPlus (tables, champs, clés) | <img src="img/relational_schema.jpg" alt="" width="300"> |
| Installer tous les outils | <img src="img/mariadb_mysql.jpg" alt="" width="300">   |
| Lancer le serveur (myslqd) | <img src="img/server.jpg" alt="" width="300">   |
| Lancer un ou plusieurs clients (mysql), utiliser les CLI... |    |
| Utiliser Workbench | <img src="img/workbench.jpg" alt="" width="300">   |
| Utiliser HeidiSQL | <img src="img/heidisql.jpg" alt="" width="300">   |
| Créer une BD avec un code source SQL et saisir les données...  |    |
| Réaliser des requêtes (*CRUD* ou *Create Retrieve Update Delete*) | <img src="img/crud.jpg" alt="" width="300">   |
| Réaliser des opérations: opérateurs, *aggregate*, *view*, *join* | <img src="img/sql-joins.jpg" alt="" width="300">   |
| Réaliser d'autres opérations: fonctions, index, *save*, *restore*, etc. |   |

## NoSQL

Découvrir les bases de données NoSQL:

- Document: MongoDB, Elasticsearch, CouchDB, BaseX
- Graph: Neo4j, RediGraph, OrientDB
- Wide Column Stores: Cassandra, CosmoDB, Bigtable, HBase 
- Key:Value: Aerospike, Berkeley DB, Couchbase, DynamoDB, Memcached, Riak, Redis

<img src="img/NoSQL.jpg" alt="" width="400">

Faire quelques formation Mongo University:

- M001: MongoDB Basics
- M100: MongoDB for SQL Pros
- M112: Diagnostic Thinking
- A300: Atlas Security

| Déployer MongoDB |    |
|:---|:---|
| Découvrir les schémas et les patrons: différents contextes, besoins... | <img src="img/patterns_matrix.jpg" alt="" width="300"> |
| Installer tous les outils | <img src="img/mongodb.jpg" alt="" width="300"> |
| Lancer le serveur (mongod) | <img src="img/server.jpg" alt="" width="300"> |
| Lancer un ou plusieurs clients (mongo, mongosh), utiliser les CLI... |  |
| Utiliser Compass | <img src="img/compass.jpg" alt="" width="300"> |
| Créer une BD locales et saisir les données... |  |
| Travailler avec Atlas, créer une grappe (*cluster*) et saisir les données... | <img src="img/atlas.jpg" alt="" width="300"> |
| Réaliser des requêtes (CRUD ou Create Retrieve Update Delete) | <img src="img/crud.jpg" alt="" width="300"> |
| Réaliser des opérations: opérateurs $, projections, index, agrégation |  |
| Réaliser d'autres opérations: *import*, *save* (CSV, JSON), *dump*, *restore* (BSON) |  |
