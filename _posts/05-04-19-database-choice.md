---
title:  Database Choice
isChild: true
anchor:  database-choice
---

##  Database Choice {#database-choice}

### Polyglot Persistence

Is a practice of using different data storage technologies for different kinds of data. Eloquent ORM can support multiple database for a reason, so don't limit yourself to MySQL.

- It is RECOMMENDED to use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB){:target="_blank"} for records that have attributes that vary a lot. For example, in an inventory system, an office supplies product might have a different set of fields compared to vehicle and auto supplies.

- It is RECOMMENDED to use [ElasticSearch](https://github.com/elasticquent/Elasticquent){:target="_blank"} for high volume data searching and indexing.

- It is RECOMMENDED to use [Neo4J](https://github.com/Vinelab/NeoEloquent){:target="_blank"} for applications that require complex relationships between models. For example a multi-level networking application, social network site and similar apps.

From this [article](https://martinfowler.com/bliki/PolyglotPersistence.html){:target="_blank"}, here  is a sample breakdown of different databases being used by a retailer company

![Sample Company](/images/polyglot.png)

