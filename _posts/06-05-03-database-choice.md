---
anchor: right-database-choice
isChild: true
anchor:  right-database-choice
---

## Choose right database for the job at hand. {#right-database-choice}

Eloquent can support multiple databases for a reason - Don't limit yourself to MySQL.

 Use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB) for records that has attributes that varies a lot. For example, in an inventory system, an office supplies product might have a different set of fields compared to vehicle and auto supplies.

 Use [ElasticSearch](https://github.com/elasticquent/Elasticquent) for high volume data searching and indexing. It is also useful on systems that requires sharding of data in multiple machines which is very huge to fit in a single replica.

 Use [Neo4J](https://github.com/Vinelab/NeoEloquent) for applications that requires complex relationships between models. For example a multi-level networking application, social network site and alike. Although you can do the same in MySQL, the amount of joins when you go beyond 2-level parent-child relationships will be unbearable in any production environment.