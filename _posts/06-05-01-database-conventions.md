---
anchor: database_conventions
---

# Database Conventions {#database_conventions_title}


### Table and field naming

Table and field names MUST be lowercase and use [Snake Case](https://en.wikipedia.org/wiki/Snake_case).

Table name should use the plural form of the actual real life object it is storing. Like for example, the table name for blog posts should be *posts* not *post*.


### Changing tables, index or inserting sample data. 

DONT create tables or index directly via PHPMyAdmin or console. Use [database migration](https://laravel.com/docs/5.2/migrations#writing-migrations) to create table, add/alter any fields, and commit those to Git repository. 

DONT pass directly the database export (sql files ) to your colleagues in able to share your database changes, let them run the migration files you committed to the repository.

DONT insert fake values directly to the database for testing purposes. create [Seeder](https://laravel.com/docs/5.2/seeding) files to populate your database.


### Eloquent can support multiple Database for a reason - Don't limit yourself to MySQL.

 Use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB) for records that has attributes that varies a lot. For example, in an inventory system, an office supplies product might have a different set of fields compared to vehicle and auto supplies.

 Use [ElasticSearch](https://github.com/elasticquent/Elasticquent) for high volume data searching and indexing.

 Use [Neo4J](https://github.com/Vinelab/NeoEloquent) for applications that requires complex relationships between models. For example a multi-level networking application, social network site and alike.
