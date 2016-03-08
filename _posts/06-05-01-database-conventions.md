---
anchor: database_conventions
---

# Database Conventions {#database_conventions_title}


### Eloquent can support multiple Database for a reason - Don't limit yourself to MySQL.

 Use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB) for records that has attributes that varies a lot. For example, in an inventory system, an office supplies product might have a different set of fields compared to vehicle and auto supplies.

 Use [ElasticSearch](https://github.com/elasticquent/Elasticquent) for high volume data searching and indexing.

 Use [Neo4J](https://github.com/Vinelab/NeoEloquent) for applications that requires complex relationships between models. For example a multi-level networking application, social network site and alike.
