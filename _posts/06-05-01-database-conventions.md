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


### Configuration

DONT hardcode database credentials anywhere in your application. Create an .env file and put the database credentials there. Remember to not commit the .env file into any Git repository.

 