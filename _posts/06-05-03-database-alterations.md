---
anchor: db_alterations
isChild: true
anchor:  db_alterations
---

## Changing tables, index or inserting sample data. {#db_alterations}

DONT create tables or index directly via PHPMyAdmin or console. Use [database migration](https://laravel.com/docs/5.2/migrations#writing-migrations) to create table, add/alter any fields, and commit those to Git repository. 

DONT pass directly the database export (sql files ) to your colleagues in able to share your database changes, let them run the migration files you committed to the repository.

DONT insert fake values directly to the database for testing purposes. create [Seeder](https://laravel.com/docs/5.2/seeding) files to populate your database.